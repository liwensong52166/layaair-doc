#Stat 통계 패널 소개

###### *version :2.2.0beta4   Update:2019-9-2*

개발자 성능 최적화를 위해 레이아아이리 3D는 성능 통계 패널'Stat 통계 패널'을 제공해 개발자가 실시간 검색해 볼 수 있는 성능 인자를 제공한다.

​![图](img/1.png)(그림 1)

참여 통계 성능 인자가 다음과 같습니다 (모든 인자가 1초당 업데이트되어 있습니다) Fps 를 제외하면 저성능이 높을 것입니다.

​**FPS (WebGL) / FPS (3D):**Laya2D 모드 또는 Laya3D 모드에 나오는 프레임 주파수가 초당 표시된 프레임수가 높을수록 안정적이고 유창해지는 것;

​**Sprite:**전체 렌더링 노드 (용기 포함) 수를 통계하면, 크기가 엔진에 영향을 미치고, 노드, 데이터 조직과 과장의 효율을 나타낸다.

​**RenderBatches:**과장 비판

​**SavedRenderBatches:**합병된 과장 도매

​**CPUMemory:**CPU 메모리

​**GPUMemory:**GPU 저장

​**Shader:**Shader 내보내기 횟수

​**트리페이스:**삼각면

​**Frustumculling:**카메라의 시추 재단 횟수

​**OcreeNodeulling:**팔작나무 노드 재단 횟수

###어떻게 Stat 통계 패널 열기

1.**편집 모드---F9-미리 보기 설정--청취 프레임 통계 패널**	

2. 프로젝트 시작 후 바로 콘솔 입력**Laya.Stat.show ()**

##### 	