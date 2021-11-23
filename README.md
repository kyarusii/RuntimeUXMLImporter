# RuntimeUXMLImporter

![image](https://user-images.githubusercontent.com/79823287/142963695-a89eae53-f3d3-4597-aa38-bfb73839adc3.png)  

UXML과 USS는 TextAsset 기반으로 임포트되며, 유니티 에디터에서 ScriptedImporter를 통해서 각각 VisualTreeAsset과 StyleSheet 타입 ScriptableObject로서 작동합니다. 
이 ScriptedImporter는 런타임에서 동작하지 않으며, 현재로서는 지원 계획도 없다고 합니다.

> 런타임용으로 사용가능한 부분만 임의로 임포트해서 적용가능하도록 간단한 것 부터 작업 시작
