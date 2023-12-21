<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>DOM 프로그래밍</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        function transform() {
            // 2진수 입력란에서 값을 가져옵니다.
            const binaryInput = document.getElementById("digit").value;

            // 2진수를 10진수로 변환합니다.
            const decimalValue = parseInt(binaryInput, 2);

            // 10진수를 16진수로 변환하고 대문자로 표시합니다.
            const hexValue = decimalValue.toString(16).toUpperCase();

            // 결과를 16진수 입력란에 표시합니다.
            document.getElementById("hexanum").value = hexValue;
        }

        function pascals() {
            // 사용자가 입력한 높이 값을 가져옵니다.
            const height = parseInt(document.getElementById("size").value);

            // 결과를 표시할 영역을 가져옵니다.
            const drawArea = document.getElementById("draw_area");

            // 이전에 표시된 내용을 초기화합니다.
            drawArea.innerHTML = "";

            // 파스칼의 삼각형을 계산하고 표시합니다.
            for (let i = 0; i < height; i++) {
                let row = "1";
                for (let j = 1; j <= i; j++) {
                    // 이항 계수를 계산합니다.
                    const coefficient = binomialCoefficient(i, j);
                    row += ` ${coefficient}`;
                }

                // 한 행을 표시하고 줄 바꿈을 추가합니다.
                drawArea.innerHTML += row + "<br>";
            }
        }

        function binomialCoefficient(n, k) {
            // 이항 계수를 재귀적으로 계산합니다.
            if (k === 0 || k === n) {
                return 1;
            } else {
                return binomialCoefficient(n - 1, k - 1) + binomialCoefficient(n - 1, k);
            }
        }
    </script>
</head>
<body>
<div class="container mt-5">
    <div class="h3">2진수 변환기</div>
    <div class="mb-3">
        <label class="form-label text-primary">2 진수 :
            <input type="text" id="digit" size="20">
        </label>
        <button type="button" class="btn btn-dark" onclick="transform()"> ===> </button>
        <label class="form-label text-primary">16 진수
            <input type="text" id="hexanum" size="20" readonly>
        </label>
    </div>
    <hr>
    <div class="h3">파스칼 삼각형</div>
    <div class="mb-3">
        <label class="form-label text-primary">삼각형 높이
            <input type="number" id="size" min="1" max="20" step="1" value="1">
        </label>
        <button type="button" class="btn btn-success" onclick="pascals()">그리기</button>
    </div>
    <div class="text-bg-secondary" id="draw_area"></div>
</div>
</body>
</html>
