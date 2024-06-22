VertexAI 는 Kubeflow에서 MLOps를 경험했다면 익숙한 도구이다. 
까다로운 설치형 Kubeflow를 벗어나 쉽게 파이프라인을 구동해 MLOps를 구현할수 있으며
airflow 만큼은 아니지만 UI적으로도 편리한 기능을 추가하고 있다.

만약 구글클라우드 사용하여 파이프라인 구현할 경우 가장 비용 효율적인 파이프라인 도구는 단연코 VertexAI pipeline이다. 

airflow처럼 다양한 DAG을 관리해야하는 경우가 아니라면 VertexAI pipeline사용한것을 추천한다. 

관련 예시를 보면 다양한 재사용가능한 컴퍼넌트를 따로 컨테이너로 구성해서 사용하는 예시가 많으나 
편의상 하나의 노트북 파일에서 모든 컴포넌트를 관리하는 구성으로 구현하는게 사실 편하다.

상세한 내용은 아래 URL 참고 가능하다 . 
https://github.com/GoogleCloudPlatform/vertex-ai-samples/blob/main/notebooks/official/pipelines/README.md

