# 26.46.0 마스터 시나리오 정본 대조표

정본 기준 커밋은 `c84baeba`입니다. 화면 목록 11개와 실제 화면 HTML 762개의 제목·분류·화면 설명을 수집하고, 주요 기능의 화면 본문과 설명 메모를 대조했습니다. 로딩·오류·입력 중·같은 기능의 크기별 변형을 별도 주요 기능으로 세지 않았습니다.

주요 기능을 39개 시나리오·175단계에 연결했습니다.

## 주요 기능 대응표

| 메뉴 | 주요 기능 | 시나리오 | 대조 후 처리 | 정본 화면 또는 정책 |
|---|---|---|---|---|
| 가입·로그인 | 업데이트·가입·초기 권한·로그인 유지 | 01·02 | 유지·보완 | first-join / first-configure / first-tutorial |
| 계정 | 비밀번호 찾기·변경·2단계 인증 | 35·26 | 추가 | first-find-password-code / setting-change-password / setting-2fa |
| 프로필 | 커버·보기 전환·공유 | 03 | 명시 | my-cover-edit / my-profile / web-share-preview |
| 프로필 | 기본 정보·직업·지역·연락처·링크·ID | 39 | 추가 | my-basic-info-sheet / my-basic-job / my-basic-email / my-basic-phone / my-basic-link |
| 프로필 | 항목별 공개 범위와 전체 프로필 비공개 | 39·03 | 추가 | my-visibility-sheet / setting-profile-visibility |
| 프로필 | 스타일 키워드·이미지·자기소개 | 31 | 추가 | first-expression / first-expression-images / first-expression-description |
| 프로필 | 학력·경력·수상 및 자격 관리 | 31 | 추가 | my-resume / my-resume-education / my-resume-register / my-resume-awards |
| 프로필 | 대표작·AI 추천사·Today 방문자 | 31 | 추가 | discovery-portfolio-owner-sheet / my-ai-recommend-retry / my-today-visitor |
| 업로드 | 영감·사진·동영상 포트폴리오·편집 | 04 | 보완 | upload-type / upload-3 / upload-image-edit / upload-video-cover |
| 업로드 | 오디오·PDF·유튜브·긴 글 | 37 | 선택형을 전체 주요 형식으로 보완 | upload-form / upload-file-picker / upload-pdf-viewer / upload-youtube-viewer |
| 업로드 | 해시태그·멘션 | 37 | 추가 | upload-hashtag-suggest / upload-mention-suggest |
| 콘텐츠 | 수정·삭제·외부 공유·공개 범위 | 04·13·22 | 보완 | upload-portfolio-edit / web-share-feed / discovery-other-feed-option |
| 발견 | 피드 넘겨보기·추천 크리에이터 | 05·36 | 보완 | discovery-home / discovery-recommended-creators |
| 발견 | 좋아요·리스펙트·댓글·저장·팔로우 | 05·34 | 유지·보완 | discovery-respect-phrase / discovery-comment-sheet / discovery-other-feed-option |
| 발견 | 위클리 베스트 작품·크리에이터·이벤트·규칙·명예의 전당 | 36 | 추가 | web-weekly-best / web-weekly-best-creator / web-weekly-best-event-no-lounge / web-weekly-best-rules / web-hall-of-fame |
| 발견 | OX·키워드 피드 모듈·혜택 | 36 | 조건부 추가 | web-discovery-quiz / web-discovery-tag-cloud / web-muse-privileges |
| 검색 시작 | Discovery·Club 돋보기·검색어 없는 둘러보기 | 27·28·29 | 추가 | finder-search-suggestion / finder-home / finder-home-portfolio / finder-home-project |
| 검색 시작 | 최근 검색어 재검색·개별 삭제·전체삭제 | 27 | 추가 | finder-search-suggestion |
| 검색 시작 | 인기 검색어·추천 카테고리 | 27 | 추가 | finder-search-suggestion |
| 크리에이터 검색 | 활동명·ID 입력·자동완성·프로필·작업물 진입 | 28 | 추가 | finder-suggest-profile / finder-results / finder-searched-creator |
| 크리에이터 검색 | 직업·지역·해시태그·유형·성별·나이 필터 | 28 | 추가 | finder-creator-filter / finder-filter-profession / finder-filter-region / finder-filter-tag |
| 크리에이터 검색 | 추천·최신·리스펙트 정렬 | 28 | 추가 | finder-creator-order |
| 작업물 검색 | 포트폴리오 일반 검색·검색어 없는 목록 | 29 | 추가 | finder-portfolio-results / finder-home-portfolio |
| 작업물 검색 | # 제안 선택·본문 태그·해시태그 결과 | 29 | 독립 흐름으로 보완 | finder-suggest-portfolio / discovery-feed-detail |
| 작업물 검색 | 최신·리스펙트·댓글 정렬 | 29 | 추가 | finder-portfolio-order |
| 통합 검색 | 전체 다섯 영역·탭 더보기·결과 없음 | 06 | 유지·명시 | finder-all-results / finder-empty-result |
| 통합 검색 | 최근 본 다섯 종류·다시 열기·삭제 | 06 | 유지 | finder-search-suggestion |
| 클럽 검색 | 프로젝트·오픈채팅·팀 결과·상태별 진입 | 06·07 | 유지·보완 | finder-project-results / finder-openchat-results / finder-team-results |
| 클럽 검색 | 전체·오픈채팅·팀 필터·탭별 정렬 | 07 | 보완 | finder-creator-filter / finder-openchat-order / finder-team-order / finder-project-order |
| 발견 | Shuffle!·다시 추천·키워드 묶음 | 30 | 추가 | club-home / finder-keyword-recommend / finder-keyword-bundle |
| 관계 | 일촌 신청·수락·팔로워·팔로잉·검색 | 32 | 추가 | my-relation-first-connection / chatty-contact / chatty-contact-search |
| 관계 | 목록에서 노크·대화·팀 연락·다이얼 | 32 | 추가 | chatty-new-chat / chatty-contact-team-sheet / chatty-network-browse |
| 대화 | 노크 수락·관심없음·수신 제한 | 08·32 | 보완 | chatty-knock-received / chatty-knock-decline / my-collab-status |
| 대화 | 메시지·답장·검색·반응·삭제 | 08 | 보완 | chatty-room / chatty-room-reply / chatty-room-deleted |
| 대화 | Club 탐색·오픈채팅 생성·미리보기·참여·목록 | 33·08 | 추가 | club-home / club-home-lounge / chatty-lounge-compose / chatty-all |
| 대화 | 사진·동영상·파일·저장·보관함·원문 이동 | 18 | 유지·보완 | chatty-room-attachment / chatty-media-viewer / chatty-file / club-main-project-files |
| 대화 | 노트 작성·수정·반응·삭제·공개 범위 | 16·13 | 유지 | chatty-board-write / chatty-board-detail / chatty-board-edit |
| 대화 | 메시지·노트 공지·교체·내리기·역할 차이 | 17 | 유지 | chatty-room-notice / chatty-room-notice-open / chatty-room-notice-project |
| 프로젝트 | 생성·수정·홈·모집 공고·앱/웹 공유 | 09 | 보완 | club-main-project-created / club-project-settings-admin / club-project-share-web |
| 프로젝트 | 지원·수락·거절·취소·재지원·모집 마감/재개 | 10 | 보완 | club-main-project-apply / club-main-project-members-admin / club-project-settings-admin-closed / 앱푸시 알림 정책 v26.46.0 |
| 게시판 | 관리·서식·미디어·수정·삭제·반응·공지·공유 | 11·12·13 | 유지 | club-main-project-board-manage / club-write / club-post-detail / club-post-edit |
| 일정 | 온라인·오프라인·장소·참여/취소·수정/삭제·공유·지난 일정·댓글 | 14·13 | 보완 | club-main-project-schedule-create / club-main-project-schedule-detail-past / club-main-project-schedule-more |
| 자료실 | 폴더·업로드·이동·다운로드·삭제·채팅 자료 연계 | 15·18 | 유지 | club-main-project-files / club-main-project-files-folder / club-main-project-files-move |
| 팀 | 생성·정보 수정·소개·멤버·공유 웹 | 19 | 보완 | club-team-form / club-team-edit / club-team-intro-write / club-team-share-web |
| 팀 | 지원·수락/거절·취소/재지원·초대 수락/거절 | 20 | 보완 | club-team-contact / club-team-members-manage / club-home-team-invite-accept / club-home-team-invite-reject |
| 팀 | 의뢰·기타 연락·관리자 대화·수신 제한 예외 | 21 | 유지 | club-team-contact-request / club-team-contact-etc / chatty-knock-received |
| 팀 | 팀 포트폴리오 등록·보기·수정·삭제·공유 | 22 | 유지 | club-team-portfolio-mine / club-team-portfolio-member / discovery-feed-detail-team |
| 알림 | 수신·분류·모두 읽기·원문 이동·권한 상실 | 23 | 보완 | notice-alarm-all / notice-alarm-readall-toast / notice-alarm-case-reaction |
| 알림 | 전체·분류·개별·휴대폰 권한·필수 알림 | 24 | 유지 | notice-alarm-setting / notice-alarm-setting-push-off / notice-alarm-setting-off |
| 설정 | 북마크 두 종류·리스펙트·좋아요·내 댓글·신고 | 34 | 추가 | setting-bookmark / setting-contents / setting-comments / discovery-report-reason-sheet |
| 설정 | 서비스 동의·문의·약관·개인정보 처리방침·버전 | 35 | 구체화 | setting-service-agreement / setting-support / setting-terms-document / setting-privacy-document |
| 권한/종료 | 나가기·내보내기·차단·해제·프로젝트 종료·팀 해체·탈퇴 | 25·26·35 | 유지 | club-project-settings-leave / club-team-settings-leave / setting-blocked / club-main-project-ended / setting-delete |
| 앱 밖 진입 | iOS 앱 아이콘 메뉴·위젯·제어 센터 | 38 | 조건부 추가 | outside-quick-actions / outside-widget-small / outside-widget-lock / outside-control |
| 피드 | 길게 눌러 미니게임 실행·플레이·피드 복귀 | 36 | 추가 | 사용자 확인 / 26.46.0 기능 정리 |

