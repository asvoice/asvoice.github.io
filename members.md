asvoice.github.io 메인 페이지는 아마도 여러 이미지가 가로/세로 그리드(Grid) 형태로 정렬되어 배치된 형태일 것입니다. 반면, 일반적인 마크다운 표(Table)는 단순히 세로로 길게 나열되기 때문에 느낌이 다를 수 있습니다.

메인 페이지처럼 **그리드 형태(바둑판 배열)**로 보이게 하려면 마크다운 안에 HTML 태그(<div>)와 스타일을 직접 섞어서 사용해야 합니다. 깃허브(GitHub) README나 페이지에서 잘 작동하도록 코드를 짜드렸습니다.

아래 코드를 전체 복사해서 .md 파일에 넣으시면 메인처럼 이미지들이 나란히 배치될 거예요.

🎨 멤버 리스트 (메인 스타일 그리드)
HTML

<div style="display: flex; flex-wrap: wrap; gap: 20px; text-align: center;">

  <div style="width: 150px;">
    <a href="https://www.instagram.com/rush_eging_team/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/r.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <b>Rush Team</b>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/be_a_simpleman/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/1.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">be_a_simpleman</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/sd179_6/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/2.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">sd179_6</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/p/DNLWWXBzyP-/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/3.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">bong_dari__</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/big_angler_seok/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/big3.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">big_angler</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/whaaat_sap/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/5.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">whaaat_sap</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/13readen.miyeok/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/6.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">13readen.miyeok</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/khyo4851/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/8.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">khyo4851</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/maestro_bong/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/9.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">maestro_bong</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/henry_.0321/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/10.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">henry_.0321</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/toto_lightgame/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/11.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">toto_lightgame</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/unifishing/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/12.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">unifishing</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/hooni_hoon/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/13.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">hooni_hoon</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://www.instagram.com/1____kyung/" target="_blank">
      <img src="https://raw.githubusercontent.com/asvoice/asvoice.github.io/refs/heads/main/assets/img/14.PNG" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <span style="font-size: 0.9em;">1____kyung</span>
    </a>
  </div>

  <div style="width: 150px;">
    <a href="https://asvoice.github.io/" target="_blank">
      <img src="https://github.com/lexicalunit/spellbot/assets/1903876/32c324a3-b060-4bd2-8d8a-a72799acc0ff" width="150" height="150" style="border-radius: 10px; object-fit: cover;"><br>
      <b>대구 또또</b>
    </a>
  </div>

</div>
