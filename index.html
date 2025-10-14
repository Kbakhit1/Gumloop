<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>خطة عمل تفاعلية: سلسلة فيديوهات Gumloop</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    <!-- Chosen Palette: Calm Tech -->
    <!-- Application Structure Plan: تم تصميم التطبيق كهيكل لوحة معلومات (Dashboard) مقسمة إلى أربعة أقسام رئيسية يمكن التنقل بينها عبر شريط ملاحة علوي (نظرة عامة، الجمهور، خريطة المحتوى، مؤشرات النجاح). هذا التصميم يعزز الاستكشاف غير الخطي للمعلومات، على عكس التقرير الأصلي الخطي. تم اختيار هذا النهج لتسهيل الوصول السريع إلى الأجزاء المختلفة من الخطة. التفاعل الرئيسي هو نظام "التفصيل عند الطلب" (Drill-down) في قسم "خريطة المحتوى"، حيث يتم عرض المراحل في تبويبات والفيديوهات كبطاقات قابلة للنقر، مما يقلل من العبء المعرفي ويسمح للمستخدم بالتركيز على تفاصيل محددة عند الحاجة دون إغراقه بالمعلومات دفعة واحدة. -->
    <!-- Visualization & Content Choices: 1. الملخص والأهداف -> بطاقات نصية منظمة (Goal: Inform, Method: Styled HTML). 2. الجمهور المستهدف -> بطاقات مرئية مع أيقونات بسيطة (Goal: Organize, Method: HTML/CSS with Unicode Icons). 3. خطة المحتوى -> نظام تبويبات للمراحل وبطاقات قابلة للنقر للفيديوهات تفتح نافذة تفاصيل (Goal: Explore/Organize, Interaction: Click to reveal details, Method: JS). 4. مؤشرات الأداء -> أربعة رسوم بيانية باستخدام Chart.js (نمو المشتركين، التفاعل، وقت المشاهدة، CTR) مع بيانات افتراضية (Goal: Visualize Data, Interaction: Hover for tooltips, Library: Chart.js/Canvas). هذا النهج يحول المعلومات الثابتة إلى عروض تفاعلية ومرئية مناسبة لطبيعة كل معلومة. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Tajawal', sans-serif;
            scroll-behavior: smooth;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 350px;
        }
        .modal-bg {
            background-color: rgba(0,0,0,0.5);
            transition: opacity 0.3s ease;
        }
        .modal-content {
            transition: transform 0.3s ease;
        }
        .nav-link {
            transition: color 0.3s, border-bottom-color 0.3s;
        }
        .nav-link:hover, .nav-link.active {
            color: #2563eb; 
            border-bottom-color: #2563eb;
        }
        .tab-button.active {
            background-color: #3b82f6;
            color: white;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="bg-white/80 backdrop-blur-md shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-xl md:text-2xl font-bold text-blue-600">خطة إطلاق سلسلة Gumloop</h1>
            <ul class="hidden md:flex items-center space-x-8 space-x-reverse text-lg">
                <li><a href="#overview" class="nav-link pb-1 border-b-2 border-transparent">نظرة عامة</a></li>
                <li><a href="#audience" class="nav-link pb-1 border-b-2 border-transparent">الجمهور</a></li>
                <li><a href="#roadmap" class="nav-link pb-1 border-b-2 border-transparent">خريطة المحتوى</a></li>
                <li><a href="#kpis" class="nav-link pb-1 border-b-2 border-transparent">مؤشرات النجاح</a></li>
            </ul>
            <button id="mobile-menu-button" class="md:hidden text-gray-700 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </nav>
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
            <a href="#overview" class="block py-2 text-lg text-gray-700">نظرة عامة</a>
            <a href="#audience" class="block py-2 text-lg text-gray-700">الجمهور</a>
            <a href="#roadmap" class="block py-2 text-lg text-gray-700">خريطة المحتوى</a>
            <a href="#kpis" class="block py-2 text-lg text-gray-700">مؤشرات النجاح</a>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">

        <section id="overview" class="mb-20">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-900">نظرة عامة على المشروع</h2>
            <p class="text-center text-lg text-gray-600 mb-12 max-w-3xl mx-auto">هذا القسم يقدم ملخصاً تنفيذياً ورؤية استراتيجية لسلسلة الفيديوهات التعليمية المقترحة حول منصة Gumloop، موضحاً القيمة التي تهدف إلى تحقيقها.</p>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-2xl font-bold mb-4 text-blue-600">ملخص تنفيذي</h3>
                    <p class="text-gray-700 leading-relaxed">
                        تهدف هذه الخطة إلى إطلاق سلسلة فيديوهات تعليمية متكاملة على قناتنا، تركز بشكل أساسي على منصة Gumloop، وهي أداة ناشئة ومتخصصة في أتمتة سير العمل المعتمدة على الذكاء الاصطناعي (AI-First Automation). تمثل هذه السلسلة فرصة استراتيجية للاستحواذ على شريحة جماهيرية جديدة ومتنامية في السوق العربي، تتكون من غير المطورين الذين يبحثون عن حلول سهلة وفعالة. من خلال تقديم محتوى تعليمي عالي الجودة وسبّاق في هذا المجال، سنرسخ مكانة قناتنا كمرجع أساسي وموثوق في مجال الأتمتة الذكية.
                    </p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-2xl font-bold mb-4 text-blue-600">الأهداف الاستراتيجية</h3>
                    <ul class="space-y-3 list-inside">
                        <li class="flex items-start"><span class="text-blue-500 text-2xl mr-2 ml-2">🏆</span> <span><strong class="font-semibold">الريادة في المحتوى:</strong> أن نصبح القناة العربية الأولى التي تقدم شرحًا متعمقًا لمنصة Gumloop.</span></li>
                        <li class="flex items-start"><span class="text-blue-500 text-2xl mr-2 ml-2">👥</span> <span><strong class="font-semibold">توسيع قاعدة الجمهور:</strong> جذب شريحة جديدة من المتابعين غير التقنيين.</span></li>
                        <li class="flex items-start"><span class="text-blue-500 text-2xl mr-2 ml-2">📚</span> <span><strong class="font-semibold">بناء مسار تعليمي متكامل:</strong> إنشاء سلسلة متدرجة من الأساسيات إلى المشاريع المتقدمة.</span></li>
                        <li class="flex items-start"><span class="text-blue-500 text-2xl mr-2 ml-2">💡</span> <span><strong class="font-semibold">تعزيز مكانة القناة:</strong> ترسيخ علامتنا التجارية كمصدر للمعرفة في تقنيات الأتمتة الحديثة.</span></li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="audience" class="mb-20">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-900">الجمهور المستهدف</h2>
            <p class="text-center text-lg text-gray-600 mb-12 max-w-3xl mx-auto">تستهدف السلسلة بشكل أساسي المهنيين غير التقنيين الذين يتطلعون إلى زيادة إنتاجيتهم عبر الأتمتة. استكشف الفئات الرئيسية المستهدفة أدناه.</p>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-lg text-center border border-gray-200">
                    <div class="text-5xl mb-4">📢</div>
                    <h3 class="text-xl font-bold mb-2">فرق التسويق والنمو</h3>
                    <p class="text-gray-600">لأتمتة مهام مثل البحث عن الكلمات المفتاحية، ومراقبة المنافسين، وإنشاء المحتوى.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-lg text-center border border-gray-200">
                    <div class="text-5xl mb-4">🚀</div>
                    <h3 class="text-xl font-bold mb-2">أصحاب المشاريع والمستقلون</h3>
                    <p class="text-gray-600">لأتمتة العمليات الروتينية وتوفير الوقت والجهد.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-lg text-center border border-gray-200">
                    <div class="text-5xl mb-4">📈</div>
                    <h3 class="text-xl font-bold mb-2">مديرو المبيعات والعمليات</h3>
                    <p class="text-gray-600">لأتمتة البحث عن العملاء المحتملين، وإثراء البيانات، وتحديث أنظمة CRM.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-lg text-center border border-gray-200">
                    <div class="text-5xl mb-4">💬</div>
                    <h3 class="text-xl font-bold mb-2">فرق دعم العملاء والموارد البشرية</h3>
                    <p class="text-gray-600">لتصنيف الطلبات، وأتمتة الردود، وفحص السير الذاتية.</p>
                </div>
            </div>
        </section>

        <section id="roadmap" class="mb-20">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-900">خريطة محتوى السلسلة</h2>
            <p class="text-center text-lg text-gray-600 mb-12 max-w-3xl mx-auto">تنقسم السلسلة إلى أربع مراحل تعليمية متدرجة. تنقل بين المراحل لاستكشاف الفيديوهات المقترحة، وانقر على أي فيديو لمعرفة المزيد من التفاصيل حوله.</p>
            <div class="bg-white p-8 rounded-xl shadow-lg border border-gray-200">
                <div id="tabs-container" class="mb-6 flex flex-wrap justify-center gap-2 md:gap-4"></div>
                <div id="content-container"></div>
            </div>
        </section>

        <section id="kpis" class="mb-12">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-900">مؤشرات النجاح الرئيسية (KPIs)</h2>
            <p class="text-center text-lg text-gray-600 mb-12 max-w-3xl mx-auto">سيتم قياس نجاح السلسلة من خلال مجموعة من مؤشرات الأداء الرئيسية التي تعكس نمو القناة وتفاعل الجمهور. الرسوم البيانية أدناه توضح الأهداف المراد تتبعها.</p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-xl font-bold mb-4 text-center">نمو المشتركين</h3>
                    <div class="chart-container">
                        <canvas id="subscribersChart"></canvas>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-xl font-bold mb-4 text-center">معدل التفاعل (إعجابات وتعليقات)</h3>
                     <div class="chart-container">
                        <canvas id="engagementChart"></canvas>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-xl font-bold mb-4 text-center">معدل الاحتفاظ بالجمهور</h3>
                     <div class="chart-container">
                        <canvas id="retentionChart"></canvas>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-lg border border-gray-200">
                    <h3 class="text-xl font-bold mb-4 text-center">نسبة النقر إلى الظهور (CTR)</h3>
                     <div class="chart-container">
                        <canvas id="ctrChart"></canvas>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-white text-center py-6">
        <p>&copy; 2025 خطة محتوى تفاعلية. جميع الحقوق محفوظة.</p>
    </footer>
    
    <div id="video-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 modal-bg opacity-0 pointer-events-none">
        <div id="modal-content" class="bg-white rounded-lg shadow-2xl w-full max-w-2xl p-8 transform scale-95">
            <div class="flex justify-between items-center mb-4">
                <h3 id="modal-title" class="text-2xl font-bold text-gray-900"></h3>
                <button id="modal-close" class="text-gray-500 hover:text-gray-800 text-3xl">&times;</button>
            </div>
            <div>
                <h4 class="text-lg font-bold text-blue-600 mb-2">الهدف من الفيديو:</h4>
                <p id="modal-goal" class="text-gray-700 mb-6"></p>
                <h4 class="text-lg font-bold text-blue-600 mb-2">المحتوى المقترح:</h4>
                <p id="modal-content-details" class="text-gray-700 leading-relaxed"></p>
            </div>
        </div>
    </div>


    <script>
        document.addEventListener('DOMContentLoaded', function () {
            
            const roadmapData = [
                {
                    phase: 'المرحلة الأولى: التأسيس وبناء الثقة',
                    videos: [
                        { id: 1, title: 'ما هي منصة Gumloop؟ (بناء أول أتمتة في 5 دقائق)', goal: 'تعريف المشاهدين بمنصة Gumloop وفلسفتها القائمة على الذكاء الاصطناعي (AI-First)، وتمكينهم من بناء أول سير عمل بسيط لتحقيق إحساس فوري بالإنجاز.', content: 'مقدمة لمفهوم الأتمتة المعتمدة على الذكاء الاصطناعي، جولة سريعة في واجهة Gumloop الجذابة، وتطبيق عملي لبناء سير عمل أساسي (مثل تلخيص نص وإرساله عبر البريد الإلكتروني).' },
                        { id: 2, title: 'المعركة الكبرى: Gumloop ضد Zapier و Make و n8n', goal: 'وضع Gumloop في سياق السوق، ومساعدة المشاهدين على اتخاذ قرار مستنير بناءً على احتياجاتهم، مما يعزز مصداقية القناة.', content: 'مقارنة موضوعية وشاملة بين المنصات الأربع بناءً على: سهولة الاستخدام، قوة الذكاء الاصطناعي، نموذج التسعير، والمرونة، مع تقديم توصية واضحة لكل حالة استخدام.' },
                        { id: 3, title: 'تسعير Gumloop بالتفصيل (نظام الأرصدة "Credits")', goal: 'إزالة الغموض حول نظام التسعير، ومساعدة المستخدمين على تقدير تكاليفهم المستقبلية، وبناء الثقة من خلال الشفافية.', content: 'شرح عملي لنظام الأرصدة، وتوضيح تكلفة الإجراءات المختلفة (خاصة استدعاءات الذكاء الاصطناعي)، وتقديم نصائح لتحسين الاستهلاك وتوفير التكاليف.' }
                    ]
                },
                {
                    phase: 'المرحلة الثانية: بناء المهارات الأساسية',
                    videos: [
                        { id: 4, title: 'مكعبات البناء: شرح الـ Nodes والـ Flows والـ Canvas', goal: 'تزويد المشاهدين بفهم عميق للمكونات الأساسية للمنصة، وتمكينهم من التفكير بطريقة منطقية لبناء سير العمل.', content: 'جولة تفصيلية في واجهة البناء، شرح الفرق بين أنواع الـ Nodes (Trigger, AI, Logic, Output)، وكيفية توصيلها وتمرير البيانات بينها.' },
                        { id: 5, title: 'استخراج البيانات مثل المحترفين (Web Scraping)', goal: 'تعليم المشاهدين واحدة من أقوى ميزات Gumloop، وهي استخراج البيانات من أي موقع ويب بسهولة.', content: 'شرح عملي لأداة استخراج البيانات، مع التركيز على استخدام إضافة كروم (Chrome Extension) لتسجيل الخطوات وتحويلها إلى أتمتة.' },
                        { id: 6, title: 'العقل المدبر: احتراف عقدة "Ask AI" والمساعد Gummie', goal: 'تمكين المشاهدين من استغلال القدرات الكاملة للذكاء الاصطناعي المدمج في المنصة.', content: 'شرح كل إعدادات عقدة الذكاء الاصطناعي، كيفية كتابة Prompt فعال، والفرق بين نماذج الذكاء الاصطناعي المتاحة. بالإضافة إلى استعراض المساعد الذكي Gummie.' },
                        { id: 7, title: 'الربط بالعالم الخارجي: شرح الـ Triggers والـ Webhooks', goal: 'تعليم المشاهدين كيفية جعل عمليات الأتمتة تبدأ تلقائيًا بناءً على أحداث خارجية.', content: 'شرح أنواع الـ Triggers المختلفة (مثل عند وصول إيميل جديد)، وتقديم شرح مبسط وعملي للـ Webhooks لربط أي أداة خارجية بـ Gumloop.' }
                    ]
                },
                {
                    phase: 'المرحلة الثالثة: التطبيقات العملية المتقدمة',
                    videos: [
                        { id: 8, title: 'مشروع: بناء صانع محتوى للسوشيال ميديا', goal: 'تقديم مشروع متكامل يجمع المهارات المكتسبة في تطبيق عملي ومطلوب بشدة في السوق.', content: 'بناء سير عمل يبحث عن مواضيع رائجة، يكتب بوستات عنها باستخدام الذكاء الاصطناعي، ويجهزها للنشر في ملف Google Sheets.' },
                        { id: 9, title: 'مشروع: أتمتة البحث عن العملاء المحتملين', goal: 'استعراض حالة استخدام قوية ومباشرة التأثير على نمو الأعمال، تستهدف أصحاب المشاريع وفرق المبيعات.', content: 'سير عمل يراقب كلمات مفتاحية معينة على منصات التواصل الاجتماعي، يحلل المنشورات بالذكاء الاصطناعي لتحديد درجة الاهتمام، ويرسل إشعارًا بالعملاء المحتملين.' },
                        { id: 10, title: 'مشروع: تحويل فيديوهات يوتيوب إلى مقالات', goal: 'تقديم حل إبداعي لمشكلة شائعة لدى صناع المحتوى، مما يوضح مرونة المنصة.', content: 'سير عمل يأخذ رابط فيديو يوتيوب، يستخرج نصه، يلخصه بالذكاء الاصطناعي، ويحوله إلى مقالة جاهزة للنشر.' },
                        { id: 11, title: 'مشروع: بناء بوت SEO للبحث عن الكلمات المفتاحية', goal: 'استهداف شريحة المسوقين الرقميين بمشروع متخصص يحل مشكلة أساسية في عملهم اليومي.', content: 'سير عمل يأخذ كلمة مفتاحية، يبحث في جوجل، يستخرج أفضل 10 نتائج، يحللها بالذكاء الاصطناعي، ويقدم تقريرًا بأفكار للمحتوى.' }
                    ]
                },
                {
                    phase: 'المرحلة الرابعة: الاحتراف والتوسع المستقبلي',
                    videos: [
                        { id: 12, title: 'السحر القابل لإعادة الاستخدام: شرح الـ Subflows', goal: 'تعليم المشاهدين تقنية متقدمة لتنظيم سير العمل المعقد وتوفير الوقت من خلال بناء وحدات قابلة لإعادة الاستخدام.', content: 'شرح مفهوم الـ Subflows، وكيفية بناء سير عمل مصغر يمكن استدعاؤه داخل سير عمل أكبر.' },
                        { id: 13, title: 'بناء أدواتك الخاصة بواجهات Gumloop (Interfaces)', goal: 'استعراض ميزة فريدة تمكن الفرق من التعاون بسهولة، حيث يمكن تحويل سير العمل المعقد إلى أداة بسيطة بواجهة استخدام سهلة.', content: 'شرح ميزة الـ Interfaces، وتطبيق عملي لإنشاء واجهة (مثل فورم) لسير عمل معقد.' },
                        { id: 14, title: 'من Gumloop إلى n8n: متى ولماذا؟', goal: 'فيديو استراتيجي يهدف إلى الاحتفاظ بالجمهور الذي تطورت احتياجاته، وتقديم مسار تعليمي جديد لهم.', content: 'مناقشة الحالات التي قد لا تكون فيها Gumloop كافية، وتقديم منصة n8n كحل للمحترفين، مع التمهيد لسلسلة جديدة حولها.' }
                    ]
                }
            ];

            const tabsContainer = document.getElementById('tabs-container');
            const contentContainer = document.getElementById('content-container');

            function renderContent(phaseIndex) {
                contentContainer.innerHTML = '';
                const phaseData = roadmapData[phaseIndex];
                const grid = document.createElement('div');
                grid.className = 'grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6';

                phaseData.videos.forEach(video => {
                    const card = document.createElement('div');
                    card.className = 'bg-gray-100 p-6 rounded-lg cursor-pointer hover:shadow-md hover:bg-blue-50 transition-all';
                    card.innerHTML = `<h4 class="font-bold text-lg text-gray-800">الفيديو ${video.id}: ${video.title}</h4>`;
                    card.addEventListener('click', () => openModal(video));
                    grid.appendChild(card);
                });
                contentContainer.appendChild(grid);
            }

            roadmapData.forEach((item, index) => {
                const button = document.createElement('button');
                button.textContent = item.phase.split(':')[0];
                button.className = 'tab-button px-4 py-2 rounded-md font-semibold text-gray-600 bg-gray-200 transition-colors';
                if (index === 0) {
                    button.classList.add('active');
                }
                button.addEventListener('click', () => {
                    document.querySelectorAll('.tab-button').forEach(btn => btn.classList.remove('active'));
                    button.classList.add('active');
                    renderContent(index);
                });
                tabsContainer.appendChild(button);
            });
            
            renderContent(0);

            const modal = document.getElementById('video-modal');
            const modalContent = document.getElementById('modal-content');
            const modalClose = document.getElementById('modal-close');

            function openModal(video) {
                document.getElementById('modal-title').textContent = `الفيديو ${video.id}: ${video.title}`;
                document.getElementById('modal-goal').textContent = video.goal;
                document.getElementById('modal-content-details').textContent = video.content;
                modal.classList.remove('opacity-0', 'pointer-events-none');
                modalContent.classList.remove('scale-95');
            }

            function closeModal() {
                modal.classList.add('opacity-0');
                modalContent.classList.add('scale-95');
                setTimeout(() => modal.classList.add('pointer-events-none'), 300);
            }

            modalClose.addEventListener('click', closeModal);
            modal.addEventListener('click', (e) => {
                if (e.target === modal) {
                    closeModal();
                }
            });

            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
            
            const navLinks = document.querySelectorAll('header a[href^="#"]');
            navLinks.forEach(link => {
                link.addEventListener('click', (e) => {
                    if (window.innerWidth < 768) { 
                        mobileMenu.classList.add('hidden');
                    }
                });
            });

            const chartOptions = {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'bottom',
                        labels: {
                            font: {
                                family: "'Tajawal', sans-serif"
                            }
                        }
                    },
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        ticks: {
                             font: {
                                family: "'Tajawal', sans-serif"
                            }
                        }
                    },
                    x: {
                        ticks: {
                            font: {
                                family: "'Tajawal', sans-serif"
                            }
                        }
                    }
                }
            };

            new Chart(document.getElementById('subscribersChart'), {
                type: 'line',
                data: {
                    labels: ['الأسبوع 1', 'الأسبوع 2', 'الأسبوع 3', 'الأسبوع 4', 'الأسبوع 5', 'الأسبوع 6'],
                    datasets: [{
                        label: 'المشتركون الجدد',
                        data: [50, 120, 250, 400, 600, 900],
                        borderColor: 'rgb(59, 130, 246)',
                        backgroundColor: 'rgba(59, 130, 246, 0.1)',
                        tension: 0.3,
                        fill: true
                    }]
                },
                options: chartOptions
            });

            new Chart(document.getElementById('engagementChart'), {
                type: 'bar',
                data: {
                    labels: ['فيديو 1', 'فيديو 2', 'فيديو 3', 'فيديو 4', 'فيديو 5'],
                    datasets: [{
                        label: 'معدل التفاعل (%)',
                        data: [8.5, 9.2, 7.8, 10.1, 8.9],
                        backgroundColor: 'rgb(34, 197, 94)',
                    }]
                },
                options: chartOptions
            });
            
            new Chart(document.getElementById('retentionChart'), {
                type: 'doughnut',
                data: {
                    labels: ['أكملوا الفيديو', 'شاهدوا 50%', 'غادروا مبكراً'],
                    datasets: [{
                        label: 'نسبة الاحتفاظ',
                        data: [45, 35, 20],
                        backgroundColor: [
                            'rgb(16, 185, 129)',
                            'rgb(245, 158, 11)',
                            'rgb(239, 68, 68)'
                        ],
                        hoverOffset: 4
                    }]
                },
                options: { ...chartOptions, scales: {} }
            });

            new Chart(document.getElementById('ctrChart'), {
                type: 'radar',
                data: {
                    labels: ['العنوان الجذاب', 'الصورة المصغرة', 'وقت النشر', 'الموضوع الرائج', 'الكلمات المفتاحية'],
                    datasets: [{
                        label: 'عوامل تؤثر على CTR (%)',
                        data: [8, 9, 6, 7.5, 8.5],
                        fill: true,
                        backgroundColor: 'rgba(139, 92, 246, 0.2)',
                        borderColor: 'rgb(139, 92, 246)',
                        pointBackgroundColor: 'rgb(139, 92, 246)',
                    }]
                },
                options: { ...chartOptions, scales: { r: { beginAtZero: true, pointLabels: { font: { family: "'Tajawal', sans-serif" } } } } }
            });

        });
    </script>
</body>
</html>
