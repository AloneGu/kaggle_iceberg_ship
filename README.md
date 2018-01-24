# kaggle_iceberg_ship 

useful links:     

* https://www.kaggle.com/c/statoil-iceberg-classifier-challenge/discussion/45265#266853

* https://www.kaggle.com/c/statoil-iceberg-classifier-challenge/discussion/47062

## notebooks

base models

## other_hand_features

generate images features and use lr,rf,gbrt,xgb,lgb generate base features

## ensemble

ensemble features and submit

## stacking

test stacking methods like voting, works for public LB

## my final result

* run ensemble/xgb_ensemble-all.ipynb

* copy results/all_xgb_sub_fold_5_rnd66.csv to stacking/all_xgb_sub_fold_5_rnd_66local1318.csv

* run stacking/best_median_v4.ipynb

* get results/stack_minmax_bestbase5.csv ( public score 0.1228, private score 0.1400 )

* final rank 295/3617, top 9%， my first kaggle medal !!! :stuck_out_tongue_winking_eye:

## leaderboard link

https://www.kaggle.com/c/statoil-iceberg-classifier-challenge/leaderboard
