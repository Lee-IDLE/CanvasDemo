Canvas 공부를 위한 데모 프로젝트입니다.

1. drawLine을 이용해 선 그리기
2. drawRect, drawRoundRect 등을 이용해 사각형 그리기
- inset을 이용해 가장자리에 여러 설정을 할 수 있다
- rotate를 이용해 도형을 돌릴 수 있다
3. drawCircle을 이용해 원 그리기
4. drawOval을 이용해 타원 그리기
5. drawRect 또는 drawCircle에 brush와 Color를 이용해 그라데이션을 넣거나, 그림자 효과 그리기
6. drawArc를 사용해 부채꼴 그리기
7. drawPath를 이용해 곡선 그리기
- Path 인스턴스에 moveTo를 이용해 시작지점으로 이동, quadraticBezierTo로 '중간 지점'과 '목표 지점'을 설정해 곡선을 그린다
- lineTo를 사용해 직선 그리기
- 마지막에는 close로 반드시 닫아준다
8. drawPoints을 이용해 점선 곡선 그리기
9. drawImage를 이용해 이미지 그리기(tint 색상 필터 등 다양한 기능들 사용 가능)
- ImageBitmap.imageResour로 이미지를 가져와 사용한다
