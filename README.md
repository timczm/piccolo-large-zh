---
tags:
- mteb
model-index:
- name: piccolo-large-zh
  results:
  - task:
      type: STS
    dataset:
      type: C-MTEB/AFQMC
      name: MTEB AFQMC
      config: default
      split: validation
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 51.40548754569409
    - type: cos_sim_spearman
      value: 54.168222315174376
    - type: euclidean_pearson
      value: 52.40464973459636
    - type: euclidean_spearman
      value: 54.26249134589867
    - type: manhattan_pearson
      value: 52.353782691201246
    - type: manhattan_spearman
      value: 54.20648078023014
  - task:
      type: STS
    dataset:
      type: C-MTEB/ATEC
      name: MTEB ATEC
      config: default
      split: test
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 53.4800486876876
    - type: cos_sim_spearman
      value: 54.27914644842898
    - type: euclidean_pearson
      value: 56.85762017857563
    - type: euclidean_spearman
      value: 54.3892743722252
    - type: manhattan_pearson
      value: 56.812630761505545
    - type: manhattan_spearman
      value: 54.359667416088556
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_reviews_multi
      name: MTEB AmazonReviewsClassification (zh)
      config: zh
      split: test
      revision: 1399c76144fd37290681b995c656ef9b2e06e26d
    metrics:
    - type: accuracy
      value: 40.33200000000001
    - type: f1
      value: 39.56855261607718
  - task:
      type: STS
    dataset:
      type: C-MTEB/BQ
      name: MTEB BQ
      config: default
      split: test
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 60.81359612041921
    - type: cos_sim_spearman
      value: 62.3148582435008
    - type: euclidean_pearson
      value: 61.21668579008443
    - type: euclidean_spearman
      value: 62.3526204140884
    - type: manhattan_pearson
      value: 61.1558631086567
    - type: manhattan_spearman
      value: 62.287696221478384
  - task:
      type: Clustering
    dataset:
      type: C-MTEB/CLSClusteringP2P
      name: MTEB CLSClusteringP2P
      config: default
      split: test
      revision: None
    metrics:
    - type: v_measure
      value: 38.98356815428385
  - task:
      type: Clustering
    dataset:
      type: C-MTEB/CLSClusteringS2S
      name: MTEB CLSClusteringS2S
      config: default
      split: test
      revision: None
    metrics:
    - type: v_measure
      value: 36.04329998232363
  - task:
      type: Reranking
    dataset:
      type: C-MTEB/CMedQAv1-reranking
      name: MTEB CMedQAv1
      config: default
      split: test
      revision: None
    metrics:
    - type: map
      value: 84.79178620472841
    - type: mrr
      value: 87.1725
  - task:
      type: Reranking
    dataset:
      type: C-MTEB/CMedQAv2-reranking
      name: MTEB CMedQAv2
      config: default
      split: test
      revision: None
    metrics:
    - type: map
      value: 84.89085057036931
    - type: mrr
      value: 87.46011904761905
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/CmedqaRetrieval
      name: MTEB CmedqaRetrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 23.351
    - type: map_at_10
      value: 35.284
    - type: map_at_100
      value: 37.222
    - type: map_at_1000
      value: 37.338
    - type: map_at_3
      value: 31.135
    - type: map_at_5
      value: 33.445
    - type: mrr_at_1
      value: 36.134
    - type: mrr_at_10
      value: 44.282
    - type: mrr_at_100
      value: 45.31
    - type: mrr_at_1000
      value: 45.356
    - type: mrr_at_3
      value: 41.615
    - type: mrr_at_5
      value: 43.169000000000004
    - type: ndcg_at_1
      value: 36.134
    - type: ndcg_at_10
      value: 41.982
    - type: ndcg_at_100
      value: 49.672
    - type: ndcg_at_1000
      value: 51.669
    - type: ndcg_at_3
      value: 36.521
    - type: ndcg_at_5
      value: 38.858
    - type: precision_at_1
      value: 36.134
    - type: precision_at_10
      value: 9.515
    - type: precision_at_100
      value: 1.5779999999999998
    - type: precision_at_1000
      value: 0.183
    - type: precision_at_3
      value: 20.747
    - type: precision_at_5
      value: 15.229000000000001
    - type: recall_at_1
      value: 23.351
    - type: recall_at_10
      value: 52.798
    - type: recall_at_100
      value: 84.806
    - type: recall_at_1000
      value: 98.172
    - type: recall_at_3
      value: 36.513
    - type: recall_at_5
      value: 43.701
  - task:
      type: PairClassification
    dataset:
      type: C-MTEB/CMNLI
      name: MTEB Cmnli
      config: default
      split: validation
      revision: None
    metrics:
    - type: cos_sim_accuracy
      value: 74.74443776307878
    - type: cos_sim_ap
      value: 83.8325812952643
    - type: cos_sim_f1
      value: 76.64593609264422
    - type: cos_sim_precision
      value: 70.78629431570607
    - type: cos_sim_recall
      value: 83.56324526537293
    - type: dot_accuracy
      value: 73.91461214672279
    - type: dot_ap
      value: 82.8769105611689
    - type: dot_f1
      value: 75.93478260869564
    - type: dot_precision
      value: 70.95267113548648
    - type: dot_recall
      value: 81.66939443535188
    - type: euclidean_accuracy
      value: 74.94888755261574
    - type: euclidean_ap
      value: 84.00606427216371
    - type: euclidean_f1
      value: 76.78665681410322
    - type: euclidean_precision
      value: 69.99615088529639
    - type: euclidean_recall
      value: 85.0362403553893
    - type: manhattan_accuracy
      value: 74.92483463619965
    - type: manhattan_ap
      value: 83.97546171072935
    - type: manhattan_f1
      value: 76.57105320779506
    - type: manhattan_precision
      value: 71.99917644636606
    - type: manhattan_recall
      value: 81.7629179331307
    - type: max_accuracy
      value: 74.94888755261574
    - type: max_ap
      value: 84.00606427216371
    - type: max_f1
      value: 76.78665681410322
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/CovidRetrieval
      name: MTEB CovidRetrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 73.34
    - type: map_at_10
      value: 81.462
    - type: map_at_100
      value: 81.661
    - type: map_at_1000
      value: 81.663
    - type: map_at_3
      value: 79.742
    - type: map_at_5
      value: 80.886
    - type: mrr_at_1
      value: 73.656
    - type: mrr_at_10
      value: 81.432
    - type: mrr_at_100
      value: 81.632
    - type: mrr_at_1000
      value: 81.634
    - type: mrr_at_3
      value: 79.786
    - type: mrr_at_5
      value: 80.87100000000001
    - type: ndcg_at_1
      value: 73.656
    - type: ndcg_at_10
      value: 85.036
    - type: ndcg_at_100
      value: 85.83
    - type: ndcg_at_1000
      value: 85.884
    - type: ndcg_at_3
      value: 81.669
    - type: ndcg_at_5
      value: 83.699
    - type: precision_at_1
      value: 73.656
    - type: precision_at_10
      value: 9.715
    - type: precision_at_100
      value: 1.005
    - type: precision_at_1000
      value: 0.101
    - type: precision_at_3
      value: 29.293999999999997
    - type: precision_at_5
      value: 18.587999999999997
    - type: recall_at_1
      value: 73.34
    - type: recall_at_10
      value: 96.101
    - type: recall_at_100
      value: 99.473
    - type: recall_at_1000
      value: 99.895
    - type: recall_at_3
      value: 87.197
    - type: recall_at_5
      value: 92.044
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/DuRetrieval
      name: MTEB DuRetrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 26.351999999999997
    - type: map_at_10
      value: 80.977
    - type: map_at_100
      value: 83.795
    - type: map_at_1000
      value: 83.836
    - type: map_at_3
      value: 56.388000000000005
    - type: map_at_5
      value: 71.089
    - type: mrr_at_1
      value: 90.75
    - type: mrr_at_10
      value: 93.648
    - type: mrr_at_100
      value: 93.71000000000001
    - type: mrr_at_1000
      value: 93.714
    - type: mrr_at_3
      value: 93.43299999999999
    - type: mrr_at_5
      value: 93.57600000000001
    - type: ndcg_at_1
      value: 90.75
    - type: ndcg_at_10
      value: 87.971
    - type: ndcg_at_100
      value: 90.594
    - type: ndcg_at_1000
      value: 90.998
    - type: ndcg_at_3
      value: 87.224
    - type: ndcg_at_5
      value: 86.032
    - type: precision_at_1
      value: 90.75
    - type: precision_at_10
      value: 41.975
    - type: precision_at_100
      value: 4.807
    - type: precision_at_1000
      value: 0.48900000000000005
    - type: precision_at_3
      value: 78.167
    - type: precision_at_5
      value: 65.85
    - type: recall_at_1
      value: 26.351999999999997
    - type: recall_at_10
      value: 88.714
    - type: recall_at_100
      value: 97.367
    - type: recall_at_1000
      value: 99.589
    - type: recall_at_3
      value: 58.483
    - type: recall_at_5
      value: 75.359
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/EcomRetrieval
      name: MTEB EcomRetrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 46.2
    - type: map_at_10
      value: 56.548
    - type: map_at_100
      value: 57.172
    - type: map_at_1000
      value: 57.192
    - type: map_at_3
      value: 53.983000000000004
    - type: map_at_5
      value: 55.408
    - type: mrr_at_1
      value: 46.2
    - type: mrr_at_10
      value: 56.548
    - type: mrr_at_100
      value: 57.172
    - type: mrr_at_1000
      value: 57.192
    - type: mrr_at_3
      value: 53.983000000000004
    - type: mrr_at_5
      value: 55.408
    - type: ndcg_at_1
      value: 46.2
    - type: ndcg_at_10
      value: 61.912
    - type: ndcg_at_100
      value: 64.834
    - type: ndcg_at_1000
      value: 65.36
    - type: ndcg_at_3
      value: 56.577
    - type: ndcg_at_5
      value: 59.15899999999999
    - type: precision_at_1
      value: 46.2
    - type: precision_at_10
      value: 7.89
    - type: precision_at_100
      value: 0.923
    - type: precision_at_1000
      value: 0.096
    - type: precision_at_3
      value: 21.367
    - type: precision_at_5
      value: 14.08
    - type: recall_at_1
      value: 46.2
    - type: recall_at_10
      value: 78.9
    - type: recall_at_100
      value: 92.30000000000001
    - type: recall_at_1000
      value: 96.39999999999999
    - type: recall_at_3
      value: 64.1
    - type: recall_at_5
      value: 70.39999999999999
  - task:
      type: Classification
    dataset:
      type: C-MTEB/IFlyTek-classification
      name: MTEB IFlyTek
      config: default
      split: validation
      revision: None
    metrics:
    - type: accuracy
      value: 44.24778761061947
    - type: f1
      value: 36.410133889743115
  - task:
      type: Classification
    dataset:
      type: C-MTEB/JDReview-classification
      name: MTEB JDReview
      config: default
      split: test
      revision: None
    metrics:
    - type: accuracy
      value: 86.09756097560975
    - type: ap
      value: 53.85203082125175
    - type: f1
      value: 80.61318243910114
  - task:
      type: STS
    dataset:
      type: C-MTEB/LCQMC
      name: MTEB LCQMC
      config: default
      split: test
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 70.49411615067606
    - type: cos_sim_spearman
      value: 75.80607876548899
    - type: euclidean_pearson
      value: 74.67002802430761
    - type: euclidean_spearman
      value: 76.00290181304833
    - type: manhattan_pearson
      value: 74.66745498313495
    - type: manhattan_spearman
      value: 76.00460005446307
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/MMarcoRetrieval
      name: MTEB MMarcoRetrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 64.388
    - type: map_at_10
      value: 73.94800000000001
    - type: map_at_100
      value: 74.279
    - type: map_at_1000
      value: 74.29
    - type: map_at_3
      value: 72.017
    - type: map_at_5
      value: 73.29599999999999
    - type: mrr_at_1
      value: 66.648
    - type: mrr_at_10
      value: 74.59599999999999
    - type: mrr_at_100
      value: 74.885
    - type: mrr_at_1000
      value: 74.896
    - type: mrr_at_3
      value: 72.88900000000001
    - type: mrr_at_5
      value: 74.017
    - type: ndcg_at_1
      value: 66.648
    - type: ndcg_at_10
      value: 77.833
    - type: ndcg_at_100
      value: 79.306
    - type: ndcg_at_1000
      value: 79.605
    - type: ndcg_at_3
      value: 74.18599999999999
    - type: ndcg_at_5
      value: 76.352
    - type: precision_at_1
      value: 66.648
    - type: precision_at_10
      value: 9.472999999999999
    - type: precision_at_100
      value: 1.0210000000000001
    - type: precision_at_1000
      value: 0.105
    - type: precision_at_3
      value: 28.055999999999997
    - type: precision_at_5
      value: 17.974
    - type: recall_at_1
      value: 64.388
    - type: recall_at_10
      value: 89.143
    - type: recall_at_100
      value: 95.794
    - type: recall_at_1000
      value: 98.152
    - type: recall_at_3
      value: 79.55499999999999
    - type: recall_at_5
      value: 84.694
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_massive_intent
      name: MTEB MassiveIntentClassification (zh-CN)
      config: zh-CN
      split: test
      revision: 31efe3c427b0bae9c22cbb560b8f15491cc6bed7
    metrics:
    - type: accuracy
      value: 67.99932750504371
    - type: f1
      value: 66.07217986916525
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_massive_scenario
      name: MTEB MassiveScenarioClassification (zh-CN)
      config: zh-CN
      split: test
      revision: 7d571f92784cd94a019292a1f45445077d0ef634
    metrics:
    - type: accuracy
      value: 72.08137188971082
    - type: f1
      value: 72.42255159515156
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/MedicalRetrieval
      name: MTEB MedicalRetrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 49.6
    - type: map_at_10
      value: 56.04
    - type: map_at_100
      value: 56.584999999999994
    - type: map_at_1000
      value: 56.637
    - type: map_at_3
      value: 54.7
    - type: map_at_5
      value: 55.505
    - type: mrr_at_1
      value: 49.7
    - type: mrr_at_10
      value: 56.094
    - type: mrr_at_100
      value: 56.638999999999996
    - type: mrr_at_1000
      value: 56.691
    - type: mrr_at_3
      value: 54.75
    - type: mrr_at_5
      value: 55.54
    - type: ndcg_at_1
      value: 49.6
    - type: ndcg_at_10
      value: 59.038000000000004
    - type: ndcg_at_100
      value: 61.964
    - type: ndcg_at_1000
      value: 63.482000000000006
    - type: ndcg_at_3
      value: 56.297
    - type: ndcg_at_5
      value: 57.743
    - type: precision_at_1
      value: 49.6
    - type: precision_at_10
      value: 6.84
    - type: precision_at_100
      value: 0.828
    - type: precision_at_1000
      value: 0.095
    - type: precision_at_3
      value: 20.3
    - type: precision_at_5
      value: 12.879999999999999
    - type: recall_at_1
      value: 49.6
    - type: recall_at_10
      value: 68.4
    - type: recall_at_100
      value: 82.8
    - type: recall_at_1000
      value: 95.1
    - type: recall_at_3
      value: 60.9
    - type: recall_at_5
      value: 64.4
  - task:
      type: Reranking
    dataset:
      type: C-MTEB/Mmarco-reranking
      name: MTEB MMarcoReranking
      config: default
      split: dev
      revision: None
    metrics:
    - type: map
      value: 27.274633976199482
    - type: mrr
      value: 25.85952380952381
  - task:
      type: Classification
    dataset:
      type: C-MTEB/MultilingualSentiment-classification
      name: MTEB MultilingualSentiment
      config: default
      split: validation
      revision: None
    metrics:
    - type: accuracy
      value: 70.15
    - type: f1
      value: 70.12595878910165
  - task:
      type: PairClassification
    dataset:
      type: C-MTEB/OCNLI
      name: MTEB Ocnli
      config: default
      split: validation
      revision: None
    metrics:
    - type: cos_sim_accuracy
      value: 68.05630752571737
    - type: cos_sim_ap
      value: 72.9224765568519
    - type: cos_sim_f1
      value: 72.97297297297295
    - type: cos_sim_precision
      value: 62.1380846325167
    - type: cos_sim_recall
      value: 88.3843717001056
    - type: dot_accuracy
      value: 68.11044937736871
    - type: dot_ap
      value: 72.84095585142163
    - type: dot_f1
      value: 72.59574468085107
    - type: dot_precision
      value: 60.79828937990022
    - type: dot_recall
      value: 90.07391763463569
    - type: euclidean_accuracy
      value: 67.73145641580942
    - type: euclidean_ap
      value: 72.8584903276338
    - type: euclidean_f1
      value: 72.82095319879778
    - type: euclidean_precision
      value: 61.3603473227207
    - type: euclidean_recall
      value: 89.54593453009504
    - type: manhattan_accuracy
      value: 67.56903086085543
    - type: manhattan_ap
      value: 72.81719990959621
    - type: manhattan_f1
      value: 72.95855560114896
    - type: manhattan_precision
      value: 59.664429530201346
    - type: manhattan_recall
      value: 93.8753959873284
    - type: max_accuracy
      value: 68.11044937736871
    - type: max_ap
      value: 72.9224765568519
    - type: max_f1
      value: 72.97297297297295
  - task:
      type: Classification
    dataset:
      type: C-MTEB/OnlineShopping-classification
      name: MTEB OnlineShopping
      config: default
      split: test
      revision: None
    metrics:
    - type: accuracy
      value: 90.27
    - type: ap
      value: 87.25468287842568
    - type: f1
      value: 90.24230569233008
  - task:
      type: STS
    dataset:
      type: C-MTEB/PAWSX
      name: MTEB PAWSX
      config: default
      split: test
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 34.445576951449894
    - type: cos_sim_spearman
      value: 38.3120125820568
    - type: euclidean_pearson
      value: 38.80156903904639
    - type: euclidean_spearman
      value: 38.240808371401656
    - type: manhattan_pearson
      value: 38.77317222891622
    - type: manhattan_spearman
      value: 38.230008722746646
  - task:
      type: STS
    dataset:
      type: C-MTEB/QBQTC
      name: MTEB QBQTC
      config: default
      split: test
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 37.990494014067295
    - type: cos_sim_spearman
      value: 38.218416274161385
    - type: euclidean_pearson
      value: 35.91543518481725
    - type: euclidean_spearman
      value: 37.34947320962178
    - type: manhattan_pearson
      value: 35.90653204921896
    - type: manhattan_spearman
      value: 37.3484819621432
  - task:
      type: STS
    dataset:
      type: mteb/sts22-crosslingual-sts
      name: MTEB STS22 (zh)
      config: zh
      split: test
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 66.10227125673059
    - type: cos_sim_spearman
      value: 66.65529695940144
    - type: euclidean_pearson
      value: 64.41045931064728
    - type: euclidean_spearman
      value: 66.48371335308076
    - type: manhattan_pearson
      value: 64.40881380301438
    - type: manhattan_spearman
      value: 66.4530857331391
  - task:
      type: STS
    dataset:
      type: C-MTEB/STSB
      name: MTEB STSB
      config: default
      split: test
      revision: None
    metrics:
    - type: cos_sim_pearson
      value: 74.46374847096926
    - type: cos_sim_spearman
      value: 74.42746155066217
    - type: euclidean_pearson
      value: 74.29184569507011
    - type: euclidean_spearman
      value: 74.88985827017852
    - type: manhattan_pearson
      value: 74.28083071864158
    - type: manhattan_spearman
      value: 74.8848458821044
  - task:
      type: Reranking
    dataset:
      type: C-MTEB/T2Reranking
      name: MTEB T2Reranking
      config: default
      split: dev
      revision: None
    metrics:
    - type: map
      value: 66.95528971496414
    - type: mrr
      value: 77.09135312892928
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/T2Retrieval
      name: MTEB T2Retrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 26.531
    - type: map_at_10
      value: 74.504
    - type: map_at_100
      value: 78.321
    - type: map_at_1000
      value: 78.393
    - type: map_at_3
      value: 52.288000000000004
    - type: map_at_5
      value: 64.228
    - type: mrr_at_1
      value: 88.331
    - type: mrr_at_10
      value: 91.044
    - type: mrr_at_100
      value: 91.156
    - type: mrr_at_1000
      value: 91.161
    - type: mrr_at_3
      value: 90.55499999999999
    - type: mrr_at_5
      value: 90.857
    - type: ndcg_at_1
      value: 88.331
    - type: ndcg_at_10
      value: 82.468
    - type: ndcg_at_100
      value: 86.494
    - type: ndcg_at_1000
      value: 87.211
    - type: ndcg_at_3
      value: 83.979
    - type: ndcg_at_5
      value: 82.40899999999999
    - type: precision_at_1
      value: 88.331
    - type: precision_at_10
      value: 41.223
    - type: precision_at_100
      value: 4.984
    - type: precision_at_1000
      value: 0.515
    - type: precision_at_3
      value: 73.603
    - type: precision_at_5
      value: 61.634
    - type: recall_at_1
      value: 26.531
    - type: recall_at_10
      value: 81.432
    - type: recall_at_100
      value: 94.404
    - type: recall_at_1000
      value: 98.085
    - type: recall_at_3
      value: 54.055
    - type: recall_at_5
      value: 67.726
  - task:
      type: Classification
    dataset:
      type: C-MTEB/TNews-classification
      name: MTEB TNews
      config: default
      split: validation
      revision: None
    metrics:
    - type: accuracy
      value: 46.543
    - type: f1
      value: 45.26659807296124
  - task:
      type: Clustering
    dataset:
      type: C-MTEB/ThuNewsClusteringP2P
      name: MTEB ThuNewsClusteringP2P
      config: default
      split: test
      revision: None
    metrics:
    - type: v_measure
      value: 60.575199180159586
  - task:
      type: Clustering
    dataset:
      type: C-MTEB/ThuNewsClusteringS2S
      name: MTEB ThuNewsClusteringS2S
      config: default
      split: test
      revision: None
    metrics:
    - type: v_measure
      value: 52.55759510188472
  - task:
      type: Retrieval
    dataset:
      type: C-MTEB/VideoRetrieval
      name: MTEB VideoRetrieval
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 56.2
    - type: map_at_10
      value: 66.497
    - type: map_at_100
      value: 66.994
    - type: map_at_1000
      value: 67.012
    - type: map_at_3
      value: 64.483
    - type: map_at_5
      value: 65.783
    - type: mrr_at_1
      value: 56.2
    - type: mrr_at_10
      value: 66.497
    - type: mrr_at_100
      value: 66.994
    - type: mrr_at_1000
      value: 67.012
    - type: mrr_at_3
      value: 64.483
    - type: mrr_at_5
      value: 65.783
    - type: ndcg_at_1
      value: 56.2
    - type: ndcg_at_10
      value: 71.18100000000001
    - type: ndcg_at_100
      value: 73.411
    - type: ndcg_at_1000
      value: 73.819
    - type: ndcg_at_3
      value: 67.137
    - type: ndcg_at_5
      value: 69.461
    - type: precision_at_1
      value: 56.2
    - type: precision_at_10
      value: 8.57
    - type: precision_at_100
      value: 0.9570000000000001
    - type: precision_at_1000
      value: 0.099
    - type: precision_at_3
      value: 24.933
    - type: precision_at_5
      value: 16.08
    - type: recall_at_1
      value: 56.2
    - type: recall_at_10
      value: 85.7
    - type: recall_at_100
      value: 95.7
    - type: recall_at_1000
      value: 98.8
    - type: recall_at_3
      value: 74.8
    - type: recall_at_5
      value: 80.4
  - task:
      type: Classification
    dataset:
      type: C-MTEB/waimai-classification
      name: MTEB Waimai
      config: default
      split: test
      revision: None
    metrics:
    - type: accuracy
      value: 85.54
    - type: ap
      value: 68.02479661585015
    - type: f1
      value: 83.87871999963863
