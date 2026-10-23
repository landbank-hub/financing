<!DOCTYPE html>
<html lang="zh-Hant-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>臺灣土地銀行 中小企業資金規劃｜測試網</title>
    <!-- 引入 Tailwind CSS 進行快速現代化排版 -->
    <script src="https://jsdelivr.net"></script>
    <style>
        /* 土地銀行企業標準色定義 */
        :root {
            --lb-dark-green: #0A5C36; /* 土銀經典深綠 */
            --lb-light-green: #E8F5E9; /* 淺綠背景 */
            --lb-gold: #D4AF37; /* 穩健金 */
        }
        .bg-lb-green { background-color: var(--lb-dark-green); }
        .text-lb-green { color: var(--lb-dark-green); }
        .border-lb-green { border-color: var(--lb-dark-green); }
        .hover-bg-lb-green:hover { background-color: #08492B; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- 導覽列 -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <!-- 土銀風格標誌意象 -->
                <div class="w-8 h-8 bg-lb-green rounded-full flex items-center justify-center text-white font-bold text-sm">土</div>
                <span class="text-xl font-bold text-lb-green tracking-wider">臺灣土地銀行 <span class="text-gray-500 text-sm font-normal">| 中小企業資金規劃測試網</span></span>
            </div>
            <div class="hidden md:flex space-x-6 font-medium text-gray-600">
                <a href="#purpose" class="hover:text-lb-green">資金用途</a>
                <a href="#calc" class="hover:text-lb-green">財務健檢</a>
                <a href="#files" class="hover:text-lb-green">文件準備</a>
                <a href="#contact" class="bg-lb-green text-white px-4 py-1.5 rounded-full hover-bg-lb-green transition">專人聯繫 ↗</a>
            </div>
        </div>
    </nav>

    <!-- 主視覺區 Hero Section -->
    <header class="bg-gradient-to-br from-[#0A5C36] to-[#1B8A5A] text-white py-20 px-4 text-center">
        <div class="max-w-4xl mx-auto">
            <p class="text-sm tracking-widest uppercase mb-3 opacity-90">LAND BANK OF TAIWAN · BUSINESS FINANCING</p>
            <h1 class="text-4xl md:text-5xl font-extrabold mb-6 tracking-tight leading-tight">
                讓土地銀行，<br class="md:hidden">深耕您的企業厚土。
            </h1>
            <p class="text-lg md:text-xl opacity-90 mb-8 max-w-2xl mx-auto font-light">
                從在地的日常週轉金、廠房購置，到前瞻的海外經貿佈局，<br>土銀與您攜手，為生意的下一步打下最穩固的資金基石。
            </p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="#purpose" class="bg-white text-lb-green font-bold px-8 py-3 rounded-lg shadow-lg hover:bg-gray-100 transition">開始資金規劃 →</a>
                <a href="#health" class="bg-transparent border border-white font-bold px-8 py-3 rounded-lg hover:bg-white/10 transition">進行企業財務健檢 ↗</a>
            </div>
        </div>
    </header>

    <!-- 流程說明區 -->
    <section class="max-w-7xl mx-auto px-4 py-16">
        <h2 class="text-2xl font-bold text-center mb-12 text-lb-green">一次看懂土地銀行資金規劃流程</h2>
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
            <div class="p-6 bg-white rounded-xl shadow-sm border-t-4 border-lb-green">
                <div class="text-3xl font-extrabold text-gray-300 mb-2">01</div>
                <h3 class="font-bold text-lg mb-2">選擇資金用途</h3>
                <p class="text-gray-600 text-sm">依據進貨週轉、購置建廠或擴展據點，選取最適合您產業的財務評估模型。</p>
            </div>
            <div class="p-6 bg-white rounded-xl shadow-sm border-t-4 border-lb-green">
                <div class="text-3xl font-extrabold text-gray-300 mb-2">02</div>
                <h3 class="font-bold text-lg mb-2">輸入經營數據</h3>
                <p class="text-gray-600 text-sm">填入預估營業額、應收付帳款天數與預算，將營運現場經驗化為具體財務數字。</p>
            </div>
            <div class="p-6 bg-white rounded-xl shadow-sm border-t-4 border-lb-green">
                <div class="text-3xl font-extrabold text-gray-300 mb-2">03</div>
                <h3 class="font-bold text-lg mb-2">試算資金缺口</h3>
                <p class="text-gray-600 text-sm">實時檢視資金缺口與還款負擔。本網頁為獨立試算，資料**不會**自動上傳雲端。</p>
            </div>
            <div class="p-6 bg-white rounded-xl shadow-sm border-t-4 border-lb-green">
                <div class="text-3xl font-extrabold text-gray-300 mb-2">04</div>
                <h3 class="font-bold text-lg mb-2">導向專員諮詢</h3>
                <p class="text-gray-600 text-sm">一鍵複製您的專屬試算摘要，前往土地銀行官方留言板，由專業企業融資經理與您接洽。</p>
            </div>
        </div>
    </section>

    <!-- 資金用途選擇 -->
    <section id="purpose" class="bg-gray-100 py-16 px-4">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl font-bold text-center mb-4 text-lb-green">這筆資金，要讓生意走到哪裡？</h2>
            <p class="text-gray-600 text-center mb-12">依據土地銀行多元融資方案，為您量身打造四大規劃模型。</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-sm flex items-start space-x-4">
                    <div class="p-3 bg-green-50 rounded-lg text-lb-green font-bold">📢</div>
                    <div>
                        <h3 class="font-bold text-lg mb-1 text-gray-900">營運週轉金融資</h3>
                        <p class="text-gray-600 text-sm mb-3">解決先進貨、後收款的日常時間差。估算公司規模擴大後，應增備的流動性週轉資金。</p>
                        <span class="text-xs font-semibold px-2 py-1 bg-gray-100 text-gray-600 rounded">適用：批發貿易 · 製造加工 · 零售電商</span>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-sm flex items-start space-x-4">
                    <div class="p-3 bg-green-50 rounded-lg text-lb-green font-bold">🏢</div>
                    <div>
                        <h3 class="font-bold text-lg mb-1 text-gray-900">購地建廠與設備貸款</h3>
                        <p class="text-gray-600 text-sm mb-3">發揮土銀土地金融核心優勢。將購地、擴建廠房的大筆資本支出，轉化為清晰的長期還款計畫。</p>
                        <span class="text-xs font-semibold px-2 py-1 bg-gray-100 text-gray-600 rounded">適用：工業區建廠 · 倉儲物流 · 傳統製造業</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 核心文件下載（改為土地銀行專屬表單命名） -->
    <section id="files" class="max-w-7xl mx-auto px-4 py-16">
        <h2 class="text-3xl font-bold text-center mb-2 text-lb-green">申貸表單下載專區</h2>
        <p class="text-gray-600 text-center mb-12">請先下載參考。實際徵提項目與適用版本，請交由土地銀行服務專員確認後辦理。</p>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- 卡片 1 -->
            <div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="text-xs font-bold text-lb-green uppercase mb-1">土銀制式表單</div>
                    <h3 class="font-bold text-lg mb-2 text-gray-900">法人、團體授信申請書</h3>
                    <p class="text-sm text-gray-600 mb-6">適用於一般大中型企業融資、建築貸款等申貸基礎，內含資金用途與還款來源說明。</p>
                </div>
                <button class="w-full bg-lb-green text-white text-sm py-2 rounded font-medium hover-bg-lb-green transition">下載 PDF ↓</button>
            </div>
            <!-- 卡片 2 -->
            <div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="text-xs font-bold text-lb-green uppercase mb-1">小微企業專用</div>
                    <h3 class="font-bold text-lg mb-2 text-gray-900">中小企業簡易授信申請書</h3>
                    <p class="text-sm text-gray-600 mb-6">針對資本額或授信總額較小之小微企業、行號簡化填寫欄位，加速銀行內部審查流程。</p>
                </div>
                <button class="w-full bg-lb-green text-white text-sm py-2 rounded font-medium hover-bg-lb-green transition">下載 PDF ↓</button>
            </div>
            <!-- 卡片 3 -->
            <div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="text-xs font-bold text-lb-green uppercase mb-1">徵信審查必要</div>
                    <h3 class="font-bold text-lg mb-2 text-gray-900">企業基本資料與營運計畫表</h3>
                    <p class="text-sm text-gray-600 mb-6">用於詳細填列公司近三年財務往來、主要產銷客戶名單及股東同一關係人結構。</p>
                </div>
                <button class="w-full bg-lb-green text-white text-sm py-2 rounded font-medium hover-bg-lb-green transition">下載 PDF ↓</button>
            </div>
        </div>
    </section>

    <!-- 頁尾 -->
    <footer class="bg-gray-900 text-gray-400 py-12 text-center text-sm px-4">
        <p class="text-white font-bold mb-3 text-base">臺灣土地銀行 中小企業資金規劃 測試網</p>
        <p class="max-w-2xl mx-auto mb-6 opacity-75">
            本網頁僅供內部互動式操作示範與教學情境試算工具，無實際送件、送審或承諾核貸之功能。網頁內所有輸入資料皆在您的個人瀏覽器端處理，不會實際回傳至土地銀行伺服器。
        </p>
        <p>© 2026 Land Bank of Taiwan. Demo Workspace. All Rights Reserved.</p>
    </footer>

</body>
</html>
