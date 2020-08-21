# README<br>

Ruby-on-rails 프레임워크로 Youtube 를 클론 해 봤습니다.<br>

Frontside 는 Bootstrap / Fontawesome 으로 Style 하였습니다.<br><br>

# 주요기능<br><br>

# 회원가입 / 로그인 / 로그아웃<br>
-devise gem 으로 구현하였습니다.<br>
-devise-i18n gem으로 한글번역 하였습니다.<br>

# 동영상 / 썸네일 업로드 기능<br>
-carrierwave gem 으로 구현하였습니다.<br>
-동영상을 업로드 하려면 로그인 상태여야 하며, before_action으로 처리 했습니다.<br>
-해당 동영상을 업로드 한 사용자만 수정/삭제 가 가능합니다.<br>
-조회수, 업로드 시간이 함께 표시됩니다.<br><br>

# 페이지네이션<br>
-kaminari gem 으로 구현하였습니다.<br><br>

# 댓글<br>
-댓글 작성이 가능하며, jquery를 사용하여 비동기처리 하였습니다.<br>
-로그인을 한 상태에서만 댓글을 작성할 수 있습니다.<br>
-댓글의 작성자와 일치하면, 삭제할 수 있습니다. 역시 jquery를 사용하여 비동기처리 하였습니다.<br><br>

# 검색<br>
- 해당 키워드를 제목에 포함 한 영상이 검색됩니다.<br>
