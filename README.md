# Counseling Chatbot with Wellness Dataset

## Award
[1st prize in AI for Future Society 2022](https://github.com/payitfoward/counseling_chatbot/blob/main/%EC%83%81%EC%9E%A5.jpg)

## How to Use

### Chatbot Model

1. Run preprocess.py

2. Run build_graph.py

3. Run train_bert.py

4. Run roberta_wellness_chatbot.py

### APP (will be rewritten by gaeun)

1. Build ./counselingApp (have to check your server ip)

## Requirements

- `dgl-cu113 == 0.9.1.post1`
- `ignite == 1.1.0`
- `python == 3.6.9`
- `torch == 1.10.0+cu113`
- `scikit-lear n== 0.24.2`
- `transformers == 4.18.0`
- `numpy =< 1.19.5`
- `networkx == 2.5.1`

## Future work

- make graph for hierarchical class
- Auto build graph for unseem data ( Now, Just Replace Embedding of last node. So, prediction task is abnormal )

## Reference

### Dataset

- [웰니스 대화 스크립트 데이터셋](https://aihub.or.kr/aihubdata/data/view.do?currMenu=120&topMenu=100&aihubDataSe=extrldata&dataSetSn=267)

### Citation

- [BertGCN: Transductive Text Classification by Combining GCN and BERT](https://arxiv.org/abs/2105.05727)
