<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Løftekalkulator - Fiberstropper</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .calculator {
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 25px;
            max-width: 400px;
            width: 100%;
            text-align: center;
        }
        h1 {
            font-size: 22px;
            color: #333;
        }
        label {
            display: block;
            margin-top: 15px;
            font-weight: bold;
            text-align: left;
        }
        select {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        button {
            width: 100%;
            padding: 12px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #0056b3;
        }
        .result {
            margin-top: 20px;
            font-size: 20px;
            font-weight: bold;
            color: #333;
            background: #e6f7ff;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="calculator">
        <h1>Løftekalkulator - Fiberstropper</h1>
        <label for="dimension">Velg Dimensjon:</label>
        <select id="dimension">
            <option value="1">1 tonn - Fiolett</option>
            <option value="2">2 tonn - Grønn</option>
            <option value="3">3 tonn - Gul</option>
            <option value="4">4 tonn - Grå</option>
            <option value="5">5 tonn - Rød</option>
            <option value="6">6 tonn - Brun</option>
            <option value="8">8 tonn - Blå</option>
            <option value="10">10 tonn - Oransje</option>
        </select>

        <label for="attachment">Velg Innfestingsmåte:</label>
        <select id="attachment">
            <option value="Rett">Rett</option>
            <option value="Snaret">Snaret</option>
            <option value="U/Dobbel">U/Dobbel</option>
            <option value="U: 0°-45°">U: 0°-45°</option>
            <option value="U: 45°-60°">U: 45°-60°</option>
        </select>

        <label for="parts">Velg antall Parter:</label>
        <select id="parts">
            <option value="1">En Stropp</option>
            <option value="2">To Stropper</option>
            <option value="3-4">Tre- og Fire Stropper</option>
        </select>

        <label for="angle">Velg Arbeidsvinkel:</label>
        <select id="angle">
            <option value="1.0">0°</option>
            <option value="0.8">1°-30°</option>
            <option value="0.7">31°-45°</option>
            <option value="0.5">46°-60°</option>
        </select>

        <button onclick="calculate()">Beregn</button>
        <div class="result" id="result">Maks belastning: <span id="maxLoad">0</span> tonn</div>
    </div>

    <script>
        function calculate() {
            const dimension = parseFloat(document.getElementById('dimension').value);
            const attachment = document.getElementById('attachment').value;
            const parts = document.getElementById('parts').value;
            const angleFactor = parseFloat(document.getElementById('angle').value);

            let baseLoad = dimension;

            if (attachment === "Snaret") {
                baseLoad *= 0.8;
            } else if (attachment === "U/Dobbel") {
                baseLoad *= 2.0;
            } else if (attachment === "U: 0°-45°") {
                baseLoad *= 1.7;
            } else if (attachment === "U: 45°-60°") {
                baseLoad *= 1.4;
            }

            if (parts === "2") {
                baseLoad *= 2.1;
            } else if (parts === "3-4") {
                baseLoad *= 3.0;
            }

            let maxLoad = baseLoad * angleFactor;

            document.getElementById('maxLoad').innerText = maxLoad.toFixed(2);
        }
    </script>
</body>
</html>
