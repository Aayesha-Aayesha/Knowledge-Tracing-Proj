# Knowledge-Tracing-Proj
This project aims to trace knowledge level of students during the exam setting and predict whether students will be able to correctly attempt future questions.
In this idea, students understanding about learning concepts is captured considering the contexts of questions.

This work performed in following steps:
1) Feature Engineering performed on pre-processed data to infer new features from the existing ones.
2) Two SOTA algorithms; LightGBM and Multi-head Self Attention Knowledge Tracing (MSAKT) were employed for the prediction task.
3) MSAKT outperformed due to Attention Mechanism that measured contextual similarity among questions for predictions.

This work resulted in two papers:
    Aayesha, A., Nouri, J., Afzaal, M., Wu, Y., Li, X. and Weegar, R., 2021, June. An ensemble approach for question-level knowledge tracing. In International Conference on Artificial Intelligence in Education (pp. 433-437). Cham: 
    Springer International Publishing.
    Aayesha , A., Nouri, J., Afzaal, M., Wu, Y., Li, X. and Weegar, R., 2021, July. A step towards improving knowledge tracing. In 2021 International Conference on Advanced Learning Technologies (ICALT) (pp. 38-39). IEEE.
