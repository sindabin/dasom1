<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>안케님 썸네일 자료</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh; /* 전체 화면 높이 */
            display: flex;
            flex-direction: column; /* 수직 정렬 */
            align-items: center; /* 중앙 정렬 */
            justify-content: flex-start; /* 상단 정렬 */
        }
        #main3 {
            width: 85%; /* 너비를 상대적으로 조정 */
            max-width: 1300px; /* 최대 너비 설정 */
            text-align: center; /* 텍스트 중앙 정렬 */
            background-color: rgb(34, 29, 29); /* 배경 색상 */
            padding: 10px; /* 여백 추가 */
            margin-top: 15px; /* 상단 여백 추가 */
        }
        #main2{
            width: 85%; /* 너비를 상대적으로 조정 */
            max-width: 1300px; /* 최대 너비 설정 */
            text-align: center; /* 텍스트 중앙 정렬 */
        }
        .aa1 {
            margin: 0; /* 기본 마진 제거 */
            color: rgb(223, 209, 192);
        }
        p {
            margin: 0; /* 기본 마진 제거 */
        }
        img {
            margin-top: 20px; /* 상단 여백 추가 (선택 사항) */
            cursor: pointer; /* 클릭 시 커서 모양 변경 */
            max-width: 100%; /* 부모 요소의 너비에 맞게 조정 */
            
        }
        .modal {
            display: none; /* 기본적으로 숨김 */
            position: fixed; /* 화면 전체에 고정 */
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8); /* 반투명 검정 배경 */
            justify-content: center; /* 중앙 정렬 */
            align-items: center; /* 중앙 정렬 */
            z-index: 1000; /* 다른 요소 위에 표시 */
        }
        .modal img {
            max-width: 100%; /* 모달 창 내에서 이미지 최대 너비 */
            max-height: 95%; /* 모달 창 내에서 이미지 최대 높이 */
        }
        .modal-close {
            position: absolute;
            top: 20px;
            right: 20px;
            color: #fff;
            font-size: 24px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div id="main3">
        <h1 class="aa1">DASOM 썸네일 샘플</h1>
    </div>
    <div id="main2">
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfOSAg/MDAxNzI1MjgwMDUyNTk1.0zusyFcHN_EQQQN-IlgnjSW3Ait2ccqAYlFA69mNZ-Qg.YYd1ByJ2obrJX7iiSU-C9u_ulGfYcVwHwGHVZqsTXngg.PNG/%EC%95%88%EC%BC%80%EB%8B%98_%EC%8D%B8%EB%84%A4%EC%9D%BC.png?type=w966" 
        id="img1" width="500px">
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfMTE2/MDAxNzI1MjgwMDU0Mzc4.QuLl_oVNFF4856Je1dEO51VFVRW-1MGWmzkgl3nj0TMg.ipQFbs_meRgQ1wMODiYZtbRaoSff8yKCeHUjV5WUAy8g.PNG/%EC%95%88%EC%BC%80%EB%8B%98_%EC%8D%B8%EB%84%A4%EC%9D%BC2.png?type=w966" 
        id="img2" width="500px">
        <br>
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfMjEg/MDAxNzI1MjgwMDc1ODQ4.alFhdbxxk599AG4xQk_l_XeO_8Q8MKLns-iGU4D94AMg.-7JrdicStyy16z0iuaLkMTq32_LMxX698-DGto_x2H0g.PNG/%EB%A6%AC%EC%A0%9C%EB%8B%98_%EC%8D%B8%EB%84%A4%EC%9D%BC1.png?type=w966"
        width="500px">
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfMTQ1/MDAxNzI1MjgwMDY0Njgx.zjyqLg9myqQ5OWy7FnCskDDZeeV4bx6DaM0xnn45pIEg.UsuNkazahITVgRXZWlsWqdKmp1HMVuis3Y2IN_Zp1V0g.PNG/%EC%B9%B8%EB%82%98%EB%8B%98%EC%8D%B8%EB%84%A4%EC%9D%BC1.png?type=w966"
        width="500px">
        <br>
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfMjgw/MDAxNzI1MjgwMDc1OTk0.YQjQ2FSmLwZ-RIaIUpwsraE7fZ0zB1OV3I47wW51Qpwg.tzaI6aFRjImvML1H-EM-FI109nrmMUV84Q2D7-iLE58g.PNG/%EB%A6%AC%EC%A0%9C%EB%8B%98_%EC%8D%B8%EB%84%A4%EC%9D%BC2.png?type=w966"
        width="500px">
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfOTUg/MDAxNzI1MjgwMDY0NDA1.5YIX87ySqXucd5sSDfNFYPnElCXgaTgKrELLPBBgOcUg.YXhzn7F9jiJeUuQk3JerZYQIYPro9AQMKArV6mXcRekg.PNG/%EC%B9%B8%EB%82%98%EB%8B%98%EC%8D%B8%EB%84%A4%EC%9D%BC3.png?type=w966"
        width="500px">
        <br>
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfMTkg/MDAxNzI1MjgwMDY0ODE4.0EL3wvd2qm-2SdGM8TnECtO3MWxPZ68XzxDgHmbWtcAg.bvqI0c8W_hZlplSuE_VyUMfPfNDL13QzchH1r02n1Acg.PNG/%EC%B9%B8%EB%82%98%EB%8B%98%EC%8D%B8%EB%84%A4%EC%9D%BC2.png?type=w966"
        width="500px">
        <img src="https://postfiles.pstatic.net/MjAyNDA5MDJfMTY5/MDAxNzI1MjgwMDUzMjc4.PPR1rJRzUwrkKkqMTbqVAYRCrZz5k8mALYyA-EMCUiYg.XqTjAHvWRr9c5_jQJ5MG1drEaTx-8Olo-q9Luw18exQg.PNG/%EC%95%BC%EC%BD%94%EC%BD%94%EB%8B%98.png?type=w966"
        width="500px">
    </div>
    <div id="modal" class="modal">
        <span id="close" class="modal-close">&times;</span>
        <img id="modal-img" src="" alt="Enlarged Image">
    </div>
    <script>
        // 모달 관련 변수
        const modal = document.getElementById('modal');
        const modalImg = document.getElementById('modal-img');
        const close = document.getElementById('close');

        // 모든 이미지 요소를 가져와 클릭 이벤트 추가
        document.querySelectorAll('#main2 img').forEach(img => {
            img.onclick = function() {
                modal.style.display = 'flex';
                modalImg.src = this.src;
            };
        });

        // 모달 닫기 버튼 클릭 시 모달 닫기
        close.onclick = function() {
            modal.style.display = 'none';
        };

        // 모달 바깥 클릭 시 모달 닫기
        window.onclick = function(event) {
            if (event.target == modal) {
                modal.style.display = 'none';
            }
        };
    </script>
</body>
</html>
