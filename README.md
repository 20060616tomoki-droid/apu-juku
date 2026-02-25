# apu-juku
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- SEO Meta Tags -->
    <title>Asia Pacific Academy | APU総合型選抜専門塾</title>
    <meta name="description" content="Asia Pacific Academy（APU総合型選抜専門塾）。志望理由書診断や面接対策、APU特化型小論文対策を現役生メンターが徹底サポート。">
    <meta name="keywords" content="APU, 立命館アジア太平洋大学, 総合型選抜, AO入試, 小論文, 対策, 塾, 志望理由書, 面接対策, Asia Pacific Academy">

    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700;900&family=Montserrat:wght@700;900&display=swap');
        
        body { font-family: 'Noto Sans JP', sans-serif; overflow-x: hidden; scroll-behavior: smooth; }
        .font-montserrat { font-family: 'Montserrat', sans-serif; }
        .gradient-primary { background: linear-gradient(135deg, #E61E4D 0%, #C4183C 100%); }
        .text-gradient {
            background: linear-gradient(90deg, #E61E4D, #4F46E5);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .hero-bg {
            background: linear-gradient(rgba(255, 255, 255, 0.85), rgba(255, 255, 255, 0.85)), 
                        url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
        }
        
        .apa-logo-circle {
            width: 48px;
            height: 48px;
            background-color: #E61E4D;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: white;
            font-family: 'Montserrat', sans-serif;
            line-height: 1;
            box-shadow: 0 4px 12px rgba(230, 30, 77, 0.3);
            border: 2px solid white;
        }
        .apa-logo-text-main { font-size: 11px; font-weight: 900; }
        .apa-logo-text-sub { font-size: 6px; font-weight: 700; margin-top: 1px; }

        .insta-style-card {
            border-radius: 24px;
            box-shadow: 0 10px 30px -5px rgba(0,0,0,0.08);
            transition: all 0.3s ease;
        }
        .insta-style-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px -10px rgba(0,0,0,0.12);
        }
        .floating { animation: float 4s ease-in-out infinite; }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }
        
        .line-button-glow {
            animation: pulse-green 2s infinite;
        }
        @keyframes pulse-green {
            0% { box-shadow: 0 0 0 0 rgba(6, 199, 85, 0.7); }
            70% { box-shadow: 0 0 0 15px rgba(6, 199, 85, 0); }
            100% { box-shadow: 0 0 0 0 rgba(6, 199, 85, 0); }
        }

        /* アコーディオン設定 */
        .faq-answer { display: none; }
        .faq-item.active .faq-answer { display: block; }
        .faq-item.active .fa-chevron-down { transform: rotate(180deg); }

        /* ステップライン */
        .step-line::before {
            content: '';
            position: absolute;
            left: 20px;
            top: 0;
            bottom: 0;
            width: 2px;
            background: #E61E4D;
            opacity: 0.2;
        }
        @media (min-width: 768px) {
            .step-line::before { left: 50%; }
        }
    </style>
</head>
<body class="bg-white text-gray-900">

    <!-- Header -->
    <header class="fixed w-full z-50 bg-white/90 backdrop-blur-xl border-b border-gray-100">
        <nav class="container mx-auto px-4 md:px-6 py-2 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <div class="apa-logo-circle">
                    <span class="apa-logo-text-main">APA</span>
                    <span class="apa-logo-text-sub">ACADEMY</span>
                </div>
                <div>
                    <span class="text-lg md:text-xl font-black tracking-tighter block leading-none">APU総合型選抜専門塾</span>
                    <span class="text-[9px] font-bold text-gray-400 uppercase tracking-widest">Asia Pacific Academy</span>
                </div>
            </div>
            <div class="hidden lg:flex space-x-8 font-bold text-sm items-center">
                <a href="#about" class="hover:text-[#E61E4D] transition">選ばれる理由</a>
                <a href="#roadmap" class="hover:text-[#E61E4D] transition">合格までの道</a>
                <a href="#price" class="hover:text-[#E61E4D] transition">料金案内</a>
                <a href="#faq" class="hover:text-[#E61E4D] transition">よくある質問</a>
                <a href="https://lin.ee/ehaZU4R" target="_blank" class="bg-[#06C755] text-white px-6 py-2.5 rounded-full shadow-md hover:shadow-lg transition flex items-center">
                    <i class="fab fa-line mr-2"></i> LINEで相談
                </a>
            </div>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero-bg min-h-screen flex items-center pt-24 md:pt-20">
            <div class="container mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-8">
                    <div class="inline-block bg-red-50 text-[#E61E4D] px-4 py-1.5 rounded-full text-xs md:text-sm font-black tracking-wider border border-red-100">
                        直近2年で50人の合格書類を保有
                    </div>
                    <h1 class="text-3xl md:text-5xl lg:text-6xl font-black leading-[1.2] tracking-tight text-gray-900">
                        <span class="text-gradient">APUを知り尽くした</span><br>
                        現役生による徹底指導。<br>
                        <span class="text-xl md:text-2xl lg:text-3xl block mt-6 text-gray-700 font-bold leading-snug">
                            書類・面接・小論文を網羅。<br>講師全員が現役のAPU生です。
                        </span>
                    </h1>
                    <div class="flex flex-wrap gap-4 pt-4">
                        <a href="https://lin.ee/ehaZU4R" target="_blank" class="bg-[#06C755] text-white px-8 py-4 rounded-2xl font-black text-lg shadow-xl hover:scale-105 transition-transform flex items-center line-button-glow">
                            <i class="fab fa-line text-2xl mr-3"></i> LINEで無料面談を予約
                        </a>
                        <a href="https://www.instagram.com/apa_juku?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" class="bg-white text-gray-900 border-2 border-gray-100 px-8 py-4 rounded-2xl font-black text-lg hover:bg-gray-50 transition flex items-center">
                            <i class="fab fa-instagram mr-2 text-[#E1306C]"></i> Instagram
                        </a>
                    </div>
                </div>
                <div class="relative hidden md:block">
                    <div class="relative z-10 floating">
                        <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?auto=format&fit=crop&w=800&q=80" alt="APUキャンパスライフ" class="rounded-[40px] shadow-2xl border-[12px] border-white">
                    </div>
                </div>
            </div>
        </section>

        <!-- Why Us -->
        <section id="about" class="py-24 bg-white overflow-hidden">
            <div class="container mx-auto px-6">
                <div class="text-center mb-20">
                    <h2 class="text-sm font-black text-[#E61E4D] tracking-[0.3em] uppercase mb-4">Core Strengths</h2>
                    <p class="text-4xl md:text-5xl font-black tracking-tighter">なぜAsia Pacific Academyなのか</p>
                </div>
                <div class="grid md:grid-cols-3 gap-8 text-center">
                    <div class="p-8 insta-style-card">
                        <div class="w-20 h-20 bg-red-50 text-[#E61E4D] rounded-3xl flex items-center justify-center text-3xl mx-auto mb-6">
                            <i class="fas fa-bolt"></i>
                        </div>
                        <h3 class="text-xl font-black mb-4">24時間以内の爆速返信</h3>
                        <p class="text-gray-500 text-sm font-bold leading-relaxed">不安な受験期、質問を放置しません。現役生の柔軟さを活かし、24時間以内に回答してあなたの学習リズムを守ります。</p>
                    </div>
                    <div class="p-8 insta-style-card">
                        <div class="w-20 h-20 bg-blue-50 text-blue-600 rounded-3xl flex items-center justify-center text-3xl mx-auto mb-6">
                            <i class="fas fa-door-open"></i>
                        </div>
                        <h3 class="text-xl font-black mb-4">オンライン自習室の開放</h3>
                        <p class="text-gray-500 text-sm font-bold leading-relaxed">一人じゃないから頑張れる。現役APU生も参加する自習室を多数開放し、受験直前まで高いモチベーションを維持します。</p>
                    </div>
                    <div class="p-8 insta-style-card">
                        <div class="w-20 h-20 bg-green-50 text-green-600 rounded-3xl flex items-center justify-center text-3xl mx-auto mb-6">
                            <i class="fas fa-hand-holding-heart"></i>
                        </div>
                        <h3 class="text-xl font-black mb-4">合格後も続く手厚い支援</h3>
                        <p class="text-gray-500 text-sm font-bold leading-relaxed">合格は通過点。別府での家探しや大学の履修、アルバイト事情まで、入学後すぐに馴染めるよう先輩が徹底サポート。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Roadmap Section -->
        <section id="roadmap" class="py-24 bg-gray-50">
            <div class="container mx-auto px-6">
                <div class="text-center mb-20">
                    <h2 class="text-sm font-black text-[#E61E4D] tracking-[0.3em] uppercase mb-4">Success Roadmap</h2>
                    <p class="text-4xl md:text-5xl font-black tracking-tighter">合格までの道のり</p>
                </div>

                <div class="relative step-line max-w-5xl mx-auto">
                    <!-- Step 1 -->
                    <div class="mb-12 md:mb-20 flex flex-col md:flex-row items-center">
                        <div class="md:w-1/2 md:pr-12 md:text-right mb-6 md:mb-0">
                            <span class="inline-block bg-[#E61E4D] text-white px-4 py-1 rounded-full text-xs font-black mb-3">STEP 01</span>
                            <h3 class="text-2xl font-black mb-4">無料カウンセリング</h3>
                            <p class="text-gray-500 text-sm font-bold leading-relaxed">まずはLINEから現状をお聞かせください。志望学部や現在の活動実績を伺い、あなただけの対策プランを提示します。</p>
                        </div>
                        <div class="relative z-10 w-10 h-10 bg-[#E61E4D] rounded-full border-4 border-white shadow-lg hidden md:block"></div>
                        <div class="md:w-1/2 md:pl-12"></div>
                    </div>

                    <!-- Step 2 -->
                    <div class="mb-12 md:mb-20 flex flex-col md:flex-row items-center">
                        <div class="md:w-1/2 md:pr-12"></div>
                        <div class="relative z-10 w-10 h-10 bg-[#E61E4D] rounded-full border-4 border-white shadow-lg hidden md:block"></div>
                        <div class="md:w-1/2 md:pl-12">
                            <span class="inline-block bg-[#E61E4D] text-white px-4 py-1 rounded-full text-xs font-black mb-3">STEP 02</span>
                            <h3 class="text-2xl font-black mb-4">書類作成 & 小論文特化カリキュラム</h3>
                            <p class="text-gray-500 text-sm font-bold leading-relaxed">
                                保有する50名の合格書類データを基に書類を練り上げます。
                                <span class="text-[#E61E4D] block mt-2">※小論文が必要な方式の場合は、APUの独自テストに特化した専用カリキュラムで小論文対策も並行して進めます。</span>
                            </p>
                        </div>
                    </div>

                    <!-- Step 3 -->
                    <div class="mb-12 md:mb-20 flex flex-col md:flex-row items-center">
                        <div class="md:w-1/2 md:pr-12 md:text-right mb-6 md:mb-0">
                            <span class="inline-block bg-[#E61E4D] text-white px-4 py-1 rounded-full text-xs font-black mb-3">STEP 03</span>
                            <h3 class="text-2xl font-black mb-4">徹底模擬面接</h3>
                            <p class="text-gray-500 text-sm font-bold leading-relaxed">APU特有の「鋭い質問」に備え、現役生メンターが納得いくまで模擬面接を実施。オンラインでも伝わる表現力を磨きます。</p>
                        </div>
                        <div class="relative z-10 w-10 h-10 bg-[#E61E4D] rounded-full border-4 border-white shadow-lg hidden md:block"></div>
                        <div class="md:w-1/2 md:pl-12"></div>
                    </div>

                    <!-- Step 4 -->
                    <div class="flex flex-col md:flex-row items-center">
                        <div class="md:w-1/2 md:pr-12"></div>
                        <div class="relative z-10 w-12 h-12 bg-yellow-400 rounded-full border-4 border-white shadow-lg flex items-center justify-center text-white hidden md:flex">
                            <i class="fas fa-crown"></i>
                        </div>
                        <div class="md:w-1/2 md:pl-12">
                            <span class="inline-block bg-yellow-400 text-white px-4 py-1 rounded-full text-xs font-black mb-3">GOAL & BEYOND</span>
                            <h3 class="text-2xl font-black mb-4">合格・入学後サポート</h3>
                            <p class="text-gray-500 text-sm font-bold leading-relaxed">合格通知を受け取った後も、家探し、履修登録、そして別府での生活基盤ができるまで、先輩として並走し続けます。</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Price Section -->
        <section id="price" class="py-24 bg-white">
            <div class="container mx-auto px-6 max-w-4xl text-center">
                <h2 class="text-sm font-black text-[#E61E4D] tracking-[0.3em] uppercase mb-4">Fee Structure</h2>
                <p class="text-4xl font-black tracking-tighter mb-16">明瞭な料金体系</p>
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="p-10 bg-gray-50 rounded-[40px] shadow-sm border-2 border-transparent hover:border-[#E61E4D] transition">
                        <p class="text-sm font-black text-gray-400 mb-4">初回のみ</p>
                        <h4 class="text-2xl font-black mb-4">入塾料</h4>
                        <p class="text-4xl font-black text-[#E61E4D]">¥30,000</p>
                        <p class="mt-4 text-xs text-gray-400 font-bold">システム登録・個別カリキュラム作成込</p>
                    </div>
                    <div class="p-10 bg-gray-50 rounded-[40px] shadow-sm border-2 border-transparent hover:border-[#E61E4D] transition">
                        <p class="text-sm font-black text-gray-400 mb-4">都度払い</p>
                        <h4 class="text-2xl font-black mb-4">個別授業料（1回）</h4>
                        <p class="text-4xl font-black text-[#E61E4D]">¥6,000</p>
                        <p class="mt-4 text-xs text-gray-400 font-bold">1対1のマンツーマン指導（オンライン）</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- FAQ Section -->
        <section id="faq" class="py-24 bg-gray-50">
            <div class="container mx-auto px-6 max-w-3xl">
                <div class="text-center mb-16">
                    <h2 class="text-sm font-black text-[#E61E4D] tracking-[0.3em] uppercase mb-4">Questions</h2>
                    <p class="text-4xl font-black tracking-tighter">よくある質問</p>
                </div>
                <div class="space-y-4">
                    <div class="faq-item bg-white p-6 rounded-2xl cursor-pointer border border-transparent hover:border-red-100 transition" onclick="this.classList.toggle('active')">
                        <div class="flex justify-between items-center font-black">
                            <span>小論文が必要な入試方式なのですが、対応していますか？</span>
                            <i class="fas fa-chevron-down text-gray-300"></i>
                        </div>
                        <p class="faq-answer mt-4 text-sm text-gray-600 font-bold leading-relaxed">
                            はい、もちろん対応しています。APUの独自テストで課される小論文には独特の傾向があります。当塾ではAPUのテスト対策専用のカリキュラムをご用意しており、論理構成から頻出テーマの対策まで徹底的に進めていきます。
                        </p>
                    </div>
                    <div class="faq-item bg-white p-6 rounded-2xl cursor-pointer border border-transparent hover:border-red-100 transition" onclick="this.classList.toggle('active')">
                        <div class="flex justify-between items-center font-black">
                            <span>「24時間以内の返信」とは、どんな内容でも可能ですか？</span>
                            <i class="fas fa-chevron-down text-gray-300"></i>
                        </div>
                        <p class="faq-answer mt-4 text-sm text-gray-600 font-bold leading-relaxed">
                            はい。志望理由書の細かな表現の相談から、受験に対する不安な気持ちの相談まで、メンターが責任を持って24時間以内にレスポンスします。
                        </p>
                    </div>
                    <div class="faq-item bg-white p-6 rounded-2xl cursor-pointer border border-transparent hover:border-red-100 transition" onclick="this.classList.toggle('active')">
                        <div class="flex justify-between items-center font-black">
                            <span>合格後のサポートは具体的に何をしてもらえますか？</span>
                            <i class="fas fa-chevron-down text-gray-300"></i>
                        </div>
                        <p class="faq-answer mt-4 text-sm text-gray-600 font-bold leading-relaxed">
                            別府での一人暮らしを始めるための家探しアドバイス、APハウスのリアルな実態、入学までに準備すべき学習、そして入学後の履修登録のコツなど、APU生ならではの情報をすべてお伝えします。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Final CTA -->
        <section id="contact" class="py-24 gradient-primary text-white">
            <div class="container mx-auto px-6 text-center max-w-2xl">
                <h2 class="text-4xl md:text-5xl font-black tracking-tighter mb-8 leading-tight">まずはLINEで<br>無料相談から</h2>
                <div class="bg-white p-10 md:p-14 rounded-[40px] text-gray-900 shadow-2xl">
                    <div class="space-y-8">
                        <div class="flex justify-center">
                            <div class="apa-logo-circle scale-150">
                                <span class="apa-logo-text-main">APA</span>
                                <span class="apa-logo-text-sub">ACADEMY</span>
                            </div>
                        </div>
                        <a href="https://lin.ee/ehaZU4R" target="_blank" class="flex items-center justify-center w-full bg-[#06C755] text-white py-6 rounded-2xl font-black text-2xl shadow-lg hover:shadow-2xl transition-transform hover:scale-[1.03] line-button-glow">
                            <i class="fab fa-line text-3xl mr-3"></i> LINEで相談を開始する
                        </a>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-white py-20 border-t border-gray-100">
        <div class="container mx-auto px-6 flex flex-col items-center text-center">
            <div class="flex items-center space-x-3 mb-8">
                <div class="apa-logo-circle">
                    <span class="apa-logo-text-main">APA</span>
                    <span class="apa-logo-text-sub">ACADEMY</span>
                </div>
                <div class="text-left">
                    <span class="text-2xl font-black tracking-tighter block leading-none">APU総合型選抜専門塾</span>
                    <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">Asia Pacific Academy</span>
                </div>
            </div>
            <p class="text-gray-400 font-bold text-xs">&copy; 2024 Asia Pacific Academy. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
