# adaptive_label_smoothing
cis.upenn.edu/~jean/math-deep.pdf

0.1
array([0.69126611, 0.69304717, 0.67580126, 0.56742386, 0.51986757,
       0.48476232, 0.44430657, 0.39495975, 0.33978941, 0.28125768,
       0.23301622, 0.19440515, 0.16620948, 0.14696526, 0.13112095,
       0.13030624, 0.11982085, 0.11919239, 0.1142505 , 0.10644591,
       0.10753436, 0.10466588, 0.09835766, 0.09999655, 0.09409382,
       0.09060141, 0.09123127, 0.08898952, 0.08664194, 0.08619576,
       0.07889295, 0.07894266, 0.07473524, 0.0718576 , 0.06595814,
       0.06427909, 0.06316579, 0.06122019, 0.05606447, 0.04918126,
       0.04220132, 0.0422824 , 0.03781387, 0.03395287, 0.0327915 ,
       0.02756839, 0.02600395, 0.02020786, 0.02190889, 0.0221693 ,
       0.01955163, 0.02537099, 0.02394782, 0.02239385, 0.01997505,
       0.02103213, 0.01783096, 0.02164505, 0.01557222, 0.01322087,
       0.01355499, 0.01993454, 0.01729079, 0.01657208, 0.01436421,
       0.0154236 , 0.0159797 , 0.02356161, 0.01538927, 0.01820385,
       0.0178852 , 0.01433184, 0.01285607, 0.01521407, 0.01107247,
       0.01540525, 0.01682726, 0.01702139, 0.01814529, 0.01295203,
       0.01378724, 0.02108537, 0.02383892, 0.01899938, 0.01399676,
       0.02160618, 0.0141379 , 0.01391103, 0.01429846, 0.0228916 ,
       0.0195109 , 0.01852678, 0.01664341, 0.01710158, 0.01768478,
       0.01290218, 0.0125385 , 0.01367772, 0.010515  , 0.00923264])

array([50.58510638, 50.4787234 , 70.59840426, 72.19414894, 74.50797872,
       74.49468085, 74.20212766, 73.85638298, 72.96542553, 72.76595745,
       72.20744681, 71.83510638, 71.91489362, 70.67819149, 70.71808511,
       71.74202128, 71.19680851, 71.54255319, 71.17021277, 71.60904255,
       70.57180851, 70.97074468, 71.18351064, 71.31648936, 70.26595745,
       71.44946809, 70.95744681, 72.30053191, 70.7712766 , 71.59574468,
       70.95744681, 71.15691489, 70.18617021, 71.26329787, 71.1037234 ,
       71.21010638, 71.38297872, 71.0106383 , 70.8643617 , 71.56914894,
       70.90425532, 69.98670213, 69.53457447, 70.63829787, 68.92287234,
       68.92287234, 69.20212766, 69.34840426, 69.08244681, 70.03989362,
       70.09308511, 70.21276596, 69.57446809, 69.66755319, 69.2287234 ,
       69.86702128, 69.78723404, 70.27925532, 70.        , 70.25265957,
       69.81382979, 69.54787234, 69.68085106, 69.98670213, 70.11968085,
       69.58776596, 71.0106383 , 70.27925532, 69.84042553, 69.36170213,
       70.4787234 , 69.86702128, 70.43882979, 69.98670213, 70.1462766 ,
       69.53457447, 69.44148936, 70.43882979, 69.50797872, 69.41489362,
       70.06648936, 69.68085106, 69.98670213, 70.09308511, 69.88031915,
       70.69148936, 69.58776596, 70.42553191, 70.19946809, 69.78723404,
       70.61170213, 69.98670213, 69.92021277, 70.79787234, 70.21276596,
       70.37234043, 70.45212766, 69.90691489, 71.1037234 , 71.03723404])

0.2
      
