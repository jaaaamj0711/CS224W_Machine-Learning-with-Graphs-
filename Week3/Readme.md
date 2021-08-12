발표 완료 1-37

Q. 소프트맥스로 표현 후 계산시간이 많이 걸리기 때문에 이를 Negative sampling 방법을 활용하여 계산  

Q. 내적 계산 부분에서 정규화가 진행이 된 상태인가?


Unnormalized Laplacian 의 properties 에서 2번의 의미가 무엇인가?

similarity 계산할 때, 임베딩 벡터를 normalization 해야할까?
similarity 계산할 때 벡터의 l2 norm으로 나눠주게되면 l2 norm을 계산하는 과정이 반복적으로 들어가고 복잡도가 높아지기때문에 모두 1로 노멀라이즈해서 사용하는 것 같아요

왜 소프트맥스를 사용하지?
random walk로 만난 노드의 확률은 높이고, 안 만난 노드의 확률은 낮추기 위해서 사용


random work에서 P(u|v)과 P(v|u)가 같은가? 
u→v로 갈때, z_v는 고정이고, z_u만 업데이트 하는 방식으로 이해하면 z_v^Tz_u = z_u^Tz_v일 필요 없을 것 같다.

그래프 임베딩을 해야할 때, virtual node를 어떻게 사용하는가?

- → standard한 노드 임베딩 기술을 이용해서, 전체 그래프의 노드를 임베딩
- → virtual node가 연결되어 있는 subgraph나 전체 그래프의 정보를 가진채 임베딩 됨
- → virtual node의 임베딩을 subgraph나 전체 그래프의 대표(?) 노드 임베딩으로 사용
