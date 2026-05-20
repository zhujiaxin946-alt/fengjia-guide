<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>逢甲玩樂指南 Fengjia Fun Guide</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        html { scroll-behavior: smooth; }
        .bg-gradient-main { background-color: #FFF8FA; }
    </style>
</head>
<body class="bg-gradient-main text-slate-800 font-sans antialiased selection:bg-purple-200">

    <nav class="fixed top-0 left-0 right-0 bg-white/80 backdrop-blur-md shadow-sm z-50 px-6 py-4 transition-all">
        <div class="max-w-7xl mx-auto flex items-center justify-between">
            <div class="flex items-center space-x-2 cursor-pointer" onclick="window.scrollTo(0,0)">
                <div class="w-10 h-10 rounded-full bg-gradient-to-tr from-purple-600 to-pink-500 flex items-center justify-center text-white shadow-md">
                    <i class="fa-solid fa-wand-magic-sparkles text-lg"></i>
                </div>
                <span class="text-xl font-bold tracking-wider text-purple-900" data-zh="逢甲玩樂指南" data-en="Fengjia Fun Guide">逢甲玩樂指南</span>
            </div>

            <div class="hidden md:flex items-center space-x-8 font-medium text-slate-600">
                <a href="#home" class="hover:text-purple-600 transition-colors" data-zh="首頁" data-en="Home">首頁</a>
                <a href="#transport" class="hover:text-purple-600 transition-colors" data-zh="交通路線" data-en="Transport">交通路線</a>
                <a href="#shops" class="hover:text-purple-600 transition-colors" data-zh="店家介紹" data-en="Shops">店家介紹</a>
                <a href="#itinerary" class="hover:text-purple-600 transition-colors" data-zh="主題行程" data-en="Itinerary">主題行程</a>
                <a href="#map" class="hover:text-purple-600 transition-colors" data-zh="導航地圖" data-en="Google Maps">導航地圖</a>
            </div>

            <div class="bg-slate-100 p-1 rounded-full flex items-center space-x-1 text-sm font-semibold shadow-inner">
                <button id="lang-zh" onclick="switchLang('zh')" class="px-3 py-1.5 rounded-full bg-purple-900 text-white shadow-sm transition-all">中</button>
                <button id="lang-en" onclick="switchLang('en')" class="px-3 py-1.5 rounded-full text-slate-600 hover:text-slate-900 transition-all">EN</button>
            </div>
        </div>
    </nav>

    <header id="home" class="pt-32 pb-20 px-6 min-h-[95vh] flex items-center relative overflow-hidden bg-cover bg-right" style="background-image: url('https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=1200&q=80'); background-blend-mode: overlay; background-color: rgba(255, 248, 250, 0.85);">
        <div class="max-w-5xl mx-auto w-full z-10">
            <p class="text-pink-600 font-bold tracking-widest text-sm md:text-base uppercase mb-4" data-zh="FENGJIA · TAICHUNG" data-en="FENGJIA · TAICHUNG">FENGJIA · TAICHUNG</p>
            
            <h1 class="text-5xl md:text-8xl font-black text-purple-950 tracking-tight leading-tight mb-6 drop-shadow-sm">
                <span data-zh="逛吃買拍" data-en="Shop, Eat, Take Photos">逛吃買拍</span><br>
                <span class="text-purple-800" data-zh="一次擁有" data-en="All in One Place">一次擁有</span>
            </h1>
            
            <p class="text-slate-600 text-base md:text-xl max-w-2xl mb-10 leading-relaxed" data-zh="逢甲夜市最完整的吃喝玩樂與交通指南。精心篩選在地老饕私藏攤位、幫你規劃最順路的旅遊行程，輕鬆暢玩逢甲商圈！" data-en="The most comprehensive food, fun, and transport guide for Fengjia Night Market. Carefully selected local hidden gems and customized itineraries just for you.">
                逢甲夜市最完整的吃喝玩樂與交通指南。精心篩選在地老饕私藏攤位、幫你規劃最順路的旅遊行程，輕鬆暢玩逢甲商圈！
            </p>
            
            <div class="flex flex-wrap gap-4">
                <a href="#transport" class="bg-amber-400 hover:bg-amber-500 text-slate-900 font-bold px-8 py-4 rounded-full shadow-lg hover:shadow-xl transform hover:-translate-y-0.5 transition-all flex items-center space-x-2 group">
                    <span data-zh="開始規劃路線" data-en="Plan Your Route">開始規劃路線</span>
                    <i class="fa-solid fa-arrow-right group-hover:translate-x-1 transition-transform"></i>
                </a>
                <a href="#shops" class="bg-white hover:bg-slate-50 text-slate-700 font-semibold px-8 py-4 rounded-full shadow-sm hover:shadow-md transition-all flex items-center justify-center border border-slate-200" data-zh="看店家推薦" data-en="View Recommended Shops">
                    看店家推薦
                </a>
            </div>
        </div>
    </header>

    <section id="transport" class="py-20 px-6 bg-white/60">
        <div class="max-w-7xl mx-auto">
            <span class="text-pink-500 font-bold tracking-widest text-xs uppercase block mb-2">STEP 01</span>
            <h2 class="text-3xl md:text-5xl font-extrabold text-purple-950 mb-4" data-zh="從車站到逢甲商圈" data-en="From Station to Fengjia">從車站到逢甲商圈</h2>
            <p class="text-slate-500 mb-12 text-sm md:text-base" data-zh="選擇你抵達台中的車站，跟著路線一路玩到逢甲。" data-en="Choose your arrival station and follow the route straight to Fengjia.">選擇你抵達台中的車站，跟著路線一路玩到逢甲。</p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-3xl shadow-xl shadow-slate-100/50 border border-slate-100 relative group hover:shadow-2xl transition-all duration-300">
                    <div class="absolute top-6 right-6 w-12 h-12 bg-purple-100 text-purple-700 rounded-full flex items-center justify-center text-lg"><i class="fa-solid fa-train-subway"></i></div>
                    <div class="text-5xl font-black text-pink-100 mb-4 group-hover:text-pink-200 transition-colors">01</div>
                    <h3 class="text-2xl font-bold text-slate-800 mb-1" data-zh="烏日高鐵站" data-en="THSR Taichung Station">烏日高鐵站</h3>
                    <p class="text-sm text-slate-400 mb-6" data-zh="從台北南下最快選擇" data-en="Fastest choice from North or South">從台北南下最快選擇</p>
                    <ul class="space-y-4 text-slate-600 text-sm mb-8">
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">1</span> <span data-zh="出站後轉乘台鐵新烏日站往北" data-en="Transfer to TRA Xinwuri Station northbound">出站後轉乘台鐵新烏日站往北</span></li>
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">2</span> <span data-zh="搭至台中車站或大慶站" data-en="Get off at Taichung or Daqing Station">搭至台中車站或大慶站</span></li>
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">3</span> <span data-zh="轉乘公車 25/35/37 直達逢甲大學" data-en="Take Bus 25/35/37 directly to Fengjia University">轉乘公車 25/35/37 直達逢甲大學</span></li>
                    </ul>
                    <div class="pt-4 border-t border-slate-100 flex items-center justify-between text-xs text-slate-400 font-medium">
                        <span><i class="fa-regular fa-clock mr-1"></i> <span data-zh="約 50 分鐘" data-en="Approx. 50 mins">約 50 分鐘</span></span>
                        <span><i class="fa-solid fa-dollar-sign mr-1"></i> NT$70</span>
                    </div>
                </div>

                <div class="bg-white p-8 rounded-3xl shadow-xl shadow-slate-100/50 border border-slate-100 relative group hover:shadow-2xl transition-all duration-300">
                    <div class="absolute top-6 right-6 w-12 h-12 bg-purple-100 text-purple-700 rounded-full flex items-center justify-center text-lg"><i class="fa-solid fa-train"></i></div>
                    <div class="text-5xl font-black text-pink-100 mb-4 group-hover:text-pink-200 transition-colors">02</div>
                    <h3 class="text-2xl font-bold text-slate-800 mb-1" data-zh="台中火車站" data-en="Taichung Train Station">台中火車站</h3>
                    <p class="text-sm text-slate-400 mb-6" data-zh="火車與客運的轉乘樞紐" data-en="The hub for trains and intercity buses">火車與客運的轉乘樞紐</p>
                    <ul class="space-y-4 text-slate-600 text-sm mb-8">
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">1</span> <span data-zh="出站於建國路公車站" data-en="Go to Jianguo Rd. Bus Station outside">出站於建國路公車站</span></li>
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">2</span> <span data-zh="搭 25/33/35/37/45/73 號公車" data-en="Take Bus 25/33/35/37/45/73">搭 25/33/35/37/45/73 號公車</span></li>
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">3</span> <span data-zh="於「逢甲大學」站下車" data-en="Get off at 'Fengjia University' stop">於「逢甲大學」站下車</span></li>
                    </ul>
                    <div class="pt-4 border-t border-slate-100 flex items-center justify-between text-xs text-slate-400 font-medium">
                        <span><i class="fa-regular fa-clock mr-1"></i> <span data-zh="約 40 分鐘" data-en="Approx. 40 mins">約 40 分鐘</span></span>
                        <span><i class="fa-solid fa-dollar-sign mr-1"></i> NT$30</span>
                    </div>
                </div>

                <div class="bg-white p-8 rounded-3xl shadow-xl shadow-slate-100/50 border border-slate-100 relative group hover:shadow-2xl transition-all duration-300">
                    <div class="absolute top-6 right-6 w-12 h-12 bg-purple-100 text-purple-700 rounded-full flex items-center justify-center text-lg"><i class="fa-solid fa-bus"></i></div>
                    <div class="text-5xl font-black text-pink-100 mb-4 group-hover:text-pink-200 transition-colors">03</div>
                    <h3 class="text-2xl font-bold text-slate-800 mb-1" data-zh="朝馬轉運站" data-en="Chaoma Bus Station">朝馬轉運站</h3>
                    <p class="text-sm text-slate-400 mb-6" data-zh="國道客運最便利的下車點" data-en="Most convenient drop-off for highway coaches">國道客運最便利的下車點</p>
                    <ul class="space-y-4 text-slate-600 text-sm mb-8">
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">1</span> <span data-zh="出站走至河南路口公車站" data-en="Walk to Henan Rd. intersection stop">出站走至河南路口公車站</span></li>
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">2</span> <span data-zh="搭 5/35/37/72/73 號公車" data-en="Take Bus 5/35/37/72/73">搭 5/35/37/72/73 號公車</span></li>
                        <li class="flex items-start space-x-3"><span class="w-5 h-5 rounded-full bg-amber-400 flex items-center justify-center text-xs font-bold text-slate-900 shrink-0">3</span> <span data-zh="5 站後抵達逢甲商圈" data-en="Arrive at Fengjia after 5 stops">5 站後抵達逢甲商圈</span></li>
                    </ul>
                    <div class="pt-4 border-t border-slate-100 flex items-center justify-between text-xs text-slate-400 font-medium">
                        <span><i class="fa-regular fa-clock mr-1"></i> <span data-zh="約 20 分鐘" data-en="Approx. 20 mins">約 20 分鐘</span></span>
                        <span><i class="fa-solid fa-dollar-sign mr-1"></i> NT$25</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="shops" class="py-20 px-6">
        <div class="max-w-7xl mx-auto">
            <span class="text-pink-500 font-bold tracking-widest text-xs uppercase block mb-2">STEP 02</span>
            <h2 class="text-3xl md:text-5xl font-extrabold text-purple-950 mb-4" data-zh="在地老饕推薦" data-en="Local Foodies' Choices">在地老饕推薦</h2>
            <p class="text-slate-500 mb-8 text-sm md:text-base" data-zh="從排隊名店到隱藏小攤，這裡是逢甲必吃必逛清單。" data-en="From famous long-queue stores to hidden gems. Here is your bucket list.">從排隊名店到隱藏小攤，這裡是逢甲必吃必逛清單。</p>

            <div class="flex flex-wrap gap-3 mb-10">
                <button onclick="filterShops('all')" class="shop-tab px-5 py-2 rounded-full bg-purple-950 text-white font-medium text-sm transition-all" data-zh="全部" data-en="All">全部</button>
                <button onclick="filterShops('food')" class="shop-tab px-5 py-2 rounded-full bg-purple-100 text-purple-800 hover:bg-purple-200 font-medium text-sm transition-all flex items-center space-x-1"><i class="fa-solid fa-utensils text-xs"></i> <span data-zh="美食" data-en="Food">美食</span></button>
                <button onclick="filterShops('drink')" class="shop-tab px-5 py-2 rounded-full bg-purple-100 text-purple-800 hover:bg-purple-200 font-medium text-sm transition-all flex items-center space-x-1"><i class="fa-solid fa-mug-hot text-xs"></i> <span data-zh="飲料" data-en="Drinks">飲料</span></button>
                <button onclick="filterShops('shop')" class="shop-tab px-5 py-2 rounded-full bg-purple-100 text-purple-800 hover:bg-purple-200 font-medium text-sm transition-all flex items-center space-x-1"><i class="fa-solid fa-bag-shopping text-xs"></i> <span data-zh="購物" data-en="Shopping">購物</span></button>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="shop-item food bg-gradient-to-br from-amber-500 via-orange-400 to-pink-500 p-8 rounded-3xl text-white shadow-xl flex flex-col justify-between relative min-h-[260px] transition-transform duration-300 hover:-translate-y-1 bg-cover bg-center" style="background-image: linear-gradient(135deg, rgba(245,158,11,0.9), rgba(236,72,153,0.85)), url('https://images.unsplash.com/photo-1565557623262-b51c2513a641?auto=format&fit=crop&w=400&q=80');">
                    <div>
                        <div class="flex justify-between items-start">
                            <span class="bg-white/20 text-white backdrop-blur-md text-xs px-2.5 py-1 rounded-full font-bold" data-zh="夜市創始" data-en="Original Origin">夜市創始</span>
                            <span class="text-4xl font-black opacity-30">01</span>
                        </div>
                        <h3 class="text-2xl font-bold mt-4 mb-2" data-zh="官芝霖大腸包小腸" data-en="Guan Zhi Lin Rice Sausage">官芝霖大腸包小腸</h3>
                        <p class="text-white/80 text-sm" data-zh="酥脆糯米腸夾烤香腸，逢甲第一名物。" data-en="Crispy glutinous rice sausage stuffed with grilled pork sausage.">酥脆糯米腸夾烤香腸，逢甲第一名物。</p>
                    </div>
                    <div class="mt-6 pt-3 border-t border-white/20 flex items-center justify-between text-xs bg-black/20 -mx-8 -mb-8 p-4 rounded-b-3xl">
                        <span class="font-bold flex items-center text-amber-200 animate-pulse"><i class="fa-solid fa-gift mr-1.5"></i><span data-zh="出示此畫面：現折 5 元！" data-en="Show Screen: NT$5 Off!">出示此畫面：現折 5 元！</span></span>
                        <span class="opacity-60" data-zh="美食" data-en="Food">美食</span>
                    </div>
                </div>

                <div class="shop-item food bg-white p-8 rounded-3xl shadow-lg border border-slate-100 flex flex-col justify-between min-h-[260px] transition-transform duration-300 hover:-translate-y-1 bg-cover bg-center" style="background-image: linear-gradient(to bottom, rgba(255,255,255,0.92), rgba(255,255,255,0.96)), url('https://images.unsplash.com/photo-1587314168485-3236d6710814?auto=format&fit=crop&w=400&q=80');">
                    <div>
                        <div class="flex justify-between items-start">
                            <span class="bg-amber-100 text-amber-800 text-xs px-2.5 py-1 rounded-full font-semibold" data-zh="排隊名店" data-en="Famous Queue">排隊名店</span>
                            <span class="text-4xl font-black text-slate-100">02</span>
                        </div>
                        <h3 class="text-2xl font-bold text-slate-800 mt-4 mb-2" data-zh="明倫蛋餅" data-en="Minglun Egg Pancake">明倫蛋餅</h3>
                        <p class="text-slate-500 text-sm" data-zh="Q 彈手工蛋餅，加辣更夠味。" data-en="Chewy handmade egg pancake with optional sweet & spicy sauce.">Q 彈手工蛋餅，加辣更夠味。</p>
                    </div>
                    <div class="mt-6 pt-3 border-t border-slate-100 flex items-center justify-between text-xs -mx-8 -mb-8 p-4 bg-purple-50/60 rounded-b-3xl">
                        <span class="font-bold text-purple-700 flex items-center"><i class="fa-solid fa-gift text-pink-500 mr-1.5 animate-bounce"></i><span data-zh="憑指南：第二份 9 折優惠" data-en="With Guide: 10% Off 2nd Item">憑指南：第二份 9 折優惠</span></span>
                        <span class="text-slate-400" data-zh="美食" data-en="Food">美食</span>
                    </div>
                </div>

                <div class="shop-item food bg-white p-8 rounded-3xl shadow-lg border border-slate-100 flex flex-col justify-between min-h-[260px] transition-transform duration-300 hover:-translate-y-1 bg-cover bg-center" style="background-image: linear-gradient(to bottom, rgba(255,255,255,0.92), rgba(255,255,255,0.96)), url('https://images.unsplash.com/photo-1615228939096-9eaa6cb74ffb?auto=format&fit=crop&w=400&q=80');">
                    <div>
                        <div class="flex justify-between items-start">
                            <span class="bg-slate-100 text-slate-500 text-xs px-2.5 py-1 rounded-full font-semibold" data-zh="經典" data-en="Classic Choice">經典</span>
                            <span class="text-4xl font-black text-slate-100">03</span>
                        </div>
                        <h3 class="text-2xl font-bold text-slate-800 mt-4 mb-2" data-zh="日船章魚小丸子" data-en="Ri Chuan Takoyaki">日船章魚小丸子</h3>
                        <p class="text-slate-500 text-sm" data-zh="外酥內軟，柴魚片香氣四溢。" data-en="Crispy outside, soft inside, topped with dancing bonito flakes.">外酥內軟，柴魚片香氣四溢。</p>
                    </div>
                    <div class="mt-6 pt-3 border-t border-slate-100 flex items-center justify-between text-xs -mx-8 -mb-8 p-4 bg-purple-50/60 rounded-b-3xl">
                        <span class="font-bold text-purple-700 flex items-center"><i class="fa-solid fa-gift text-pink-500 mr-1.5 animate-bounce"></i><span data-zh="特約：買兩盒送飲料一瓶" data-en="Deal: Free drink with 2 boxes">特約：買兩盒送飲料一瓶</span></span>
                        <span class="text-slate-400" data-zh="美食" data-en="Food">美食</span>
                    </div>
                </div>

                <div class="shop-item drink bg-white p-8 rounded-3xl shadow-lg border border-slate-100 flex flex-col justify-between min-h-[260px] transition-transform duration-300 hover:-translate-y-1 bg-cover bg-center" style="background-image: linear-gradient(to bottom, rgba(255,255,255,0.92), rgba(255,255,255,0.96)), url('https://images.unsplash.com/photo-1505394033641-4edc63e38a26?auto=format&fit=crop&w=400&q=80');">
                    <div>
                        <div class="flex justify-between items-start">
                            <span class="bg-blue-50 text-blue-700 text-xs px-2.5 py-1 rounded-full font-semibold" data-zh="老字號" data-en="Time-Honored">老字號</span>
                            <span class="text-4xl font-black text-slate-100">04</span>
                        </div>
                        <h3 class="text-2xl font-bold text-slate-800 mt-4 mb-2" data-zh="幸發亭蜜豆冰" data-en="Xing Fa Ting Shaved Ice">幸發亭蜜豆冰</h3>
                        <p class="text-slate-500 text-sm" data-zh="古早味剉冰，配料豐富夏天必嚐。" data-en="Traditional sweet bean shaved ice, a summer must-have.">古早味剉冰，配料豐富夏天必嚐。</p>
                    </div>
                    <div class="mt-6 pt-3 border-t border-slate-100 flex items-center justify-between text-xs -mx-8 -mb-8 p-4 bg-purple-50/60 rounded-b-3xl">
                        <span class="font-bold text-purple-700 flex items-center"><i class="fa-solid fa-gift text-pink-500 mr-1.5 animate-bounce"></i><span data-zh="消費滿百折 10 元" data-en="Save NT$10 over NT$100">消費滿百折 10 元</span></span>
                        <span class="text-slate-400" data-zh="飲料" data-en="Drinks">飲料</span>
                    </div>
                </div>

                <div class="shop-item drink bg-purple-900 p-8 rounded-3xl text-white shadow-xl flex flex-col justify-between min-h-[260px] transition-transform duration-300 hover:-translate-y-1 bg-cover bg-center" style="background-image: linear-gradient(135deg, rgba(76,29,149,0.9), rgba(107,33,168,0.85)), url('https://images.unsplash.com/photo-1541832676-9b763b0239ab?auto=format&fit=crop&w=400&q=80');">
                    <div>
                        <div class="flex justify-between items-start">
                            <span class="bg-white/20 text-white backdrop-blur-md text-xs px-2.5 py-1 rounded-full font-bold" data-zh="甜品" data-en="Dessert">甜品</span>
                            <span class="text-4xl font-black opacity-20">05</span>
                        </div>
                        <h3 class="text-2xl font-bold mt-4 mb-2" data-zh="三兄弟豆花" data-en="Three Brothers Tofu Pudding">三兄弟豆花</h3>
                        <p class="text-purple-200 text-sm" data-zh="綿密豆花滑嫩順口，傳統配料豐富。" data-en="Silky smooth tofu pudding with premium sweet toppings.">綿密豆花滑嫩順口，傳統配料豐富。</p>
                    </div>
                    <div class="mt-6 pt-3 border-t border-white/20 flex items-center justify-between text-xs bg-black/20 -mx-8 -mb-8 p-4 rounded-b-3xl">
                        <span class="font-bold flex items-center text-amber-300 animate-pulse"><i class="fa-solid fa-gift mr-1.5"></i><span data-zh="免費加料一種（限珍珠/椰果）" data-en="Free extra topping (Tapioca/Jelly)">免費加料一種（限珍珠/椰果）</span></span>
                        <span class="opacity-60" data-zh="飲料" data-en="Drinks">飲料</span>
                    </div>
                </div>

                <div class="shop-item drink bg-gradient-to-br from-purple-700 to-indigo-800 p-8 rounded-3xl text-white shadow-xl flex flex-col justify-between min-h-[260px] transition-transform duration-300 hover:-translate-y-1 bg-cover bg-center" style="background-image: linear-gradient(135deg, rgba(109,40,217,0.9), rgba(30,58,138,0.85)), url('https://images.unsplash.com/photo-1541658016709-82535e94bc69?auto=format&fit=crop&w=400&q=80');">
                    <div>
                        <div class="flex justify-between items-start">
                            <span class="bg-white/20 text-white backdrop-blur-md text-xs px-2.5 py-1 rounded-full font-bold" data-zh="人氣手搖" data-en="Popular Drink">人氣手搖</span>
                            <span class="text-4xl font-black opacity-30">06</span>
                        </div>
                        <h3 class="text-2xl font-bold mt-4 mb-2" data-zh="小芋圓冬瓜鮮奶" data-en="Taro Ball Melon Milk">小芋圓冬瓜鮮奶</h3>
                        <p class="text-purple-100 text-sm" data-zh="古法熬煮冬瓜茶搭配濃厚鮮奶與 Q 彈小芋圓。" data-en="Traditional white gourd tea with rich fresh milk and chewy taro balls.">古法熬煮冬瓜茶搭配濃厚鮮奶與 Q 彈小芋圓。</p>
                    </div>
                    <div class="mt-6 pt-3 border-t border-white/20 flex items-center justify-between text-xs bg-black/20 -mx-8 -mb-8 p-4 rounded-b-3xl">
                        <span class="font-bold flex items-center text-amber-200 animate-pulse"><i class="fa-solid fa-gift mr-1.5"></i><span data-zh="出示此指南：飲品免費升級大杯" data-en="Show Guide: Free Upgrade to Large">出示此指南：飲品免費升級大杯</span></span>
                        <span class="opacity-60" data-zh="飲料" data-en="Drinks">飲料</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="itinerary" class="py-20 px-6 bg-white/40">
        <div class="max-w-5xl mx-auto">
            <span class="text-pink-500 font-bold tracking-widest text-xs uppercase block mb-2">STEP 03</span>
            <h2 class="text-3xl md:text-5xl font-extrabold text-purple-950 mb-4" data-zh="主題行程推薦" data-en="Recommended Itineraries">主題行程推薦</h2>
            <p class="text-slate-500 mb-12 text-sm md:text-base" data-zh="不知道從哪開始？挑一個主題，跟著走就對了。" data-en="Don't know where to start? Just pick a theme and explore.">不知道從哪開始？挑一個主題，跟著走就對了。</p>

            <div class="space-y-12">
                <div class="bg-white rounded-3xl shadow-xl border border-slate-100 flex flex-col md:flex-row overflow-hidden">
                    <div class="md:w-1/3 bg-cover bg-center p-8 md:p-10 text-white flex flex-col justify-between min-h-[200px]" style="background-image: linear-gradient(to bottom, rgba(124,58,237,0.85), rgba(76,29,149,0.95)), url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80');">
                        <div>
                            <span class="bg-amber-400 text-slate-900 text-xs px-2.5 py-1 rounded-full font-bold uppercase" data-zh="美食" data-en="Food Only">美食</span>
                            <h3 class="text-2xl font-bold mt-4 mb-2" data-zh="半日美食衝刺" data-en="Half-Day Food Sprint">半日美食衝刺</h3>
                            <div class="text-purple-200 text-sm flex items-center"><i class="fa-regular fa-clock mr-1.5"></i> <span data-zh="3 小時" data-en="3 Hours">3 小時</span></div>
                        </div>
                        <div class="text-6xl font-black opacity-20 text-right">01</div>
                    </div>
                    <div class="md:w-2/3 p-6 md:p-8 space-y-3 w-full justify-center flex flex-col">
                        <div class="bg-pink-50/40 hover:bg-pink-50 p-4 rounded-xl flex items-center justify-between border border-pink-100/30 transition-colors">
                            <div class="flex items-center space-x-4">
                                <span class="w-7 h-7 rounded-full bg-purple-700 text-white font-bold text-xs flex items-center justify-center">1</span>
                                <span class="font-semibold text-slate-700" data-zh="大腸包小腸開胃" data-en="Appetizer: Rice & Pork Sausage">大腸包小腸開胃</span>
                            </div>
                        </div>
                        <div class="bg-pink-50/40 hover:bg-pink-50 p-4 rounded-xl flex items-center justify-between border border-pink-100/30 transition-colors">
                            <div class="flex items-center space-x-4">
                                <span class="w-7 h-7 rounded-full bg-purple-600 text-white font-bold text-xs flex items-center justify-center">2</span>
                                <span class="font-semibold text-slate-700" data-zh="明倫蛋餅墊肚" data-en="Main: Minglun Egg Pancake">明倫蛋餅墊肚</span>
                            </div>
                        </div>
                        <div class="bg-pink-50/40 hover:bg-pink-50 p-4 rounded-xl flex items-center justify-between border border-pink-100/30 transition-colors">
                            <div class="flex items-center space-x-4">
                                <span class="w-7 h-7 rounded-full bg-purple-500 text-white font-bold text-xs flex items-center justify-center">3</span>
                                <span class="font-semibold text-slate-700" data-zh="章魚小丸子續攤" data-en="Snack: Crispy Takoyaki">章魚小丸子續攤</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="map" class="py-20 px-6 max-w-7xl mx-auto">
        <span class="text-pink-500 font-bold tracking-widest text-xs uppercase block mb-2">STEP 04</span>
        <h2 class="text-3xl md:text-5xl font-extrabold text-purple-950 mb-4" data-zh="互動導航地圖" data-en="Google Maps Navigation">互動導航地圖</h2>
        <p class="text-slate-500 mb-10 text-sm md:text-base" data-zh="一鍵開啟 Google 地圖，隨時查看定位、店家評價並開始導航！" data-en="One click to open Google Maps, check live locations, reviews, and start navigating!">一鍵開啟 Google 地圖，隨時查看定位、店家評價並開始導航！</p>

        <div class="flex flex-col lg:flex-row gap-8 items-stretch">
            <a href="https://www.google.com/maps/d/edit?mid=1lCXSz4zwZ3M_uslm3vek11T7d8I64yU&usp=sharing" target="_blank" 
               class="lg:w-2/3 w-full rounded-3xl overflow-hidden shadow-xl min-h-[400px] bg-gradient-to-tr from-slate-900 via-purple-950 to-slate-900 text-white p-8 flex flex-col justify-between group hover:shadow-2xl transition-all duration-300 relative border border-slate-800">
                
                <div class="absolute inset-0 opacity-10 bg-cover bg-center transition-transform duration-700 group-hover:scale-105" style="background-image: url('https://images.unsplash.com/photo-1524661135-423995f22d0b?auto=format&fit=crop&w=800&q=80');"></div>
                
                <div class="relative z-10">
                    <div class="w-16 h-16 rounded-2xl bg-white/10 backdrop-blur-md flex items-center justify-center text-3xl mb-6 text-amber-400 group-hover:bg-amber-400 group-hover:text-slate-950 transition-all duration-300">
                        <i class="fa-solid fa-map-location-dot"></i>
                    </div>
                    <h3 class="text-3xl md:text-4xl font-black mb-4 tracking-tight">
                        <span data-zh="開啟 Google Maps 專屬地圖" data-en="Open Our Custom Google Maps">開啟 Google Maps 專屬地圖</span>
                    </h3>
                    <p class="text-purple-200 text-base max-w-md leading-relaxed" data-zh="不用擔心網頁載入緩慢！點擊立刻開啟你在 Google Maps 建立的專屬地圖與完美路線。" data-en="No more slow loading! Click to directly open your customized map routes inside Google Maps app or web.">
                        不用擔心網頁載入緩慢！點擊立刻開啟你在 Google Maps 建立的專屬地圖與完美路線。
                    </p>
                </div>
                
                <div class="relative z-10 pt-6 border-t border-white/10 flex items-center justify-between text-amber-400 font-bold group-hover:text-white transition-colors">
                    <span class="text-sm tracking-wider uppercase" data-zh="點擊前往地圖網站 ➔" data-en="Click to Open Map ➔">點擊前往地圖網站 ➔</span>
                    <span class="bg-amber-400 text-slate-900 text-xs px-3 py-1 rounded-full uppercase tracking-widest font-black" data-zh="推薦功能" data-en="LIVE MAP">推薦功能</span>
                </div>
            </a>

            <div class="lg:w-1/3 w-full bg-purple-900 text-white rounded-3xl p-8 flex flex-col justify-between shadow-xl">
                <div>
                    <h3 class="text-2xl font-bold mb-6 tracking-wide">Hotspots</h3>
                    <div class="space-y-4">
                        <div class="bg-white/10 hover:bg-white/15 p-4 rounded-xl flex items-start space-x-3 cursor-pointer transition-all">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                            <div>
                                <h4 class="font-bold text-sm" data-zh="逢甲大學" data-en="Feng Chia University">逢甲大學</h4>
                                <p class="text-xs text-purple-200 mt-0.5" data-zh="商圈中心點" data-en="The center of the business district">商圈中心點</p>
                            </div>
                        </div>
                        <div class="bg-white/10 hover:bg-white/15 p-4 rounded-xl flex items-start space-x-3 cursor-pointer transition-all">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                            <div>
                                <h4 class="font-bold text-sm" data-zh="逢甲夜市" data-en="Fengjia Night Market">逢甲夜市</h4>
                                <p class="text-xs text-purple-200 mt-0.5" data-zh="美食一條街" data-en="Main street full of delicious food">美食一條街</p>
                            </div>
                        </div>
                        <div class="bg-white/10 hover:bg-white/15 p-4 rounded-xl flex items-start space-x-3 cursor-pointer transition-all">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                            <div>
                                <h4 class="font-bold text-sm" data-zh="福星路服飾街" data-en="Fuxing Rd. Fashion Street">福星路服飾街</h4>
                                <p class="text-xs text-purple-200 mt-0.5" data-zh="購物聖地" data-en="The ultimate shopping paradise">購物聖地</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="text-xs text-purple-300 border-t border-white/10 pt-4 mt-6" data-zh="© 2026 逢甲玩樂指南. 保留所有權利." data-en="© 2026 Fengjia Fun Guide. All Rights Reserved.">
                    © 2026 逢甲玩樂指南. 保留所有權利.
                </div>
            </div>
        </div>
    </section>

    <script>
        // 語系切換功能
        function switchLang(lang) {
            const zhBtn = document.getElementById('lang-zh');
            const enBtn = document.getElementById('lang-en');
            
            if (lang === 'zh') {
                zhBtn.className = "px-3 py-1.5 rounded-full bg-purple-900 text-white shadow-sm transition-all";
                enBtn.className = "px-3 py-1.5 rounded-full text-slate-600 hover:text-slate-900 transition-all";
            } else {
                enBtn.className = "px-3 py-1.5 rounded-full bg-purple-900 text-white shadow-sm transition-all";
                zhBtn.className = "px-3 py-1.5 rounded-full text-slate-600 hover:text-slate-900 transition-all";
            }

            const elements = document.querySelectorAll('[data-zh]');
            elements.forEach(el => {
                if (lang === 'zh') {
                    el.textContent = el.getAttribute('data-zh');
                } else {
                    el.textContent = el.getAttribute('data-en');
                }
            });
        }

        // 店家類別篩選功能
        function filterShops(category) {
            const tabs = document.querySelectorAll('.shop-tab');
            tabs.forEach(tab => {
                tab.classList.remove('bg-purple-950', 'text-white');
                tab.classList.add('bg-purple-100', 'text-purple-800');
            });
            event.currentTarget.classList.remove('bg-purple-100', 'text-purple-800');
            event.currentTarget.classList.add('bg-purple-950', 'text-white');

            const items = document.querySelectorAll('.shop-item');
            items.forEach(item => {
                if (category === 'all' || item.classList.contains(category)) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }
    </script>
</body>
</html>
