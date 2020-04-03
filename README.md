# .NET_core_study
study for ASP.NET core &amp; Entitiy framework core

# 실무에 적용

## 기존 ASP 프로젝트를 ASP.NET으로 변경할 때 고려할 점
- https://yaraba.tistory.com/494
  - 1. .asp를 .cshtml로 변경하는 방법, 그리고 백단을 C#으로 작성(가장 쉬운 방법)
  - 2. Web Forms으로 화면 개발하기 (웹폼이 익숙하긴 하지만 이미 CSS 잘 서서 만든 기존 화면을 다 뒤집을 가능성이 있다는 점에서 보류)
  - 3. ASP.NET MVC 도입(정확히 무슨 방법인지 모르겠음, 하지만 화면단(디자이너)과 콘트롤단, 모델단(DB)을 분리하는 가장 좋은 방법이긴 한 듯)
  - 4. 비주얼스튜디오에서 ASP.NET Web API 프로젝트를 실행해서 컨버트? 하는 방법(HTML을 직접 못 만지면 디자이너들과 협력이 안될 수 있기에..)
  
- ASP에서 ASP.NET로 마이그레이션(업체 통할시 견적볼 수 있는 곳 : http://www.ispirer.co.kr/purchase) : ezTips, Inc. 010 3293 2745
  - 액티브 서버 페이지 (*.asp)에서 ASP.NET 페이지(*.aspx)로 변환
  - VBScripts(*.vb)에서 C# (*.cs)
  - VBScripts(*.asp)에서 C# (*.aspx.cs) : 프로그래밍 로직 비하인드 페이지에서 .NET 프레임워크 페이지로 변환
  - Data Access로 변환: ADO.NET, LINQ
  
## 아예 다른 언어로 변환
- 프론트엔드를 javascript를 그대로 가져가고, 백엔드도 javascript(Node.js)로 전환하는 방법이 가장 쉬워보임
- 프론트엔드는 reactjs(결국 javscript 프레임워크니까..)로, 백단은 python으로.(둘다 제대로 해보지 않은 언어이기에 러닝커브가 고려됨)
- (그나마 내가 젤 잘할 수 있는)Java와 jsp를 도입하는 방법은, 대규모 서비스로 커질 것을 대비한다면 좋겠지만.. 비용이  