array([0.69213121, 0.68679507, 0.67525471, 0.65941983, 0.62599081,
       0.57868621, 0.53061202, 0.52341513, 0.47517695, 0.45339236,
       0.4153981 , 0.3990921 , 0.3871044 , 0.43777273, 0.40562678,
       0.38509458, 0.39239014, 0.3799333 , 0.36110281, 0.34116009,
       0.3200317 , 0.29352055, 0.25689789, 0.21968116, 0.17862699,
       0.16194036, 0.1413699 , 0.12743098, 0.11064369, 0.10300556,
       0.09344692, 0.08439278, 0.07847545, 0.08237569, 0.07222806,
       0.07108952, 0.06610493, 0.06375193, 0.06184708, 0.06255616,
       0.05118245, 0.05124047, 0.05224903, 0.05465859, 0.05319914,
       0.05134465, 0.04281938, 0.04600221, 0.04602659, 0.04193062,
       0.04259326, 0.03901491, 0.03947871, 0.03963162, 0.03740245,
       0.04035976, 0.03993776, 0.03280448, 0.03271899, 0.04047435,
       0.03195732, 0.03082758, 0.03523199, 0.02980761, 0.03102136,
       0.03105497, 0.02977537, 0.03119244, 0.02865588, 0.02727481,
       0.02841839, 0.03432059, 0.0280243 , 0.0244103 , 0.0251958 ,
       0.02384932, 0.0239934 , 0.02316706, 0.02315684, 0.02445538,
       0.02141767, 0.02475548, 0.02099027, 0.02503582, 0.02334534,
       0.02218539, 0.02209065, 0.02262008, 0.02849929, 0.02321562,
       0.02092969, 0.02039865, 0.02429537, 0.01915476, 0.02289317,
       0.01900982, 0.02278416, 0.0207788 , 0.01824395, 0.020393  ])
       
       
 array([51.55585106, 52.92553191, 50.63829787, 58.11170213, 59.01595745,
       60.83776596, 50.15957447, 51.36968085, 51.06382979, 51.64893617,
       59.20212766, 58.57712766, 59.72074468, 49.94680851, 54.65425532,
       55.43882979, 56.74202128, 59.24202128, 59.7606383 , 60.66489362,
       59.96010638, 61.30319149, 59.65425532, 59.46808511, 58.05851064,
       58.21808511, 58.2712766 , 59.86702128, 59.05585106, 60.3856383 ,
       57.34042553, 59.32180851, 57.55319149, 58.6037234 , 58.88297872,
       58.72340426, 58.81648936, 58.57712766, 57.9787234 , 58.56382979,
       58.71010638, 58.56382979, 57.91223404, 58.75      , 57.85904255,
       59.04255319, 58.41755319, 58.48404255, 59.28191489, 58.24468085,
       58.63031915, 58.56382979, 59.32180851, 57.75265957, 58.39095745,
       58.03191489, 58.37765957, 58.44414894, 58.33776596, 58.01861702,
       58.53723404, 57.77925532, 57.75265957, 57.87234043, 58.45744681,
       59.16223404, 58.04521277, 58.33776596, 58.81648936, 58.8962766 ,
       58.37765957, 58.125     , 59.00265957, 60.18617021, 57.84574468,
       59.05585106, 57.87234043, 58.73670213, 59.28191489, 57.77925532,
       58.64361702, 58.57712766, 59.30851064, 58.35106383, 58.3643617 ,
       58.49734043, 58.8962766 , 59.38829787, 59.34840426, 59.33510638,
       59.72074468, 58.81648936, 59.65425532, 58.77659574, 58.32446809,
       58.72340426, 58.52393617, 58.61702128, 58.67021277, 58.72340426])

0.3

