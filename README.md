<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VR‑HI3559AV100 | 海思VR一体机眼镜主板</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #0f1117;
            color: #e6edf3;
            line-height: 1.7;
            padding: 0 16px;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 48px 0;
        }
        .hero {
            text-align: center;
            margin-bottom: 52px;
        }
        .hero h1 {
            font-size: 2.6rem;
            color: #58a6ff;
            margin-bottom: 12px;
        }
        .hero p.subtitle {
            font-size: 1.2rem;
            color: #8b949e;
            max-width: 720px;
            margin: 0 auto;
        }
        .notice-box {
            background-color: rgba(248, 181, 83, 0.12);
            border: 1px solid #f8b553;
            border-radius: 10px;
            padding: 18px 22px;
            margin: 32px 0;
            color: #f9d398;
        }
        h2 {
            font-size: 1.6rem;
            margin: 42px 0 18px;
            color: #c9d1d9;
            border-left: 4px solid #58a6ff;
            padding-left: 14px;
        }
        .feature-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 14px;
            margin: 20px 0 32px;
        }
        .feature-item {
            background-color: #161b22;
            padding: 16px;
            border-radius: 8px;
            border: 1px solid #30363d;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 16px;
            margin: 20px 0;
        }
        .gallery-item {
            overflow: hidden;
            border-radius: 10px;
            border: 1px solid #30363d;
            background-color: #161b22;
        }
        .gallery-item img {
            width: 100%;
            height: auto;
            display: block;
        }
        .caption {
            padding: 10px 14px;
            font-size: 0.9rem;
            color: #8b949e;
        }
        .tip-text {
            color:#8b949e;
            margin:10px 0 20px;
        }
        footer {
            margin-top: 60px;
            padding-top:24px;
            border-top:1px solid #30363d;
            color:#6e7681;
            font-size:0.9rem;
            text-align:center;
        }
    </style>
</head>
<body>
<div class="container">
    <section class="hero">
        <h1>VR‑HI3559AV100</h1>
        <p class="subtitle">基于海思 HI3559AV100 的 VR 一体机眼镜主板开源工程</p>
    </section>

    <div class="notice-box">
        ⚠️ 作品仅供学习参考，请勿直接打板。整体硬件成本很高，项目仍存在较多不完善之处。
    </div>

    <h2>项目简介</h2>
    <p>完整8层PCB VR眼镜硬件方案，主控采用海思 HI3559AV100，面向室内多人交互VR场景设计；外壳结构参考苹果 Vision Pro。</p>

    <h2>核心硬件规格</h2>
    <div class="feature-list">
        <div class="feature-item">4颗 DDR4，最大支持 8GB</div>
        <div class="feature-item">板载 UFS 存储</div>
        <div class="feature-item">2片视涯 1.3英寸 Micro‑OLED 显示</div>
        <div class="feature-item">4颗豪威 4‑Lane 摄像头</div>
        <div class="feature-item">4G / Wi‑Fi 通信模块</div>
        <div class="feature-item">VR瞳距调节电机</div>
        <div class="feature-item">UWB定位芯片，支持多人室内VR互动</div>
        <div class="feature-item">HDMI 等丰富外部接口</div>
    </div>

    <h2>项目效果图</h2>
    <div class="gallery">
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/5074848b-05ce-4429-ac6e-85620fa9618b" alt="效果图1">
        </div>
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/971124bf-e337-483c-aff3-837a16432746" alt="效果图2">
        </div>
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/e6037438-acc4-4fea-b8b8-10306c73db71" alt="效果图3">
        </div>
    </div>

    <h2>PCB 设计</h2>
    <p class="tip-text">作者一直觉得PCB是一项艺术。下图已经移除顶层铺铜。</p>
    <div class="gallery">
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/ea8502c1-4ccb-4acb-8d02-c5b9d99d1be9" alt="PCB图1">
        </div>
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/5a5d7b01-f0f1-4cec-95d3-74f9a6373c49" alt="PCB图2">
        </div>
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/9746433c-77ca-44ee-abeb-480b7085983e" alt="PCB图3">
        </div>
    </div>

    <h2>3D模型图</h2>
    <div class="gallery">
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/3b7e4003-4353-4b21-9436-f5070ac06aa0" alt="模型1">
        </div>
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/47f8871a-45c5-4cee-a835-f4c2d20a0a54" alt="模型2">
        </div>
        <div class="gallery-item">
            <img src="https://github.com/user-attachments/assets/611a3316-1948-43f1-ab2f-8f96e7df4fc5" alt="模型3">
        </div>
    </div>

    <footer>
        VR‑HI3559AV100｜开源硬件项目展示页
    </footer>
</div>
</body>
</html>
