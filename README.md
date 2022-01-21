# superai-handwritten-digit-hackathon-solution

## Introduction
[The Super AI Engineer 2021: Handwritten Digit competition](https://www.kaggle.com/c/super-ai-engineer-2021-handwritten-digit/overview) requires particpant to predict 1-5 digits from the images pool captured by participants themselves. We applied various technique and ultimately select [TrOCR](https://arxiv.org/abs/2109.10282) to be used in this notebook. 

Unfortunately, the competition dataset is not available publicly. **To fully use the notebook, you have to be competition's participant and change Google Drive path in the notebook to your own images storage path.**

## Outcome
- **Ranked #3 amongs 50 teams** participating the [Kaggle hackathon](https://www.kaggle.com/c/super-ai-engineer-2021-handwritten-digit/leaderboard) in the score leaderboard.
- Scored (Edit distance) 0.31059 and 0.30506 in private and public leaderboard

![image](https://user-images.githubusercontent.com/12471844/150430067-9803afec-c5d0-4ce8-b9f0-0bb4197dd049.png)
____
![image](https://user-images.githubusercontent.com/12471844/150430142-d2e2ea93-b89b-452e-9f9f-782afa6eec4c.png)
____
![image](https://user-images.githubusercontent.com/12471844/150430173-38fd246e-34a7-43d2-9b7a-dc9e04ab66d3.png)

## Labels
Because the competition has submission limit, we manually labelled the 870 samples competition datasets for testing purpose only. The labels are provided in this repository as `labels.csv`


## Contributors
- Norapat Buppodom: Modeling and Programming [![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/norapat-buppodom/) [![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/new5558)
- Teeraphong Kanchanakantikul: Modeling and Visualization [🏆 Kaggle](https://github.com/new5558)

https://www.kaggle.com/kengmut

## Credits
- [Super AI Engineer program](https://superai.aiat.or.th/) for creating this program/competition and kindly support the development of AI Engineers in Thailand.
- Khun Thitorn: [ORAND Dataset](https://www.orand.cl/icfhr2014-hdsr/) and TrOCR inspiration [![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/thititorn-seneewong-na-ayutthaya-74b0b4227/)
- [Huggingface tutorial](https://huggingface.co/docs/transformers/model_doc/trocr) and [TrOCR Original paper](https://arxiv.org/abs/2109.10282)
- [ARDIS: A Swedish Handwritten Digit Dataset](https://ardisdataset.github.io/ARDIS/)

