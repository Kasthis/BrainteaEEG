# BrainteaEEG
Creation of Network in EEG data, application of Community detection, and EEG analysis

In this study, an EEG dataset containing features such as Differential
Entropy (DE), Power Spectral Density (PSD), and Hemispheric Asymme-
try (ASM) is analyzed. The dataset was recorded from fifteen subjects who
watched fifteen film clips, with the goal of examining how these features might
differ across individuals and emotions. Therefore, an expansive study of the
EEG data in the world of graph theory is undertaken.
Four community detection algorithms, including the Louvain method, the
Girvan-Newman, the Walk-Trap, and the Fast Greedy partition methods, are
employed to assess significant similarities and dissimilarities among the subject
features in the context of networks and communities. More specifically, EEG
network features annotated by gender and emotion are compared.
The analysis reveals that gamma is isolated with no connections. Simi-
larities are found in the brain activity between female and male participants
during the watching of neutral film clips. Additionally, other male and female
testees exhibit beta wave similarities during the watching of the film clip that
evokes sad emotions. The results suggest a more intricate interaction between
emotions and brain activity in the last community, which encompasses mul-
tiple film clips, emotion labels, and brain activity patterns. This community
may indicate a diverse range of emotional experiences and cognitive processes
occurring concurrently.

The SJTU Emotion EEG Dataset (SEED) is a collection of EEG datasets curated by the BCMI laboratory, led by Prof. Bao-Liang Lu. The dataset consists of fifteen film clips carefully selected to elicit coherent emotional responses from participants across positive, neutral, and negative emotions. Each participant experienced fifteen trials, with a 5-second self-assessment period before each film clip and a 15-second rest period between clips. The EEG data was recorded using a 62-channel ESI NeuroScan System. Fifteen Chinese individuals, assigned numerical identifiers, participated in the study. The dataset includes pre-processed EEG data, downsampled to 200 Hz and bandpass filtered, as well as feature-extracted data, focusing on differential entropy, rational asymmetry, differential asymmetry, and power spectral density. The features underwent additional processing for improved accuracy and quality.

Gephi, a powerful network visualization software, plays a crucial role in visualizing the EEG network that has been constructed. The EEG network represents the intricate connections and relationships among various elements derived from the EEG data, such as brain regions or electrodes. By utilizing Gephi's intuitive interface and extensive range of visualization options, it becomes possible to effectively explore and analyze the complex patterns and structures within the EEG network. Gephi's interactive features enable the examination of node attributes, edge weights, and community structures, facilitating a deeper understanding of the underlying connectivity patterns in the EEG data. In summary, Gephi serves as an indispensable tool for visualizing and interpreting the EEG network, enabling researchers to gain valuable insights into the functional connectivity of the brain.
