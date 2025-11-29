<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart Disease Prediction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #3e70e4;
            padding: 40px;
        }
        .container {
            width: 450px;
            margin: auto;
            background: rgb(5, 206, 112);
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border-radius: 6px;
            border: 1px solid #ae18be;
        }
        button {
            width: 100%;
            padding: 12px;
            background: #007bff;
            border: none;
            color: rgb(26, 195, 228);
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 12px;
        }
        button:hover {
            background: #005ec4;
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            text-align: center;
            font-weight: bold;
            border-radius: 8px;
            display: none;
        }
        .danger {
            background: #ffcccc;
            color: #c40000;
        }
        .safe {
            background: #635656;
            color: #006400;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Heart Disease Prediction</h2>

        <label>Age</label>
        <input type="number" id="age">

        <label>Sex</label>
        <select id="sex">
            <option value="1">Male</option>
            <option value="0">Female</option>
        </select>

        <label>Chest Pain Type (cp)</label>
        <select id="cp">
            <option value="0">0 – Typical Angina</option>
            <option value="1">1 – Atypical Angina</option>
            <option value="2">2 – Non-anginal</option>
            <option value="3">3 – Asymptomatic</option>
        </select>

        <label>Resting BP (trestbps)</label>
        <input type="number" id="bp">

        <label>Cholesterol</label>
        <input type="number" id="chol">

        <label>Max Heart Rate (thalach)</label>
        <input type="number" id="thalach">

        <button onclick="predict()">Predict</button>

        <div id="result"></div>
    </div>

    <script>
        function predict() {
            const data = {
                age: document.getElementById("age").value,
                sex: document.getElementById("sex").value,
                cp: document.getElementById("cp").value,
                trestbps: document.getElementById("bp").value,
                chol: document.getElementById("chol").value,
                thalach: document.getElementById("thalach").value
            };

            fetch("http://127.0.0.1:5000/predict", {
                method: "POST",
                headers: {"Content-Type": "application/json"},
                body: JSON.stringify(data)
            })
            .then(res => res.json())
            .then(result => {
                let box = document.getElementById("result");
                box.style.display = "block";

                if (result.prediction === 1) {
                    box.className = "danger";
                    box.innerHTML = "⚠ High Chance of Heart Disease";
                } else {
                    box.className = "safe";
                    box.innerHTML = "✔ No Major Heart Disease Risk";
                }
            })
            .catch(err => alert("Server not running! Start Flask backend."));
        }
    </script>

</body>
</html>
