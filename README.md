# gaHealth
gaHealth: An English–Irish Bilingual Corpus of Health Data

To assess the merits of using in-domain data, a dataset for the specific domain of health was developed for the low-resource English to Irish language pair. Our study outlines the process used in developing the corpus and empirically demonstrates the benefits of using an in-domain dataset for the health domain. In the context of translating health-related data, models developed using the gaHealth corpus demonstrated a maximum BLEU score improvement of 22.2 points (40%) when compared with top performing models from the LoResMT2021 Shared Task.

The following training files may be used for developing in-domain health models:

-- gaHealth.en.txt
<br />-- gaHealth.ga.txt

The following files have augmented the gaHealth corpus with 8k lines of additional data from LoResMT2021:

-- gaHealth*.en.txt
<br />-- gaHealth*.ga.txt

In order to test the accuracy of in-domain health models developed using gaHealth, the validation and test sets from LoResMT2021 were used:

-- dev.en
<br />-- dev.ga

-- test.en.txt
<br />-- test.ga.txt

![image](https://user-images.githubusercontent.com/29402225/149958050-1d2c1385-7e3a-49d7-bd3d-a936044df529.png)

# References
Lankford, S., Afli, H. and Way, A., 2021, August. Machine Translation in the Covid domain: an English-Irish case study for LoResMT 2021. In Proceedings of the 4th Workshop on Technologies for MT of Low Resource Languages (LoResMT2021) (pp. 144-150).

Ojha, A.K., Liu, C.H., Kann, K., Ortega, J., Shatam, S. and Fransen, T., 2021. 
Findings of the LoResMT 2021 Shared Task on COVID and Sign Language for Low-resource Languages. arXiv preprint arXiv:2108.06598.
