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



** Corpora Stats **

Lines   |   Words   |   Characters
<br />249         4278          26665       test.ga.txt
<br />249         3394          19891       test.en.txt
<br />
<br />502         9406          63505       dev.ga
<br />502         7731          51525       dev.en
<br />
<br />24338       424127        2851986     gaHealth*.ga.txt
<br />24338       372976        2378565     gaHealth*.en.txt

***

![image](https://user-images.githubusercontent.com/29402225/149958050-1d2c1385-7e3a-49d7-bd3d-a936044df529.png)

Training **GA-EN** model with **combined 17k gaHealth corpus and 8k LoResMT2021 covid corpus** achieving a max validation accuracy of 38.7% and perplexity of 126 after 40k steps. BLEU score: 57.6.

***

![image](https://user-images.githubusercontent.com/29402225/149958414-a1fb2364-1d52-45c2-af04-35c93f9d9753.png)

Training **EN-GA** model with **combined 17k gaHealth corpus and 8k LoResMT2021 covid corpus** achieving a max validation accuracy of 38.3% and perplexity of 120 after 40k steps. BLEU score: 37.6.

***

![image](https://user-images.githubusercontent.com/29402225/149958511-1a64b72f-e865-4d3f-b0f9-92e4e5a58436.png)

Training **EN-GA** model with **8k LoResMT2021 covid corpus** achieving a max validation accuracy of 30.0% and perplexity of 354 after 30k steps. BLEU score: 36.0.

***

# References
Lankford, S., Afli, H. and Way, A., 2021, August. Machine Translation in the Covid domain: an English-Irish case study for LoResMT 2021. In Proceedings of the 4th Workshop on Technologies for MT of Low Resource Languages (LoResMT2021) (pp. 144-150).

Ojha, A.K., Liu, C.H., Kann, K., Ortega, J., Shatam, S. and Fransen, T., 2021. 
Findings of the LoResMT 2021 Shared Task on COVID and Sign Language for Low-resource Languages. arXiv preprint arXiv:2108.06598.
