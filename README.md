# s4_project_text_classification

프로젝트 설명 : https://www.notion.so/TEXT_CLASSIFICATION-a22a669bc0d04fee937729f12b2bdabb

Parameter
  - model_fn : 모델 저장 경로
  - train_fn : 데이터 경로
  - gpu_id : gpu 사용 여부. gpu 사용 가능하면 0
  - batch_size : 256
  - n_epochs : 10
  - dropout : 0.3
  - max_length : 문장 최대 길이. 256
  - hidden_size : rnn model hidden size. 512
  - n_layers : rnn 층 개수. 4
  - use_batch_norm : batch normalization 사용 여부
  - window_sizes : cnn window size. list형태. [3,4,5]