## 적용 조건과 포함 범위

| 대상 | 처리 | 근거와 실행 방법 |
|---|---|---|
| Muse 혜택 | 36 조건부 수행 | 권한 있는 계정이 필요합니다. 계정이 없으면 막힘으로 남깁니다. 일반 계정으로 작성 성공을 기대하지 않습니다. |
| OX·키워드 피드 모듈 | 36 조건부 수행 | 서버가 해당 모듈을 제공해야 합니다. 예시 화면이 있다는 이유로 항상 피드에 있어야 한다고 판정하지 않습니다. |
| 위젯·제어 센터 | 38 해당 OS 수행 | 정본은 iOS Widget·Control 진입을 정의합니다. Android는 적용 제외, iOS도 OS 지원 조건을 따릅니다. |
| 갤러리 | 실행 대상에서 제외 | 이번 마스터 시나리오에서 제외합니다. |
| 피드 길게 누르기 미니게임 | 36-7~36-9 수행 | 실행 대상에 포함합니다. 피드 카드 길게 누르기 → 플레이 → 닫고 피드 복귀를 확인합니다. |

## 정본에 남아 있지만 이번 버전에서 제외된 화면

팀 의뢰의 예산·마감일·참고자료 첨부와 지원용 포트폴리오 선택은 해당 화면의 설명 칸에 `스펙아웃(26.46.0 제외)`로 명시돼 있습니다. 화면 파일이 남아 있어도 이번 실행 목록에는 넣지 않았습니다. 최신 팀 연락하기의 의뢰할 일·내용, 지원하기·기타 연락은 20~21에서 확인합니다.

## 세부 QA에 남긴 것

네트워크 단절·지연, 경계값, 반복 입력, 동시 처리, 회전·글꼴 배율, 로딩·오류 변형 전수, 장기 보관 배치·위클리 베스트 집계 및 지급 전수는 제외했습니다. 진단·내부 의견 보내기와 운영 배포용 화면도 일반 사용자 마스터에 추가하지 않았습니다.

화면 목록에만 있고 실제 파일이 없는 `chatty-create-menu`, `chatty-applicants`, `chatty-lounge-banner`는 독립 기능의 근거로 사용하지 않았습니다. 현재 Club 만들기 메뉴와 프로젝트 멤버 관리 화면으로 기능을 확인합니다.

이 대조표는 정본의 주요 사용자 기능을 시나리오로 연결한 결과입니다. 실제 앱 실행 결과나 모든 구현의 통과를 의미하지 않습니다. 실행 범위는 미니게임을 포함하고 갤러리를 제외하는 실행 범위로 구성했습니다.
