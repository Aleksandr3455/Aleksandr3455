<!DOCTYPE html>
<html>
<head>
    <title>BAYBWallet</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css">
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
</head>
<body>
    <div class="container">
        <header class="app-header">
            <h1>BAYBWallet</h1>
        </header>

        <div class="balance-section">
            <div class="balance-card">
                <span class="balance-label">Мой баланс</span>
                <span class="balance-amount" id="balance">$0.00</span>
            </div>
        </div>

        <div class="referral-section">
            <h2>Мои рефералы</h2>
            <div class="referral-stats">
                <div class="stat-item">
                    <span class="stat-value" id="referral-count">0</span>
                    <span class="stat-label">Рефералов</span>
                </div>
                <div class="stat-item">
                    <span class="stat-value" id="referral-earnings">$0.00</span>
                    <span class="stat-label">Заработано</span>
                </div>
            </div>
        </div>

        <div class="actions-section">
            <button class="tg-button primary" id="topup-btn">
                Пополнить баланс
            </button>
            <button class="tg-button success" id="withdraw-btn">
                Доступно к выводу: <span id="available-amount">$0.00</span>
            </button>
        </div>
    </div>

    <script src="app.js"></script>
</body>
</html>
