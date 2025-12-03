People in a social network are connected, and their homogeneity is reflected by the similarity of their attributes. For effective clustering in such a network, the similarities among people
within a cluster must be much higher than the similarities between different clusters. The higher the similarity within a cluster and the greater the difference between clusters, the more
effective the clustering results will be. Traditional clustering algorithms like hierarchical (agglomerative) clustering or k-medoids take distances between objects as input and find
clusters of objects. The distance functions used should comply with the triangle inequality (TI) property, but sometimes this property may be violated, thus negatively impacting the
quality of the generated clusters.
However, in certain scenarios, such as social networks, it is still possible to achieve meaningful clustering even if the TI does not hold. One possibility to find meaningful
clusters are quantum-logic-inspired query languages such as the commuting quantum query language (CQQL). It is the base for the clique-guided non-TI clustering approach, which
is used in this thesis. The CQQL is particularly noteworthy as it allows the formulation of logic-based queries that incorporate both Boolean and similarity conditions. Therefore, it
can be used to derive the similarity value between two objects.
Furthermore, attributes in the network may not have equal impact on similarity and affect the resulting clusters, impacting user satisfaction. CQQL incorporates weights to
express the varying importance of sub-conditions in a query while preserving consistency with Boolean algebra. This enables personalization of results through relevance feedback
(RF), which enhances user interaction with the system. The approach incorporates user feedback to enhance the quality of clusters, finds clusters relevant to user needs, and also
provides alternative possible feedback to the user.
The main challenge of comparing clusterings is that there is no ground truth data associated with this approach to compare to. In such situations, the relevance of any clustering
can be measured based on human judgment. Human-generated gold standard clustering, which is considered to be "correct" in some sense, can be used in this scenario. However,
the question is how to compare the performance of common clustering approaches to that of human-generated gold standard clustering. A noteworthy technique for comparing clusterings involves counting the pairs of objects that are grouped identically in both clusterings. By
doing so, a clustering distance is calculated that measures the dissimilarity between the two clusterings.
To validate the utility of the non-TI clustering approach, experiments are conducted on social networks of different sizes. Three central questions are addressed by the experiments
mentioned: first, is it possible to detect meaningful clusters even though TI violates; second, how does a user interact with the system to provide feedback based on their needs; and
third, how fast do the detected clusters based on the proposed approach converge to the ideal solution during the relevance feedback process?
To sum up, the experiments’ objective is to demonstrate the validity of a theoretical approach. The research findings presented here provide sufficient evidence for detecting
meaningful clusters based on user interaction. Furthermore, the experiments clearly demonstrate that the non-TI clustering approach can be used as an RF technique in clustering.
