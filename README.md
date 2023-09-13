# COSP2
###	Folder structure:
   * **RQ1&RQ2-COSP2-prediction-results/** — COSP2 and three baselines prediction results for all smell types and prediction intervals.
        * **cosp2-slope2-results/** — COSP2 prediction results when slope is set to 2.
        * **cosp2-slope5-results/** — COSP2 prediction results when slope is set to 5.
        * **cosp2-slope10-results/** — COSP2 prediction results when slope is set to 10.
        * **cosp2-slope20-results/** — COSP2 prediction results when slope is set to 20.
   * **RQ1&RQ2-AUC/** — AUC for COSP2
        * **AUC-all-repo-results.csv** — AUC for all smell types, repositories, slopes and prediction intervals.
        * **AUC-avg-results.csv** — AUC averages between repositories.
   * **RQ1&RQ2-COSP2-prediction-plots/** — COSP2 plots for all smell types and prediction intervals.
        * **legend.pdf** — legend for colors of prediction intervals.
        * **predictions-slope2.pdf** — COSP prediction plots when slope is set to 2.
        * **predictions-slope5.pdf** — COSP prediction plots when slope is set to 5.
        * **predictions-slope10.pdf** — COSP prediction plots when slope is set to 10.
        * **predictions-slope20.pdf** — COSP prediction plots when slope is set to 20.
   * **RQ1&RQ2-qualitative-examples/** — system's snapshots at commits shown in qualitative examples.
        * **baomidou/mybatis-plus/** — sucess case.
        * **Bukkit/Bukkit/** — sucess case.
        * **confluentinc/ksq/** — failure case.        
   * **RQ1&RQ2-randomClassifier-prediction-results/** — random classifier prediction results for all smell types.
        * **rand-slope2/** — COSP2 prediction results when slope is set to 2.
        * **rand-slope5/** — COSP2 prediction results when slope is set to 5.
        * **rand-slope10/** — COSP2 prediction results when slope is set to 10.
        * **rand-slope20/** — COSP2 prediction results when slope is set to 20.
   * **RQ1&RQ2-releases/** — releases and distance between them in all repositories.
   * **RQ3-features/** — most important features selected by the GreedyStepwise algorithm for all smell types and prediction intervals
   * **smelly/clean-files-with-historical-slope-counts.csv** — smelly and clean file counts which have historical slopes.
