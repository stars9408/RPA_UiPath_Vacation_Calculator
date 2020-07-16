# RPA_UiPath_Vacation_Calculator
UiPath RPA that crawls the vacation inquiries from company's groupware(web) and records it on excel files.

1. 공휴일은 '공휴일' 엑셀파일에 년도에 맞게 넣어주어야 한다.
2. Internet Explorer가 있어야 한다.
3. '휴가종합' 엑셀파일의 이름이 변경되는 경우, UiPath 프로그램 內 엑셀파일의 이름도 변경해주어야 한다.

*연결되어 있는 엑셀파일들의 경로 확인!!
*검색 범위에 포함되는 날짜(예: 오늘로부터 15일 전 날짜부터 휴가 처리)를 수정할 수 있다.
*그룹웨어는 허용된 IP와 ID로만 접근이 허용되는 경우도 있다. (IP는 어디서나 접근 가능) (ID는 허용된 ID를 이용해야만 접근 가능)