---


## piccolo-large-zh

piccolo是一个通用embedding模型(中文), 由来自商汤科技的通用模型组完成训练。piccolo借鉴了E5以及GTE的训练流程，采用了两阶段的训练方式。
在第一阶段中，我们搜集和爬取了4亿的中文文本对(可视为弱监督文本对数据)，并采用二元组的softmax对比学习损失来优化模型。
在第二阶段中，我们搜集整理了2000万人工标注的中文文本对(精标数据)，并采用带有难负样本的三元组的softmax对比学习损失来帮助模型更好地优化。
目前，我们提供了piccolo-base-zh和piccolo-large-zh两个模型。

piccolo is a general text embedding model(chinese), powered by General Model Group from SenseTime Research. 
Inspired from E5 and GTE, piccolo is trained using a two stage pipeline. On the first stage, we collect and crawl 400 million weakly supervised Chinese text pairs from the Internet, 
and train the model with the pair(text and text pos) softmax contrastive loss. 
On the second stage, we collect 20 million human labeled chinese text pairs dataset, and finetune the model with tiplet (text, text_pos, text_neg) contrastive loss. 
Currently here we offer two different sizes of models, including piccolo-base-zh, piccolo-large-zh. 

## Metric
我们将piccolo与其他的开源embedding模型在CMTEB榜单上进行了比较，请参考CMTEB榜单。我们在[eval文件夹](https://huggingface.co/sensenova/piccolo-base-zh/tree/main/eval)中提供了复现结果的脚本。

We compared the performance of the piccolo with other embedding models on the C-MTEB benchmark. please refer to the C-MTEB leaderboard. 
we provide scripts in ["eval" folder](https://huggingface.co/sensenova/piccolo-base-zh/tree/main/eval) for results reproducing.


| Model Name | Model Size (GB) | Dimension | Sequence Length | Average (35) | Classification (9) | Clustering (4) | Pair Classification (2) | Reranking (4) | Retrieval (8) | STS (8) |
|:----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [**piccolo-large-zh**] | 0.65 | 1024 | 512 | **64.11** | 67.03 | 47.04 | 78.38 | 65.98 | 70.93 | 58.02 |
| [bge-large-zh]| 1.3 | 1024| 512 | 63.96 | 68.32 | 48.39 | 78.94 | 65.11 | 71.52 | 54.98 |
| [**piccolo-base-zh**]| 0.2 | 768 | 512 | **63.66** | 66.98 | 47.12 | 76.61 | 66.68 | 71.2 | 55.9 |
| [bge-large-zh-no-instruct]| 1.3 | 1024 | 512 | 63.4 | 68.58 | 50.01 | 76.77 | 64.9 | 70.54 | 53 |
| [bge-base-zh]| 0.41 | 768 | 512 | 62.8 | 67.07 | 47.64 | 77.5 | 64.91 | 69.53 | 54.12 |

## Usage
在sentence-transformer package中可以很容易地调用piccolo模型
```python
# for s2s dataset, you can use piccolo as below
# 对于短对短数据集，下面是通用的使用方式
from sentence_transformers import SentenceTransformer
sentences = ["数据1", "数据2"]
model = SentenceTransformer('sensenova/piccolo-base-zh')
embeddings_1 = model.encode(sentences, normalize_embeddings=True)
embeddings_2 = model.encode(sentences, normalize_embeddings=True)
similarity = embeddings_1 @ embeddings_2.T
print(similarity)
# for s2p dataset, we recommend to add instruction for passage retrieval
# 对于短对长数据集，我们推荐添加instruction，来帮助模型更好地进行检索。
from sentence_transformers import SentenceTransformer
queries = ['query_1', 'query_2']
passages = ["doc_1", "doc_2"]
model = SentenceTransformer('sensenova/piccolo-base-zh')
q_embeddings = model.encode(["查询：" + q for q in queries], normalize_embeddings=True)
p_embeddings = model.encode(["结果：" + p for p in passages], normalize_embeddings=True)
scores = q_embeddings @ p_embeddings.T
```

## Training Detail
### pretrain

pretrain 通常不需要太大的max length, 推荐128。小的max length用以提高batch size，加快训练速度，从而适应大规模数据。
pretrain 损失我们采用二元组contrastive loss，不加入hard negative, 直接采用inbatch negative，在实际训练中，我们使用了32张40G A100进行训练，单卡的batch size为1024。

Pretrain usually does not require a large max length, and 128 is recommended. A small max length is used to increase batch size and speed up training to adapt to large-scale data.
We use binary contrastive loss for pretrain loss, without adding hard negative, and directly use inbatch negative. In actual training, we used 32 40G A100 for training, and the batch size of a single card is 1024.

### finetune
finetune 通常会将 max length扩增到512。用以适应更大长度的文本输入，finetune时会多sample S2P的数据，以增强模型在retrieval任务上的性能。
finetune 损失采用三元组contrastive loss，加入hard negative，neg num通常设置为2-7，loss计算方式可以参考GTE里的improved contrastive loss。
注意: 我们给query和passage设置了不同的max length，query的max length始终保持在64。

For finetuning, we usually expands the max length to 512. To adapt to larger length text input, finetune will sample more S2P data to enhance the performance of the model on retrieval tasks.
The finetune loss uses triple contrastive loss, adding hard negative. Neg num is usually set to 2-7. The loss calculation method can refer to the improved contrastive loss in GTE.
Note: We set different max lengths for query and passage, and the max length of query is always kept at 64.

### Others
一些有用的trick:
1. 减小显存的方式: fp16 + gradient checkpointing + ZERO STAGE1 (stage2 不支持双塔结构下的gradient checkpointing) 相关issue见: https://github.com/microsoft/DeepSpeed/issues/988
2. dataset sampler，我们采用了M3E的dataset sampler，用以保证每个batch里的样本均来自于一个dataset，负样本更有价值。
3. instruction。instruction在我们的实验中对retrieval任务有非常大的性能提升，我们在每个训练样本前都加入'查询: '和'结果: '这样的instruction。

some useful tricks:
1. The way to reduce memory usage: fp16 + gradient checkpointing + ZERO STAGE1 (stage2 does not support gradient checkpointing under the double-tower structure) For related issues, see: https://github.com/microsoft/DeepSpeed/issues/ 988
2. Dataset sampler, we use M3E's dataset sampler to ensure that the samples in each batch come from a dataset, and negative samples are more valuable.
3. instruction. Instruction has greatly improved the performance of the retrieval task in our experiments. We added instructions like 'query: ' and 'result: ' before each training sample.

## Reference

这里我们列出了我们参考过的embedding项目和论文
1. [M3E](https://github.com/wangyuxinwhy/uniem)。非常棒的中文开源embedding项目，收集和整理了较多的中文高质量数据集，uniem也是一个不错的框架。
2. [Text2vec](https://github.com/shibing624/text2vec)。另一个一个非常棒的中文开源embedding项目。
3. [FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding)。智源AI开源的embedding模型，收集和整理了CMTEB benchmark，填补了中文embedding系统性评测的空缺。
4. [E5](https://github.com/microsoft/unilm/tree/master/e5)。来自微软的一篇文章，有非常详细的消融实验以及数据处理过滤细节。
5. [GTE](https://huggingface.co/thenlper/gte-base)。一篇来自阿里达摩的embedding论文。

Here we list the embedding projects and papers we have referenced
1. [M3E](https://github.com/wangyuxinwhy/uniem). A great Chinese open source embedding project that collects and organizes a large number of high-quality Chinese datasets. Uniem is also a good framework.
2. [Text2vec](https://github.com/shibing624/text2vec). Another great Chinese open source embedding project.
3. [Flag Embedding](https://github.com/FlagOpen/FlagEmbedding). Zhiyuan AI’s open source embedding model.They collect and organize CMTEB benchmark, filling the gap in systematic evaluation of Chinese embeddings.
4. [E5](https://github.com/microsoft/unilm/tree/master/e5). Powerd by microsoft，producing very detailed ablation experiments and data processing filtering details.
5. [GTE](https://huggingface.co/thenlper/gte-base). An embedding paper from Alibaba Damo.


## License
Piccolo 使用 MIT License，免费商用。
Piccolo use MIT License. It can be used for commercial purposes free of charge.

## Acknowledgement
piccolo 由来自商汤科技研究院的通用模型组完成训练，[Jinkin](https://huggingface.co/Jinkin) 完成了代码实现和模型训练， [Jinkin](https://huggingface.co/Jinkin), 
[CCCCxxx](https://huggingface.co/CCCCxxx) 一起完成了数据搜集、整理和评测工作. 项目由 [Gaomengya](https://huggingface.co/gaomengya) 和 [chaorenwu111](https://huggingface.co/chaorenwu111) 主导。

piccolo is powered by Genral Model group from SenseTime Research. 
[Jinkin](https://huggingface.co/Jinkin) complete code implementation and model training. 
[Jinkin](https://huggingface.co/Jinkin), [CCCCxxx](https://huggingface.co/CCCCxxx) completed the data collection、processing and model evaluation together. 
Project is led by [Gaomengya](https://huggingface.co/gaomengya) and [chaorenwu111](https://huggingface.co/chaorenwu111)