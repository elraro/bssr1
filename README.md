# Biometric Scores Set

**This dataset has been discontinued.**

Biometric Scores Set - Release 1 (BSSR1) is a set of raw output similarity scores from two c. 2002 face recognition systems and one c. 2004 fingerprint system, operating on frontal faces, and left and right index live-scan fingerprints, respectively. The release includes true multimodal score data, i.e. similarity scores from comparisons of faces and fingerprints of the same people.

The data is intended to allow interested parties to investigate a range of outstanding statistical problems related to biometrics. Particularly the data are suited to the study of score-level fusion-based multimodal, multi-algorithmic, multi-sample and repeated-sample biometrics. In addition, the data is likely to be valuable for other purposes including the development of models of large population identification performance, testing of confidence interval estimators and assessment of the existence of the biometric zoo.

The release contains three partitions described:

**Set 1** is comprised of face and fingerprint scores from the same set of 517 individuals. For each individual, the set contains one score from the comparison of two right index fingerprints, one score from the comparison of two left index fingerprints, and two scores (from two separate matchers) from the comparison of two frontal faces. The fingerprint images and the face images from which these scores were computed are from the same person (i.e. the chimera assumption is not in use) at the same time (and the dates are provided). The non-matching scores from the full cross-comparison are also included.

| Property                                                      | Value                           |
| ------------------------------------------------------------- | ------------------------------- |
| Number of subjects                                            | 517                             |
| Number of fingerprint systems                                 | 2                               |
| Number of face systems                                        | 2                               |
| Number of face images from which scores were obtained         | 2 per subject                   |
| Number of fingerprint images from which scores were obtained  | 4 (2 left, 2 right) per subject |
| Number of scores                                              | 2 * 517 * 517                   |
| Number of similarity files                                    | 2068                            |
| Suggested use in fusion studies                               | Face and finger fusion          |

**Set 2** is comprised of fingerprint scores from one system run on images of 6000 individuals. For each individual, the set contains one score from the comparison of two left index fingerprints, and another from two right index fingerprints. The non-matching scores from the left vs. left and right vs. right cross-comparisons are also included.

| Property                                                      | Value                           |
| ------------------------------------------------------------- | ------------------------------- |
| Number of subjects                                            | 6000                            |
| Number of fingerprint systems                                 | 1                               |
| Number of face systems                                        | 0                               |
| Number of face images from which scores were obtained         | 0                               |
| Number of fingerprint images from which scores were obtained  | 4 (2 left, 2 right) per subject |
| Number of scores                                              | 2 * 6000 * 6000                 |
| Number of similarity files                                    | 12000                           |
| Suggested use in fusion studies                               | Two-finger fusion               |

**Set 3** contains scores from two face systems run on images from 3000 individuals. For each individual, the set contains one score from the comparison of face A with a later face, B, and a score from face A and another later face, C. This data is provided for each of two mid-2002 face recognition algorithms

| Property                                                      | Value                                         |
| ------------------------------------------------------------- | --------------------------------------------- |
| Number of subjects                                            | 3000                                          |
| Number of fingerprint systems                                 | 0                                             |
| Number of face systems                                        | 3                                             |
| Number of face images from which scores were obtained         | 2 per subject                                 |
| Number of fingerprint images from which scores were obtained  | 0                                             |
| Number of scores                                              | 2 * 3000 * 6000                               |
| Number of similarity files                                    | 12000                                         |
| Suggested use in fusion studies                               | Two-sample fusion and/or two-algorithm fusion |
