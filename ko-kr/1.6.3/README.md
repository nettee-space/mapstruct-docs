# MapStruct 1.6.3 레퍼런스 가이드

원저자: Gunnar Morling, Andreas Gudian, Sjaak Derksen, Filip Hrisafov and the MapStruct community
─ 2024-11-09  
번역: [SilberBullet (No Silver Bullet)](https://github.com/silberbullet),
  [Merge Simpson](https://github.com/merge-simpson)
  ─ 번역 중

<details open>
  <summary>일람표</summary>

[머리말](#머리말)  
[1\. 소개](#소개)

</details>

# 머리말

이 문서는 형식에 안전하고 성능이 우수하며 종속성이 없는 빈 매핑 코드를 생성하기 위한 주석 처리기인 MapStruct의 참조 문서입니다.
이 가이드는 MapStruct에서 제공하는 모든 기능을 다룹니다. 이 가이드에서 모든 질문에 대한 답을 찾을 수 없는 경우
MapStruct [GitHub 토론](https://github.com/mapstruct/mapstruct/discussions)에 참여하여 도움을 받으세요.

이 가이드에서 오타나 기타 오류를 발견하셨나요? [MapStruct GitHub 리포지토리](https://github.com/mapstruct/mapstruct)에서
이슈를 개설하여 알려주시거나, 더 좋은 방법은 커뮤니티에 도움을 주시고 풀 리퀘스트를 보내서 수정해 주세요!

이 저작물은 [크리에이티브 커먼즈 저작자표시-동일조건변경허락 4.0 국제 라이선스
](http://creativecommons.org/licenses/by-sa/4.0/)에 따라 라이선스가 부여됩니다.  
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
