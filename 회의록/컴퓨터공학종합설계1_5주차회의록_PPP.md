## 주요내용

    저의 팀이 멘토랑 토론하고 개발언어와 환경, 점검 사항의 세부 정의, 실현 방법에 대해 팀원이랑 함께 회의를 시행 되었다. 
    개발언어와 환경은 Windows PC에서 Qt Creator개발환경 이용하고  C++로 개발언어 사용하였다.
    
    점검 사항의 세부 정의는요, 계정보안, 화면보안이랑 공유보안이 나타났다. 
    
    시스템 로그인 패스워드 복잡도 점검이고 화면 보호기 설정 여부 점검하고 시스템에서 사용하는 
    폴더를 제외하고 공유중인 폴더가 있는지 점검한다고 예정이다. 또는 안전 등급은 취약, 일반, 안전으로 나타났다. 
    
    모든 점검사항은 안전이 아닌 경우 조치방법 출력한다.
    
    실현방법은 시스템 내부에 접근하기 위해서 Windows시스템의 내부에 가지고 있는 많은 
    API중에 필요한 정보를 얻게 해 줄 수 있는 API를 찾아서 프로그램 만들기로 했다. 
