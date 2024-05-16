<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>跳转中…</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: white;
            color: black;
        }
        h3 {
            font-size: 48px; /* 放大标题字体 */
            margin-bottom: 30px;
        }
        #rocket {
            font-size: 144px; /* 放大火箭图标 */
            margin-bottom: 30px;
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-30px);
            }
            60% {
                transform: translateY(-15px);
            }
        }
        #countdown {
            font-size: 144px; /* 放大倒计时数字字体 */
            color: #007bff; /* 蓝色 */
            font-weight: bold;
            margin: 30px 0;
            display: block; /* 将数字显示为块级元素 */
            margin: 0 auto; /* 水平居中 */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
            animation: pulse 1s infinite;
        }
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }
        .button-container {
            display: flex;
            justify-content: center;
            gap: 30px; /* 按钮之间的间距 */
        }
        button {
            padding: 25px 50px; /* 增大按钮的内边距 */
            font-size: 32px; /* 增大按钮字体 */
            cursor: pointer;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 25px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s, transform 0.3s;
        }
        button:hover {
            background-color: #0056b3;
            transform: translateY(-2px);
        }
        .ad-container {
            margin-top: 30px;
            width: 600px;
            height: 200px;
            border: 2px dashed #007bff;
            border-radius: 15px;
            background-color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .ad-container a {
            font-size: 30px; /* 广告文字字体 */
            color: black; /* 黑色字体 */
            text-decoration: none;
        }
        .ad-container a:hover {
            text-decoration: underline;
        }
        .footer {
            position: absolute;
            bottom: 30px;
            width: 100%;
            text-align: center;
            font-size: 24px; /* 增大底部文字字体 */
            color: gray;
        }
        .language-switch {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 18px;
            font-weight: bold;
            color: gray;
        }
        .language-switch span {
            cursor: pointer;
            margin-left: 10px;
        }
        .language-switch span:hover {
            color: black;
        }
        /* 覆盖层样式 */
        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }
        .modal {
            background: white;
            padding: 50px; /* 增大内边距 */
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 600px; /* 增大最大宽度 */
            width: 90%;
        }
        .modal p {
            font-size: 25px;
            margin-bottom: 20px;
        }
        .modal button {
            padding: 10px 20px;
            font-size: 22px;
            cursor: pointer;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .modal button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="language-switch">
        <span id="lang-zh">中文</span> ｜<span id="lang-en">English</span>
    </div>
    <div id="rocket">🚀</div>
    <h3><span id="countdown">5</span> 秒后跳转到NextWeb</h3>
    <div class="button-container">
        <button id="googleBtn">NextWeb【推荐】</button>
        <button id="baiduBtn">Lobe</button>
    </div>
    <div class="ad-container">
        <a href="https://qr.alipay.com/fkx16480lgnw1yqksezmab7" target="_blank">捐赠｜Alipay donation</a>
    </div>
    <div class="footer">
        邮箱：admin@houyinx.top
    </div>

    <!-- 覆盖层 -->
    <div id="overlay" class="overlay">
        <div class="modal">
            <p>根据《生成式人工智能服务管理办法》及相关法律法规规定，请您务必在合规范围之内使用本站语言大模型，本站不存储您的任何信息，且不对任何生成结果负有任何责任，请知悉！</p>
            <button id="acknowledgeButton">同意</button>
        </div>
    </div>

    <script>
        // 多语言文本定义
        const texts = {
            zh: {
                countdown: "秒后跳转到NextWeb",
                googleBtn: "NextWeb【推荐】",
                baiduBtn: "Lobe",
                footer: "邮箱：admin@houyinx.top",
                adContent: "捐赠｜Alipay donation"
            },
            en: {
                countdown: "seconds to redirect to NextWeb",
                googleBtn: "NextWeb 【Recommended】",
                baiduBtn: "Lobe",
                footer: "Email: admin@houyinx.top",
                adContent: "捐赠｜Alipay donation"
            }
        };

        // 获取元素
        const h3 = document.querySelector('h3');
        const googleBtn = document.getElementById('googleBtn');
        const baiduBtn = document.getElementById('baiduBtn');
        const footer = document.querySelector('.footer');
        const langZh = document.getElementById('lang-zh');
        const langEn = document.getElementById('lang-en');
        const adContainer = document.querySelector('.ad-container a');

        // 语言切换函数
        function switchLanguage(lang) {
            h3.innerHTML = `<span id="countdown">${counter}</span> ${texts[lang].countdown}`;
            googleBtn.textContent = texts[lang].googleBtn;
            baiduBtn.textContent = texts[lang].baiduBtn;
            footer.textContent = texts[lang].footer;
            adContainer.textContent = texts[lang].adContent;
        }

        // 绑定语言切换按钮事件
        langZh.addEventListener('click', () => switchLanguage('zh'));
        langEn.addEventListener('click', () => switchLanguage('en'));

        // 倒计时逻辑
        const span = document.getElementById('countdown');
        let counter = 5;
        let timerId;

        function startCountdown() {
            timerId = setInterval(function() {
                counter -= 1;
                if (counter === 0) {
                    location.href = 'https://aione.houyinx.top';
                } else {
                    span.textContent = counter;
                }
            }, 1000);
        }

        // 按钮跳转逻辑
        baiduBtn.addEventListener('click', () => {
            clearInterval(timerId);
            location.href = 'https://aitwo.houyinx.top';
        });

        googleBtn.addEventListener('click', () => {
            clearInterval(timerId);
            location.href = 'https://aione.houyinx.top';
        });

        // 提示窗口逻辑
        document.getElementById('acknowledgeButton').addEventListener('click', function() {
            document.getElementById('overlay').style.display = 'none';
            startCountdown();
        });
    </script>
</body>
</html>
