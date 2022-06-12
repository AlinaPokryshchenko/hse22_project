# hse22_project
#### Целью работы над проектом является поиск и изучение консервативных участков генома Z-ДНК в геномах прокариот и эукариот, где . В процессе выполнения проекта будут получены важные практические навыки биоинформатика -- работа в командной строке с утилитой bedtools, визуализация данных, конвертация координат участков между разными версиями генома (разными организмами) и т.п.
таксон: Alphaproteobacteria

род: Methylobacterium

Геномы: Methylobacterium durans, Methylobacterium indicum, Methylobacterium phyllosphaerae, Methylobacterium radiodurans, Methylobacterium terrae

[Ссылка на Colab](https://colab.research.google.com/drive/1_A0Oq3I4IT85y59-s7wpaluvN5LufUxA?usp=sharing)

[Бонус](https://colab.research.google.com/drive/1oR71QgG_l1GwB3Cpdc92eNSgIzSoAvY8?usp=sharing)
### Аннотированные гены и zDNA
Вид | Кол-во аннотированных генов | Доля аннотированных генов | Кол-во предсказанных zDNA | Общая длина предсказанных zDNA | Кол-во предсказанных zDNA с ZH-Score >= 500 | Общая длина предсказанных zDNA с ZH-Score >= 500
--- | --- | ----- | ----- | ------- | ------ | -------
Methylobacterium durans | 6572 | 82,58 | 6788375 | 65417268 | 117471 | 1176170
Methylobacterium indicum | 6640 | 85, 887 | 31542 | 300652 | 89253 | 887710
Methylobacterium phyllosphaera | 5839 | 85,62 | 36169 | 342760 | 94669 | 941564
Methylobacterium radiodurans | 5255 | 85,71 | 5539695 | 53677270 | 116393 | 1168542
Methylobacterium terrae | 5757 | 86,14 | 6162702 | 59857882 | 93034 | 928316
### Графики с распределением ZH-score
#### Methylobacterium durans
![Methylobacterium durans](/images/ZH-score/1.png)
#### Methylobacterium durans ZH-Score >= 500
![Methylobacterium durans](/images/ZH-score/2.png)
#### Methylobacterium indicum
![Methylobacterium indicum](/images/ZH-score/3.png)
#### Methylobacterium indicum ZH-Score >= 500
![Methylobacterium durans](/images/ZH-score/4.png)
#### Methylobacterium phyllosphaerae
![Methylobacterium phyllosphaerae](/images/ZH-score/5.png)
#### Methylobacterium phyllosphaerae ZH-Score >= 500
![Methylobacterium phyllosphaerae](/images/ZH-score/6.png)
#### Methylobacterium radiodurans
![Methylobacterium radiodurans](/images/ZH-score/7.png)
#### Methylobacterium radiodurans ZH-Score >= 500
![Methylobacterium radiodurans](/images/ZH-score/8.png)
#### Methylobacterium terrae
![Methylobacterium terrae](/images/ZH-score/9.png)
#### Methylobacterium terrae ZH-Score >= 500
![Methylobacterium terrae](/images/ZH-score/10.png)
### Расположение предсказанных Z-ДНК
#### Methylobacterium durans
![Methylobacterium durans](/images/place_z-DNA/1.png)
#### Methylobacterium indicum
![Methylobacterium indicum](/images/place_z-DNA/2.png)
#### Methylobacterium phyllosphaerae
![Methylobacterium phyllosphaerae](/images/place_z-DNA/3.png)
#### Methylobacterium radiodurans
![Methylobacterium radiodurans](/images/place_z-DNA/4.png)
#### Methylobacterium terrae
![Methylobacterium terrae](/images/place_z-DNA/5.png)
### Распределение предсказанных zDNA
![predicted zDNA gen](/images/predicted_zDNA_on_gene.png)
### Гомологичные кластеры
#### Количество геномов, входящих в кластеры
![clusters in genome](/images/clusters_in_genome.png)
#### Количество генов в кластерах
![genes in clusters](/images/genes_in_clusters.png)

Далее были выбраны 10 кластеров с самым большим средним ZH-Score
Кластер | Количество генов в кластере | Вид бактерии | Белок | Ген, кодирующий белок | Средний ZH-score | Функция белка в организме
--- | ------ | ------- | ------ | ----- | -------- | -----
1 | 5 | Methylobacterium durans | WP_109890964.1 | DK389_RS15785 | 1086.857933 | protein-glutamate O-methyltransferase CheR, part of the chemotaxis signaling mechanism
1 | 5 | Methylobacterium indicum | WP_207181734.1 | miv_RS05275 | 4093.2068 |  protein-glutamate O-methyltransferase CheR, part of the chemotaxis signaling mechanism
1 | 5 | Methylobacterium phyllosphaerae | MCBMB27_RS17240 | MCBMB27_RS17240 | 956.5028 | protein-glutamate O-methyltransferase CheR, part of the chemotaxis signaling mechanism
1 | 5 | Methylobacterium radiodurans | WP_109949666.1 | DK427_RS01190 | 839.9186 | protein-glutamate O-methyltransferase CheR, part of the chemotaxis signaling mechanism
1 | 5 | Methylobacterium terrae | WP_109960203.1 | DK419_RS17430 | 3211.76964 | protein-glutamate O-methyltransferase CheR, part of the chemotaxis signaling mechanism
2 | 5 | Methylobacterium durans | WP_236960547.1 | DK389_RS02535 | 8687.55 | pilus assembly protein
2 | 5 | Methylobacterium phyllosphaerae | WP_043353026.1 | MCBMB27_RS07950 | 1864.189333 |  pilus assembly protein
2 | 5 | Methylobacterium radiodurans | WP_245930788.1 | DK427_RS03940 | 471108.8882 | pilus assembly protein
2 | 5 | Methylobacterium terrae | WP_109962173.1 | DK419_RS07150 | 1755.117667 | pilus assembly protein
3 | 5 | Methylobacterium durans | WP_109896464.1 | DK389_RS16700 | 2511.514187 | N-acyltransferase activity, lipid A biosynthetic process
3 | 5 | Methylobacterium indicum | WP_207178558.1 | miv_RS20415 | 190270.53572 | N-acyltransferase activity, lipid A biosynthetic process
3 | 5 | Methylobacterium phyllosphaerae | WP_075380717.1 | MCBMB27_RS14100 | 4646.798625 | N-acyltransferase activity, lipid A biosynthetic process
3 | 5 | Methylobacterium radiodurans | WP_109954115.1 | DK427_RS11315 | 9874.917933 | N-acyltransferase activity, lipid A biosynthetic process
3 | 5 | Methylobacterium terrae | WP_109961063.1 | DK419_RS22515 | 120887.733675 | N-acyltransferase activity, lipid A biosynthetic process
4 | 5 | Methylobacterium durans | WP_236961082.1 | DK389_RS29685 | 12300.554743 | transporter substrate-binding domain-containing protein
4 | 5 | Methylobacterium indicum | WP_244278495.1 | miv_RS09790 | 1372.8328 | transporter substrate-binding domain-containing protein
4 | 5 | Methylobacterium phyllosphaerae | WP_051975947.1 | MCBMB27_RS05940 | 6794.88026 | transporter substrate-binding domain-containing protein
4 | 5 | Methylobacterium radiodurans | WP_109952080.1 | DK427_RS15685 | 159240.145567 | transporter substrate-binding domain-containing protein
4 | 5 | Methylobacterium terrae | WP_208642368.1 | DK419_RS19170 | 1026.5838 | transporter substrate-binding domain-containing protein
5 | 5 | Methylobacterium durans | WP_236960122.1 | DK389_RS34350 | 13594.646814 | LpxI, functionally equivalent to LpxH, replaces it in LPS biosynthesis in a minority of bacteria
5 | 5 | Methylobacterium indicum | WP_207178554.1 | miv_RS20400 | 1893.4602 | LpxI, functionally equivalent to LpxH, replaces it in LPS biosynthesis in a minority of bacteria
5 | 5 | Methylobacterium phyllosphaerae | WP_043382807.1 | MCBMB27_RS14085 | 768.160633 | LpxI, functionally equivalent to LpxH, replaces it in LPS biosynthesis in a minority of bacteria
5 | 5 | Methylobacterium radiodurans | WP_109951341.1 | DK427_RS11330 | 109048.676867 | LpxI, functionally equivalent to LpxH, replaces it in LPS biosynthesis in a minority of bacteria
5 | 5 | Methylobacterium terrae | WP_109961060.1 | DK419_RS22500 | 2672.12954 | LpxI, functionally equivalent to LpxH, replaces it in LPS biosynthesis in a minority of bacteria
6 | 5 | Methylobacterium durans | WP_109889663.1 | DK389_RS11380 | 1619.94415 | hypothetical protein
6 | 5 | Methylobacterium indicum | WP_207182058.1 | miv_RS07390 | 7285.298357 | hypothetical protein
6 | 5 | Methylobacterium phyllosphaerae | WP_075380963.1 | MCBMB27_RS17835 | 3542.7886 | hypothetical protein
6 | 5 | Methylobacterium radiodurans | WP_109950423.1 | DK427_RS05770 | 189714.06928 | hypothetical protein
6 | 5 | Methylobacterium terrae | WP_109960737.1 | DK419_RS20540 | 5965.195286 | hypothetical protein
7 | 5 | Methylobacterium durans | WP_109890605.1 | DK389_RS14585 | 4158.46707 | malonyl-CoA synthase
7 | 5 | Methylobacterium indicum | WP_207179700.1 | miv_RS25895 | 1122.293686 | malonyl-CoA synthase
7 | 5 | Methylobacterium phyllosphaerae | WP_043389413.1 | MCBMB27_RS05195 | 6786.37566 | malonyl-CoA synthase
7 | 5 | Methylobacterium radiodurans | WP_109951198.1 | DK427_RS10435 | 111411.332411 | malonyl-CoA synthase
7 | 5 | Methylobacterium terrae | WP_109958441.1 | DK419_RS07005 | 1290.98364 | malonyl-CoA synthase
8 | 5 | Methylobacterium durans | WP_109890889.1 | DK389_RS15560 | 2525.787100 | YidB family protein 
8 | 5 | Methylobacterium indicum | WP_207181965.1 | miv_RS06680 | 2204.6703 | YidB family protein
8 | 5 | Methylobacterium phyllosphaerae | WP_075380136.1 | MCBMB27_RS07180 | 1076.249225 | YidB family protein
8 | 5 | Methylobacterium radiodurans | WP_109951254.1 | DK427_RS10760 | 1728.99055 | YidB family protein
8 | 5 | Methylobacterium terrae | WP_109958966.1 | DK419_RS10095 | 8922.646 | YidB family protein
9 | 5 | Methylobacterium durans | WP_109891442.1 | DK389_RS17420 | 2001.588356 | TIM44-like domain-containing protein
9 | 5 | Methylobacterium indicum | WP_207180638.1 | miv_RS29925 | 975.54255 | TIM44-like domain-containing protein
9 | 5 | Methylobacterium phyllosphaerae | WP_043383225.1 | MCBMB27_RS00300 | 6050.374667 | TIM44-like domain-containing protein
9 | 5 | Methylobacterium radiodurans | WP_109951158.1 | DK427_RS10185 | 3844.00804 | TIM44-like domain-containing protein
9 | 5 | Methylobacterium terrae | WP_109961145.1 | DK419_RS22985 | 1648.804237 | TIM44-like domain-containing protein
10 | 5 | Methylobacterium durans | WP_109889055.1 | DK389_RS09320 | 2936.121243 | 2-isopropylmalate synthase activity, 2-isopropylmalate synthase
10 | 5 | Methylobacterium indicum | WP_058617355.1 | miv_RS03275 | 5513.130009 | 2-isopropylmalate synthase activity, 2-isopropylmalate synthase
10 | 5 | Methylobacterium phyllosphaerae | WP_043380649.1 | MCBMB27_RS10110 | 4592.047427 | 2-isopropylmalate synthase activity, 2-isopropylmalate synthase
10 | 5 | Methylobacterium radiodurans | WP_109950823.1 | DK427_RS08090 | 2246.670380 | 2-isopropylmalate synthase activity, 2-isopropylmalate synthase
10 | 5 | Methylobacterium terrae | WP_109957635.1 | DK419_RS02095 | 3488.106615 | 2-isopropylmalate synthase activity, 2-isopropylmalate synthase
### Распределение Z-ДНК относительно генов в кластерах
![clusters_range](/images/clusters_range/1.png)
![clusters_range](/images/clusters_range/2.png)
![clusters_range](/images/clusters_range/3.png)
![clusters_range](/images/clusters_range/4.png)
![clusters_range](/images/clusters_range/5.png)
![clusters_range](/images/clusters_range/6.png)
![clusters_range](/images/clusters_range/7.png)
![clusters_range](/images/clusters_range/8.png)
![clusters_range](/images/clusters_range/9.png)
![clusters_range](/images/clusters_range/10.png)
### Множественное белковое выравнивание
Данные файлы расположены в папке muscle

### Визуализация расположение Z-ДНК для кластеров
![zdna_on_genes](/images/zdna_on_genes/1.png)
![zdna_on_genes](/images/zdna_on_genes/2.png)
![zdna_on_genes](/images/zdna_on_genes/3.png)
![zdna_on_genes](/images/zdna_on_genes/4.png)
![zdna_on_genes](/images/zdna_on_genes/5.png)
![zdna_on_genes](/images/zdna_on_genes/6.png)
![zdna_on_genes](/images/zdna_on_genes/7.png)
![zdna_on_genes](/images/zdna_on_genes/8.png)
![zdna_on_genes](/images/zdna_on_genes/9.png)
![zdna_on_genes](/images/zdna_on_genes/10.png)
