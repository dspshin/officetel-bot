# officetel-bot
오피스텔 봇 : 오피스텔 및 연립다세대 매매 정보 알림 서비스.

<pre>
명령어 사용법:
/howmuch 지역코드 년월 필터 : 해당 지역의 월 거래를 확인하며, 필터를 포함하는 정보를 조회합니다.
 (년월이 생략되면 현재 월로 설정되며, 필터가 생략되면 전체 구/군의 정보가 나옵니다.)
 ex. /howmuch 11710 201603
 ex. /howmuch 11710
 ex. /howmuch 11710 201603 잠실
/loc 지역명 : 지역코드 검색.
 ex. /loc 송파
/noti add 지역코드 필터 : 노티 등록. howmuch의 사용법과 유사하며, 해당 결과가 있을 경우 매일 아침에 전송함(필터생략가능. 첫 노티는 전월 데이터도 전송됩니다).
 ex. /noti add 11710 잠실
/noti list : 노티 리스트 조회.
/noti remove 아이디 : 노티 제거.
</pre>
