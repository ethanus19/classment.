<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🏆 Classement 🎉</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            text-align: center;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            width: 90%;
            max-width: 300px; /* Réduit de 0,75 cm de chaque côté */
            padding: 20px;
        }

        h2 {
            color: #4CAF50;
            font-size: 1.6rem;
            margin-bottom: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 12px;
            border-radius: 10px;
            text-align: center;
            font-size: 1rem;
        }

        th {
            background-color: #4CAF50;
            color: white;
            font-weight: bold;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        tr:hover {
            background-color: #e0e0e0;
        }

        td {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            transition: background-color 0.3s ease;
        }

        .emoji {
            font-size: 1.5rem;
        }

        .position {
            font-weight: bold;
        }

        .points {
            color: #FF5722;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>🏆 Classement 🎉</h2>
        <table>
            <thead>
                <tr>
                    <th>Position</th>
                    <th>Prénom</th>
                    <th>Points</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="position">🥇</td>
                    <td>Grace</td>
                    <td class="points">150</td>
                </tr>
                <tr>
                    <td class="position">🥈</td>
                    <td>Eve</td>
                    <td class="points">130</td>
                </tr>
                <tr>
                    <td class="position">🥉</td>
                    <td>Alice</td>
                    <td class="points">120</td>
                </tr>
                <tr>
                    <td class="position">4️⃣</td>
                    <td>Jack</td>
                    <td class="points">115</td>
                </tr>
                <tr>
                    <td class="position">5️⃣</td>
                    <td>Charlie</td>
                    <td class="points">110</td>
                </tr>
                <tr>
                    <td class="position">6️⃣</td>
                    <td>Ivy</td>
                    <td class="points">105</td>
                </tr>
                <tr>
                    <td class="position">7️⃣</td>
                    <td>Frank</td>
                    <td class="points">100</td>
                </tr>
                <tr>
                    <td class="position">8️⃣</td>
                    <td>Bob</td>
                    <td class="points">95</td>
                </tr>
                <tr>
                    <td class="position">9️⃣</td>
                    <td>Hannah</td>
                    <td class="points">90</td>
                </tr>
                <tr>
                    <td class="position">🔟</td>
                    <td>David</td>
                    <td class="points">80</td>
                </tr>
            </tbody>
        </table>
    </div>

</body>
</html>
