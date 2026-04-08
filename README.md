<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>최애 앨범 소개</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #7fff00 0%, #808000 50%, #ff00ff 100%);
            font-family: "Oswald", sans-serif;
            font-optical-sizing: auto;
            font-weight: 400;
            color: #ffffff;
            font-size: 18px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            text-align: center;
            }
             .listen-btn {
                background-color: #ffffff;
                color: #000000;
                padding: 10px 20px;
                font-size: 13px;
                border-radius: 5px;
             }

    </style>
</head>
<body>
    <header id="album-header">
        <p class="artist-name">Back to the 2000's</p>
        <h1>Y2K Playlist
        </h1>
        <p class="subtitle">다채로운 매력으로 가득 찬 플레이리스트</p>
    </header>

    <section class="lyrics-section">
        <h2>🎵 킬링 파트 가사</h2>
        <div class="lyrics-box">
            <p>404 Not found in the system</p>
            <p class="highlight">404 new era era</p>
            <p>404 좌표 밖의 지점</p>
            <p>404  new era era</p>
           <p>-kii kii </p>
        </div>
    </section>

    <section class="info-section">
        <h2>✨ 입덕 포인트</h2>
        <ul id="charm-list">
            <li>2000s 그 시절의 감성을 담아낸 비트들</li>
            <li>세기 말과 신세기의 교차점</li>
            <li>2000s 스타일의 독특한 사운드</li>
        </ul>
    </section>

    <section class="track-section">
        <h2>🎧 추천 플레이리스트</h2>
        <table id="track-table">
            <thead>
                <tr>
                    <th>Track</th>
                    <th>곡명</th>
                    <th>아티스트</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>01</td>
                    <td>Love Love Love</td>
                    <td>에픽하이</td>
                </tr>
                <tr>
                    <td>02</td>
                    <td>Circles</td>
                    <td>키마라 러브레이스</td>
                </tr>
                <tr>
                    <td>03</td>
                    <td>Hype Boy</td>
                    <td>뉴진스</td>
                </tr>
            </tbody>
        </table>
    </section>

    <footer id="album-footer">
        <button class="listen-btn">전곡 스밍하러 가기</button>
    </footer>
</body>
</html>