array([0.69256007, 0.68901171, 0.67693533, 0.64964059, 0.60751164,
       0.55880466, 0.51077519, 0.46570157, 0.43345734, 0.4114814 ,
       0.40340552, 0.39450504, 0.39226265, 0.38467524, 0.38250396,
       0.37668197, 0.37180625, 0.36535843, 0.3644528 , 0.36036635,
       0.35490623, 0.35112084, 0.35866722, 0.36010207, 0.3549403 ,
       0.34069374, 0.32823099, 0.33632933, 0.34086609, 0.32784242,
       0.3311535 , 0.32775949, 0.31389711, 0.31190138, 0.31936333,
       0.2890827 , 0.29442801, 0.29527205, 0.2805434 , 0.26699477,
       0.25664203, 0.24279039, 0.22900117, 0.21477953, 0.20475329,
       0.19536061, 0.18332595, 0.16222775, 0.15468547, 0.1379982 ,
       0.12720914, 0.1288927 , 0.1121324 , 0.10987967, 0.0924255 ,
       0.08655145, 0.08754512, 0.07258681, 0.06882173, 0.0672323 ,
       0.06618007, 0.05932814, 0.06508315, 0.06330505, 0.0569928 ,
       0.05201361, 0.05286508, 0.05869139, 0.05507588, 0.04623985,
       0.04166509, 0.05564821, 0.04473181, 0.04042862, 0.04598348,
       0.04311296, 0.04320836, 0.04177447, 0.03537752, 0.04221929,
       0.04257411, 0.0387891 , 0.04082744, 0.03296551, 0.03578678,
       0.02976035, 0.03705879, 0.0439471 , 0.04329184, 0.04054291,
       0.03048862, 0.02895978, 0.0338699 , 0.03358525, 0.04233096,
       0.03479735, 0.03081982, 0.02972912, 0.03215723, 0.03836245])

array([50.61170213, 50.53191489, 50.87765957, 51.51595745, 50.02659574,
       51.64893617, 50.8643617 , 51.02393617, 50.42553191, 51.64893617,
       51.4893617 , 50.81117021, 50.99734043, 50.27925532, 50.02659574,
       50.87765957, 52.14095745, 51.60904255, 51.75531915, 51.59574468,
       51.91489362, 52.38031915, 52.24734043, 53.47074468, 55.87765957,
       54.58776596, 54.93351064, 51.64893617, 51.25      , 51.36968085,
       52.47340426, 53.64361702, 50.61170213, 52.31382979, 50.85106383,
       50.79787234, 50.09308511, 51.11702128, 51.40957447, 50.625     ,
       51.82180851, 51.14361702, 50.95744681, 52.00797872, 51.64893617,
       50.625     , 50.74468085, 51.21010638, 50.97074468, 51.52925532,
       51.15691489, 50.79787234, 50.73138298, 50.83776596, 51.64893617,
       51.17021277, 51.875     , 51.52925532, 51.18351064, 51.05053191,
       50.71808511, 51.17021277, 51.09042553, 51.7287234 , 50.8643617 ,
       50.89095745, 51.25      , 51.35638298, 51.19680851, 51.91489362,
       51.40957447, 52.18085106, 51.75531915, 51.19680851, 52.12765957,
       51.11702128, 51.50265957, 50.87765957, 51.60904255, 51.88829787,
       51.11702128, 51.56914894, 51.36968085, 52.06117021, 51.94148936,
       51.36968085, 51.23670213, 51.07712766, 50.89095745, 51.50265957,
       52.10106383, 52.2606383 , 52.2606383 , 51.82180851, 51.62234043,
       51.875     , 52.23404255, 52.00797872, 52.20744681, 51.11702128])

noise_rate gambler_es vl_es gb_epoch vl_epoch

0.1 74.00265957446808 70.98404255319149 (10,) (46,) \t
0.2 49.255319148936174 59.62765957446808 (200,) (8,) \t 
0.3 51.223404255319146 51.130319148936174 (6,) (8,) \t
0.4 51.1436170212766 49.22872340425532 (11,) (6,) \t

0.02 79.81382978723404 79.74734042553192 (14,) (25,)
0.04 78.61702127659575 77.12765957446808 (13,) (25,)
0.06 77.56648936170212 74.38829787234043 (13,) (20,)
0.08 75.05319148936171 72.92553191489361 (25,) (32,)


baseline

0.25 63.66%
0.15 71.51%

0.1 70.58510638297872%
0.2 59.202127659574465%
0.3 52.566489361702125%
0.4 50.09308510638298%
