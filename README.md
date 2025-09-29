# lo1<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Loans & Insurance</title>
    <style>
        body {
            background: #f8fafc;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .main-title {
            text-align: center;
            font-size: 1.4em;
            font-weight: 650;
            margin-top: 25px;
            color: #275db2;
        }
        .display-bar {
            margin: 25px auto 24px auto;
            width: 84%;
            text-align: center;
            border: 2px solid #51baf6;
            border-radius: 7px;
            background: #f6fdfe;
            padding: 17px 0;
            color: #295176;
            font-size: 1.13em;
            font-weight: 500;
        }
        .sections-container {
            display: flex;
            justify-content: space-around;
            align-items: flex-start;
            gap: 38px;
            width: 90%;
            margin: 22px auto 0 auto;
            padding-bottom: 32px;
        }
        .section-box {
            background: #fcfdff;
            border: 2px solid #6eb7e7;
            border-radius: 11px;
            min-width: 310px;
            max-width: 350px;
            padding: 29px 18px 18px 24px;
            box-shadow: 0 2px 14px #daeefd60;
        }
        .section-title {
            background: #479ede;
            color: #fff;
            font-size: 1.18em;
            font-weight: 600;
            padding: 9px 0;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 18px;
        }
        .steps-list {
            font-size: 1.03em;
            color: #273965;
            margin-left: 8px;
            margin-bottom: 8px;
        }
        .branch-title {
            margin: 12px 0 5px 0;
            font-weight: 600;
            color: #386ab3;
        }
        ul {
            margin: 0 0 8px 23px;
            padding: 0;
        }
        @media (max-width: 950px) {
            .sections-container {
                flex-direction: column;
                align-items: center;
                gap: 18px;
                width: 98%;
            }
            .section-box { min-width: 97%; max-width: 99%;}
        }
    </style>
</head>
<body>
    <div class="main-title">
        Loans & Insurance<br>
        &darr;<br>open
    </div>
    <div class="display-bar">
        add display
    </div>
    <div class="sections-container">
        <!-- Loans Section -->
        <div class="section-box">
            <div class="section-title">Loans</div>
            <div class="steps-list">
                &darr; open
                <ul>
                    <li>Loan</li>
                    <li>Car</li>
                    <li>Bike</li>
                    <li>House</li>
                    <li>Personal</li>
                    <li>Business</li>
                    <li>etc</li>
                </ul>
            </div>
        </div>
        <!-- Insurance Section -->
        <div class="section-box">
            <div class="section-title">Insurance</div>
            <div class="steps-list">
                &darr; open<br>
                &darr; Location
                <ul>
                    <li>Health</li>
                    <li>Mobile</li>
                    <li>Car</li>
                    <li>Bike</li>
                    <li>etc</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
