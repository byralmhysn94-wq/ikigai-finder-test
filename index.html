<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مختبر الإيكيغاي الرقمي</title>
    <style>
        /* ==================== CSS STYLES ==================== */
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --background-color: #ecf0f1;
            --card-color: #ffffff;
            --passion-color: #e74c3c;
            --skill-color: #f39c12;
            --world-color: #2ecc71;
            --paid-color: #9b59b6;
            --text-color: #34495e;
            --light-gray: #bdc3c7;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: var(--background-color);
            margin: 0;
            padding: 0;
            color: var(--text-color);
            direction: rtl;
            text-align: right;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        /* --- شاشات التطبيق --- */
        .screen {
            display: none;
            padding: 20px 0;
        }

        .screen.active {
            display: block;
        }

        /* --- شاشة البداية والنتائج المشتركة --- */
        h1, h2 {
            text-align: center;
            color: var(--primary-color);
        }

        .cta-button {
            display: block;
            width: 80%;
            max-width: 300px;
            margin: 30px auto;
            padding: 15px 20px;
            background-color: var(--secondary-color);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1.1em;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.1s;
        }

        .cta-button:hover {
            background-color: #2980b9;
        }

        .cta-button:active {
            transform: scale(0.98);
        }

        /* --- شاشة الأسئلة --- */
        .question-card {
            background-color: var(--card-color);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .question-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            border-bottom: 2px solid var(--light-gray);
            padding-bottom: 10px;
        }

        #question-category {
            padding: 5px 10px;
            border-radius: 5px;
            font-weight: bold;
            font-size: 0.9em;
            color: white;
        }

        .tag-passion { background-color: var(--passion-color); }
        .tag-skill { background-color: var(--skill-color); }
        .tag-world { background-color: var(--world-color); }
        .tag-paid { background-color: var(--paid-color); }

        .question-content h3 {
            font-size: 1.4em;
            margin: 10px 0 5px 0;
            color: var(--primary-color);
        }

        #question-hint {
            color: #7f8c8d;
            font-size: 0.9em;
            display: block;
            margin-bottom: 20px;
        }

        /* --- خيارات الإجابة المعدلة --- */
        #options-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
            margin-top: 25px;
        }

        .option-card {
            background-color: var(--background-color);
            padding: 15px;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.2s, border 0.2s, transform 0.1s;
            border: 2px solid var(--light-gray);
            display: flex;
            align-items: center;
        }

        .option-card:hover {
            background-color: #e0e0e0;
        }

        .option-card.selected {
            border-color: var(--secondary-color);
            background-color: #d8ecf6;
            box-shadow: 0 0 10px rgba(52, 152, 219, 0.5);
            transform: scale(1.02);
        }

        .option-number {
            font-size: 1.2em;
            font-weight: bold;
            color: var(--secondary-color);
            margin-left: 10px;
            background-color: white;
            border-radius: 50%;
            width: 30px;
            height: 30px;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-shrink: 0;
        }

        .option-card.selected .option-number {
            background-color: var(--secondary-color);
            color: white;
        }

        .option-text {
            flex-grow: 1;
        }

        /* --- شريط التقدم والتحكم --- */
        .progress-bar-container {
            margin-bottom: 20px;
            background-color: var(--light-gray);
            border-radius: 10px;
            height: 20px;
            overflow: hidden;
            position: relative;
        }

        #progress-fill {
            height: 100%;
            width: 0%;
            background-color: var(--secondary-color);
            transition: width 0.3s ease-in-out;
        }

        #progress-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-weight: bold;
            font-size: 0.8em;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.4);
        }

        .navigation-buttons {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
        }

        .nav-btn {
            padding: 12px 25px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1em;
            transition: opacity 0.3s;
        }

        #prev-btn {
            background-color: var(--light-gray);
            color: var(--text-color);
        }

        #next-btn {
            background-color: var(--secondary-color);
            color: white;
        }

        .nav-btn:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        /* --- شاشة التحميل --- */
        .loading-screen {
            text-align: center;
            padding: 100px 20px;
        }

        .spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            border-top: 4px solid var(--secondary-color);
            border-radius: 50%;
            width: 50px;
            height: 50px;
            animation: spin 1s linear infinite;
            margin: 20px auto;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* --- شاشة النتائج --- */
        .results-summary {
            text-align: center;
            margin-bottom: 40px;
            padding: 20px;
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
        }

        .ikigai-score-ring {
            width: 150px;
            height: 150px;
            margin: 20px auto;
            border-radius: 50%;
            border: 10px solid var(--light-gray);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: var(--secondary-color);
            color: white;
            font-size: 2.5em;
            font-weight: bold;
        }

        .ikigai-score-ring span {
            font-size: 0.4em;
            font-weight: normal;
        }

        .results-details {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .category-result-card {
            background-color: var(--card-color);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
            border-top: 5px solid;
        }

        .category-result-card.passion { border-color: var(--passion-color); }
        .category-result-card.skill { border-color: var(--skill-color); }
        .category-result-card.world { border-color: var(--world-color); }
        .category-result-card.paid { border-color: var(--paid-color); }

        .category-result-card h4 {
            margin-top: 0;
            font-size: 1.2em;
            color: var(--primary-color);
        }

        .category-score {
            font-size: 1.8em;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .strengths-list {
            list-style: none;
            padding: 0;
            font-size: 0.9em;
        }

        .strengths-list li {
            background-color: var(--background-color);
            padding: 5px 10px;
            margin-bottom: 5px;
            border-radius: 5px;
        }

        /* --- التوصيات المتقدمة --- */
        .recommendations-section {
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid var(--light-gray);
        }

        .recommendations-section h3 {
            color: var(--passion-color);
            border-bottom: 2px solid var(--passion-color);
            padding-bottom: 5px;
        }

        .job-card {
            background-color: #f8f8f8;
            border: 1px solid var(--light-gray);
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .job-title {
            font-weight: bold;
            color: var(--secondary-color);
            margin-bottom: 5px;
        }

        .job-salary {
            font-size: 0.9em;
            color: var(--world-color);
            margin-top: 5px;
        }

        .job-links a {
            display: inline-block;
            margin-left: 10px;
            font-size: 0.8em;
            color: var(--primary-color);
            text-decoration: none;
            border: 1px solid var(--primary-color);
            padding: 3px 8px;
            border-radius: 5px;
        }

        /* --- الإشعارات --- */
        #notification {
            position: fixed;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            z-index: 1000;
            display: none;
            animation: fadeInOut 3s forwards;
        }

        @keyframes fadeInOut {
            0%, 100% { opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>مختبر الإيكيغاي الرقمي</h1>
        <p style="text-align: center; color: #7f8c8d;">ابحث عن نقطة تلاقي شغفك، ومهارتك، واحتياج العالم، وما يُدفع لك مقابله.</p>
    </header>

    <div id="start-screen" class="screen active">
        <div class="question-card">
            <h2>ابدأ رحلة الإيكيغاي الخاصة بك</h2>
            <p style="text-align: center;">سيساعدك هذا الاختبار على تحليل ميولك ونقاط قوتك بدقة عالية من خلال 80 سؤالاً مُركَّزاً.</p>
            <p style="text-align: center; font-weight: bold; color: var(--passion-color);">يرجى اختيار الإجابة التي تمثلك بدقة في كل سؤال.</p>
            <button class="cta-button" id="start-button">ابدأ الاختبار الآن</button>
        </div>
    </div>

    <div id="question-screen" class="screen">
        <div class="progress-bar-container">
            <div id="progress-fill"></div>
            <div id="progress-text">السؤال 1 من 80</div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span id="question-category" class="category-tag tag-passion">الشغف</span>
                <span id="category-text">الشغف</span>
            </div>
            
            <div class="question-content">
                <h3 id="question-text">ما هو الشيء الذي لا تمل من القيام به؟</h3>
                <span id="question-hint">فكر في الأنشطة التي تجعلك تفقد الإحساس بالوقت.</span>
            </div>
        </div>
        
        <div id="options-container">
            </div>

        <div class="navigation-buttons">
            <button id="prev-btn" class="nav-btn" onclick="prevQuestion()" disabled>السابق</button>
            <button id="next-btn" class="nav-btn" onclick="nextQuestion()">التالي</button>
        </div>
    </div>

    <div id="loading-screen" class="screen loading-screen">
        <div class="spinner"></div>
        <h2>جارٍ تحليل الإجابات...</h2>
        <p>نحن نعمل على مطابقة شغفك بمهاراتك واحتياجات السوق.</p>
    </div>

    <div id="results-screen" class="screen">
        <h2>نتائج الإيكيغاي الخاصة بك</h2>

        <div class="results-summary">
            <h3>مستوى الإيكيغاي العام</h3>
            <div class="ikigai-score-ring" id="ikigai-score-ring">
                <span id="ikigai-score">0</span>
                <span>%</span>
            </div>
            <p id="ikigai-label" style="font-weight: bold; font-size: 1.2em;"></p>
        </div>

        <h3>نقاط القوة الأساسية</h3>
        <div class="results-details">
            
            <div class="category-result-card passion">
                <h4>الشغف (ما تحب)</h4>
                <div class="category-score" id="passion-score">0%</div>
                <p id="passion-text"></p>
                <h5>التركيز الأعلى:</h5>
                <ul class="strengths-list" id="passion-strengths"></ul>
            </div>

            <div class="category-result-card skill">
                <h4>المهارة (ما تتقن)</h4>
                <div class="category-score" id="skill-score">0%</div>
                <p id="skill-text"></p>
                <h5>التركيز الأعلى:</h5>
                <ul class="strengths-list" id="skill-strengths"></ul>
            </div>

            <div class="category-result-card world">
                <h4>احتياج العالم (ما يحتاجه)</h4>
                <div class="category-score" id="world-score">0%</div>
                <p id="world-text"></p>
                <h5>التركيز الأعلى:</h5>
                <ul class="strengths-list" id="world-strengths"></ul>
            </div>

            <div class="category-result-card paid">
                <h4>الدخل (ما يُدفع لك مقابله)</h4>
                <div class="category-score" id="paid-score">0%</div>
                <p id="paid-text"></p>
                <h5>التركيز الأعلى:</h5>
                <ul class="strengths-list" id="paid-strengths"></ul>
            </div>
        </div>

        <div class="recommendations-section">
            <h3>وظائف مقترحة بناءً على نقطة الإيكيغاي الخاصة بك</h3>
            <p>هذه الوظائف تحقق التوازن الأكبر بين الفئات الأربع لديك، مع التركيز على فئتك المهيمنة:</p>
            <div id="jobs-grid" class="jobs-grid">
                </div>
        </div>

        <button class="cta-button" onclick="restartTest()">ابدأ من جديد</button>
    </div>

    <div id="notification"></div>

</div>

<script>
    // ==================== بيانات التطبيق ====================
    const appState = {
        currentQuestion: 0,
        answers: {},
        scores: {
            passion: 0,
            skill: 0,
            world: 0,
            paid: 0
        },
        strengths: {
            passion: {},
            skill: {},
            world: {},
            paid: {}
        }
    };

    // ==================== قاعدة الأسئلة (80 سؤال) ====================
    const questions = [
        // ========== الشغف (20 سؤال) ==========
        { id: 1, category: 'passion', text: 'ما الذي تفعله عندما يكون لديك وقت فراغ تماماً؟', hint: 'فكر في الأنشطة التي تختارها عندما تكون حراً في فعل أي شيء' },
        { id: 2, category: 'passion', text: 'ما الموضوع الذي يمكنك التحدث عنه لساعات دون ملل؟', hint: 'المجال الذي تستمتع بالقراءة عنه ومشاركته مع الآخرين' },
        { id: 3, category: 'passion', text: 'ما هو آخر شيء تعلمته بسرور وليس بضغط؟', hint: 'المهارة أو المعرفة التي اكتسبتها بدافع شخصي' },
        { id: 4, category: 'passion', text: 'ما النشاط الذي يجعلك تفقد الإحساس بالوقت؟', hint: 'عندما تكون منغمساً فيه تماماً' },
        { id: 5, category: 'passion', text: 'ما الذي كنت تحب فعله في طفولتك؟', hint: 'الهوايات أو الأنشطة التي كنت تستمتع بها' },
        { id: 6, category: 'passion', text: 'ما الشيء الذي تتطلع إليه خلال الأسبوع؟', hint: 'النشاط الذي يمنحك الطاقة والحماس' },
        { id: 7, category: 'passion', text: 'ما نوع الكتب أو الأفلام التي تفضل مشاهدة/قراءتها؟', hint: 'المواضيع التي تجذب انتباهك باستمرار' },
        { id: 8, category: 'passion', text: 'كيف ستنفق وقتك إذا فزت بجائزة مالية كبيرة ولم تعد مضطراً للعمل؟', hint: 'كيف ستغير روتين حياتك اليومي' },
        { id: 9, category: 'passion', text: 'ما الذي يجعلك تشعر بالحيوية والنشاط؟', hint: 'المحفزات التي تزيد طاقتك' },
        { id: 10, category: 'passion', text: 'ما الشيء الذي تتمنى لو لديك المزيد من الوقت لفعله؟', hint: 'النشاط الذي تستمتع به ولكن الوقت لا يسمح' },
        { id: 11, category: 'passion', text: 'ما الذي تحلم بتحقيقه إذا لم تكن هناك قيود؟', hint: 'الأهداف الشخصية غير المرتبطة بالمال أو الظروف' },
        { id: 12, category: 'passion', text: 'ما النشاط الذي تشعر بالرضا بعد الانتهاء منه؟', hint: 'الشعور بالإنجاز والرضا' },
        { id: 13, category: 'passion', text: 'ما الجوانب التي تحب تعلمها عن نفسك؟', hint: 'التي تثير فضولك عن شخصيتك' },
        { id: 14, category: 'passion', text: 'ما المكان الذي تحب زيارته والتعرف عليه؟', hint: 'الأماكن التي تثير اهتمامك' },
        { id: 15, category: 'passion', text: 'ما نوع التجارب التي تبحث عنها؟', hint: 'المغامرات أو الخبرات الجديدة' },
        { id: 16, category: 'passion', text: 'ما الذي يثير إبداعك؟', hint: 'المحفزات الإبداعية' },
        { id: 17, category: 'passion', text: 'ما الشيء الذي تحب مشاركته وتعليمه للآخرين؟', hint: 'المعارف أو الخبرات التي تحب نقلها' },
        { id: 18, category: 'passion', text: 'ما النشاط الذي تستمتع به حتى لو كنت متعباً؟', hint: 'الذي يمنحك الطاقة' },
        { id: 19, category: 'passion', text: 'ما الشيء الذي لا تمل من تكراره؟', hint: 'النشاط المستمر الذي لا يفقد جاذبيته' },
        { id: 20, category: 'passion', text: 'ما الذي تشعر أنه جزء أساسي من هويتك؟', hint: 'الجوانب التي تحدد شخصيتك' },

        // ========== المهارات (20 سؤال) ==========
        { id: 21, category: 'skill', text: 'في أي مجال يطلب منك الآخرون المساعدة أو النصيحة باستمرار؟', hint: 'المجال الذي يعتمد عليك فيه الناس' },
        { id: 22, category: 'skill', text: 'ما المهارة التي تتعلمها بسرعة وسهولة مقارنة بغيرها؟', hint: 'المهارات التي تكتسبها بجهد أقل' },
        { id: 23, category: 'skill', text: 'ما الذي تتقنه بشكل طبيعي دون تدريب مكثف؟', hint: 'المواهب الفطرية' },
        { id: 24, category: 'skill', text: 'ما المجال الذي تتلقى فيه إشادات متكررة من الزملاء أو المشرفين؟', hint: 'المهارات التي يلاحظها الآخرون' },
        { id: 25, category: 'skill', text: 'ما المهمة التي تشعر بالثقة الكاملة عند البدء بها؟', hint: 'المهام التي لا تشك في قدرتك عليها' },
        { id: 26, category: 'skill', text: 'ما الذي يمكنك تعليمه للآخرين بوضوح وفاعلية؟', hint: 'المعارف التي تتقنها' },
        { id: 27, category: 'skill', text: 'ما المجال الذي لديك فيه خبرة عملية أو ميدانية ملموسة؟', hint: 'الخبرات الميدانية' },
        { id: 28, category: 'skill', text: 'ما المهارة التي طورتها بشكل منهجي عبر السنوات؟', hint: 'التطور المهني المستمر' },
        { id: 29, category: 'skill', text: 'ما الدور الذي تجيده في العمل الجماعي أو الفريق؟', hint: 'نقاط التميز المهني' },
        { id: 30, category: 'skill', text: 'ما المهارات التي تعتبر نقاط قوة في شخصيتك الاجتماعية؟', hint: 'المهارات الشخصية المتميزة' },
        { id: 31, category: 'skill', text: 'ما الشيء الذي يمكنك القيام به بشكل أفضل من 80% من الناس؟', hint: 'المهارات النسبية' },
        { id: 32, category: 'skill', text: 'ما المهمة التي تستمتع بها لأنك ببساطة تجيدها؟', hint: 'الارتباط بين الإتقان والمتعة' },
        { id: 33, category: 'skill', text: 'ما المهارات التقنية/الرقمية التي تتقنها؟', hint: 'المهارات التقنية المتخصصة' },
        { id: 34, category: 'skill', text: 'ما الذي يمكنك إنجازه في وقت قياسي وبجودة عالية؟', hint: 'الكفاءة والإنتاجية' },
        { id: 35, category: 'skill', text: 'ما المهارات التي تطورت لديك من خلال الهوايات أو الأنشطة غير الرسمية؟', hint: 'المهارات المكتسبة من الأنشطة غير الرسمية' },
        { id: 36, category: 'skill', text: 'ما المجال الذي لديك فيه مؤهلات رسمية (شهادات/دورات متقدمة)؟', hint: 'المؤهلات الرسمية' },
        { id: 37, category: 'skill', text: 'ما الذي تجيده في التعامل مع النزاعات أو الخلافات؟', hint: 'المهارات الاجتماعية' },
        { id: 38, category: 'skill', text: 'ما المهارات الإدارية أو القيادية التي تمتلكها؟', hint: 'القدرات القيادية' },
        { id: 39, category: 'skill', text: 'ما الذي تجيده في حل المشكلات المعقدة؟', hint: 'مهارات التفكير النقدي' },
        { id: 40, category: 'skill', text: 'ما المهارات الإبداعية التي تمتلكها؟', hint: 'القدرات الإبداعية والابتكارية' },

        // ========== احتياجات العالم (20 سؤال) ==========
        { id: 41, category: 'world', text: 'ما المشكلة المجتمعية التي تثير فيك قلقاً عميقاً؟', hint: 'القضايا التي تشعر بالمسؤولية تجاهها' },
        { id: 42, category: 'world', text: 'ما الذي ترى أن العالم بحاجة ماسة إليه لتجاوز أزمة معينة؟', hint: 'الحاجات العالمية الملحة' },
        { id: 43, category: 'world', text: 'ما القضية التي تتابع أخبارها وتبحث عن حلولها باستمرار؟', hint: 'المواضيع التي تتابعها باهتمام' },
        { id: 44, category: 'world', text: 'ما الشيء الذي تتمنى تغييره في نظام التعليم أو الصحة في مجتمعك؟', hint: 'التغييرات المجتمعية المطلوبة' },
        { id: 45, category: 'world', text: 'ما المجال الذي ترى أن التطوير فيه ضروري لتمكين الفئات الأضعف؟', hint: 'مجالات التطوير المجتمعي' },
        { id: 46, category: 'world', text: 'ما الذي تحس أن الناس يعانون منه في حياتهم اليومية؟', hint: 'المعاناة المجتمعية' },
        { id: 47, category: 'world', text: 'ما القضية التي تشعر أنها الأكثر إلحاحاً وغير منصفة؟', hint: 'قضايا العدالة الاجتماعية' },
        { id: 48, category: 'world', text: 'ما الذي يحتاجه قطاع التكنولوجيا/البيئة/الزراعة لتطويره؟', hint: 'احتياجات القطاع المهني' },
        { id: 49, category: 'world', text: 'ما المشكلة البيئية التي تهتم بها بشكل خاص (التغير المناخي، النفايات، إلخ)؟', hint: 'قضايا البيئة والاستدامة' },
        { id: 50, category: 'world', text: 'ما الذي يحتاجه الشباب في مجتمعك لضمان مستقبل أفضل؟', hint: 'احتياجات الفئة الشبابية' },
        { id: 51, category: 'world', text: 'ما المجال التعليمي الذي يحتاج تطويراً جذرياً؟', hint: 'احتياجات النظام التعليمي' },
        { id: 52, category: 'world', text: 'ما القضية الصحية التي ترى أهميتها الكبرى؟', hint: 'مجالات الصحة العامة' },
        { id: 53, category: 'world', text: 'ما الذي يحتاجه الاقتصاد المحلي للنمو؟', hint: 'احتياجات التنمية الاقتصادية' },
        { id: 54, category: 'world', text: 'ما المشكلة التكنولوجية التي تحتاج لحلول مبتكرة؟', hint: 'التحديات التقنية' },
        { id: 55, category: 'world', text: 'ما الذي يحتاجه قطاع الأعمال ليصبح أكثر أخلاقية واستدامة؟', hint: 'احتياجات بيئة الأعمال' },
        { id: 56, category: 'world', text: 'ما القضية الثقافية التي تهتم بها (التراث، الهوية، الفنون)؟', hint: 'المجال الثقافي والفني' },
        { id: 57, category: 'world', text: 'ما الذي يحتاجه الأشخاص ذوو الإعاقة للاندماج الكامل؟', hint: 'قضايا الدمج والتمكين' },
        { id: 58, category: 'world', text: 'ما المشكلة الأسرية أو الاجتماعية التي تراها منتشرة؟', hint: 'قضايا الأسرة والمجتمع' },
        { id: 59, category: 'world', text: 'ما الذي يحتاجه القطاع الزراعي لضمان الأمن الغذائي؟', hint: 'تحديات القطاع الزراعي' },
        { id: 60, category: 'world', text: 'ما القضية الإنسانية التي تلامس قلبك (اللاجئون، الفقراء، إلخ)؟', hint: 'القضايا الإنسانية العاجلة' },

        // ========== ما يُدفع لك مقابله (20 سؤال) ==========
        { id: 61, category: 'paid', text: 'ما المهارات المطلوبة في سوق العمل الأردني حالياً؟', hint: 'المهارات الأكثر طلباً' },
        { id: 62, category: 'paid', text: 'ما المجالات التي تشهد نمواً كبيراً في الأردن؟', hint: 'القطاعات المتوسعة' },
        { id: 63, category: 'paid', text: 'ما الوظائف التي تقدم رواتب مجزية مقارنة بالجهد المطلوب؟', hint: 'المجالات المالية المجزية' },
        { id: 64, category: 'paid', text: 'ما الخدمات أو المنتجات التي يطلبها الناس بكثرة في الأردن؟', hint: 'احتياجات السوق المحلي' },
        { id: 65, category: 'paid', text: 'ما المشاريع الريادية الأكثر نجاحاً واستدامة في الأردن؟', hint: 'نماذج الأعمال الناجحة' },
        { id: 66, category: 'paid', text: 'ما المهن التي لديها طلب مستمر ولا تتأثر كثيراً بالأزمات؟', hint: 'المهن الأساسية' },
        { id: 67, category: 'paid', text: 'ما المجالات التكنولوجية الأكثر طلباً في الشركات الكبرى؟', hint: 'التخصصات التقنية' },
        { id: 68, category: 'paid', text: 'ما الوظائف التي تسمح بالعمل عن بعد وتقدم دخلاً بالدولار؟', hint: 'فرص العمل المرن' },
        { id: 69, category: 'paid', text: 'ما القطاعات التي تستثمر فيها الحكومة الأردنية حالياً؟', hint: 'مجالات الدعم الحكومي' },
        { id: 70, category: 'paid', text: 'ما الخدمات الجديدة التي يحتاجها القطاع السياحي في الأردن؟', hint: 'فرص القطاع السياحي' },
        { id: 71, category: 'paid', text: 'ما المشاريع الصغيرة التي يمكن أن تدر دخلاً جيداً في الأحياء؟', hint: 'أفكار المشاريع الصغيرة' },
        { id: 72, category: 'paid', text: 'ما المهارات التي تزيد فرص التوظيف بسرعة؟', hint: 'المهارات التنافسية' },
        { id: 73, category: 'paid', text: 'ما المجالات الطبية/الصحية المطلوبة حالياً في الأردن؟', hint: 'فرص القطاع الصحي' },
        { id: 74, category: 'paid', text: 'ما الخدمات التعليمية التي لديها طلب عالٍ (مثل الدروس الخصوصية، التدريب)؟', hint: 'فرص القطاع التعليمي' },
        { id: 75, category: 'paid', text: 'ما المشاريع الخدمية المربحة التي لا تحتاج لرأس مال كبير؟', hint: 'الأعمال الخدمية' },
        { id: 76, category: 'paid', text: 'ما المجالات الهندسية المطلوبة بكثرة في مشاريع البنية التحتية؟', hint: 'فرص القطاع الهندسي' },
        { id: 77, category: 'paid', text: 'ما خدمات الدعم التي يحتاجها رواد الأعمال والشركات الناشئة؟', hint: 'قطاع دعم الأعمال' },
        { id: 78, category: 'paid', text: 'ما المجالات الإعلامية المطلوبة (مثل صناعة المحتوى، التسويق عبر المؤثرين)؟', hint: 'فرص الإعلام الجديد' },
        { id: 79, category: 'paid', text: 'ما الخدمات المالية التي يحتاجها الأفراد والشركات في ظل التضخم؟', hint: 'فرص القطاع المالي' },
        { id: 80, category: 'paid', text: 'ما المشاريع التي تدعمها المؤسسات الدولية والمانحين في الأردن؟', hint: 'فرص التمويل الدولي' }
    ];

    // خيارات الإجابة المعدلة (نمط الأسئلة المحددة)
    const questionOptions = {
        // ========== الشغف (Passion) - أمثلة موسعة لجميع الأسئلة الـ 80 ==========
        1: [
            { text: 'أقرأ، أكتب، أو أتعلم شيئاً جديداً', value: 9, focus: 'تعلم، تحليل، بحث' },
            { text: 'أصمم، أرسم، أطبخ، أو أمارس حرفة يدوية', value: 8, focus: 'إبداع، فنون، تصميم' },
            { text: 'أمارس الرياضة أو أنشطة خارجية حركية', value: 7, focus: 'حركة، لياقة، طاقة' },
            { text: 'أتواصل مع الأصدقاء، أساعدهم، أو أحل خلافاتهم', value: 6, focus: 'تواصل، اجتماعي، إرشاد' }
        ],
        2: [
            { text: 'التنمية البشرية وعلم النفس والسلوك', value: 9, focus: 'إرشاد، تحليل نفسي، تعليم' },
            { text: 'التكنولوجيا، الذكاء الاصطناعي، والابتكارات', value: 8, focus: 'تقنية، برمجة، هندسة' },
            { text: 'التاريخ، الثقافة، والسياسة الدولية', value: 7, focus: 'وعي عالمي، تحليل سياسي، بحث' },
            { text: 'الفنون، السينما، الأدب، أو الموسيقى', value: 6, focus: 'فنون، إبداع، ثقافة' }
        ],
        3: [
            { text: 'برنامج حاسوبي أو لغة برمجة جديدة', value: 9, focus: 'تقنية، برمجة، تحليل' },
            { text: 'مهارة تواصل أو إلقاء أمام الجمهور', value: 8, focus: 'قيادة، تواصل، إقناع' },
            { text: 'مهارة يدوية أو رياضية', value: 7, focus: 'حركة، فنون، تصميم' },
            { text: 'قراءة الكتب والمقالات المتخصصة', value: 6, focus: 'بحث، تحليل، تعلم' }
        ],
        4: [
            { text: 'العمل على مشروع معقد يتطلب تركيزاً عميقاً (برمجة، تصميم، كتابة)', value: 9, focus: 'تركيز، تحليل، تقنية' },
            { text: 'مساعدة شخص آخر على حل مشكلة أو تحقيق هدف', value: 8, focus: 'إرشاد، مساعدة، اجتماعي' },
            { text: 'ممارسة هواية إبداعية (رسم، عزف، تصوير)', value: 7, focus: 'إبداع، فنون، تصميم' },
            { text: 'تنظيم وترتيب جدول أعمالي ومساحة عملي', value: 6, focus: 'تنظيم، تخطيط، إدارة' }
        ],
        5: [
            { text: 'تصميم وبناء أشياء صغيرة (ليغو، نماذج، تركيبات)', value: 9, focus: 'هندسة، تصميم، حل مشكلات' },
            { text: 'اللعب الجماعي وتنظيم الأنشطة مع الأصدقاء', value: 8, focus: 'قيادة، تواصل، اجتماعي' },
            { text: 'القراءة والقصص والبحث عن معلومات', value: 7, focus: 'تعلم، بحث، تحليل' },
            { text: 'الرسم أو التلوين أو صنع الحرف اليدوية', value: 6, focus: 'إبداع، فنون، تصميم' }
        ],
        6: [
            { text: 'موعد أو نشاط يتعلق بمشروع جديد أعمل عليه', value: 9, focus: 'إنجاز، عمل، تركيز' },
            { text: 'وقت قراءة أو تعلم مخصص', value: 8, focus: 'تعلم، بحث، تطوير الذات' },
            { text: 'لقاء اجتماعي أو مساعدة شخص محتاج', value: 7, focus: 'اجتماعي، إرشاد، إنساني' },
            { text: 'ممارسة الرياضة أو أي نشاط بدني', value: 6, focus: 'حركة، طاقة، لياقة' }
        ],
        7: [
            { text: 'أفلام/كتب الخيال العلمي أو التكنولوجيا المعقدة', value: 9, focus: 'تقنية، خيال، تحليل' },
            { text: 'الوثائقيات عن التاريخ أو الطبيعة أو المجتمعات', value: 8, focus: 'بحث، وعي عالمي، ثقافة' },
            { text: 'كتب التنمية الذاتية وعلم النفس', value: 7, focus: 'إرشاد، تحليل نفسي، تعليم' },
            { text: 'أعمال فنية (روايات، مسرحيات، أفلام درامية)', value: 6, focus: 'فنون، إبداع، تحليل عاطفي' }
        ],
        8: [
            { text: 'سأستثمر وقتي في البحث والتعلم والتدريب في مجال جديد', value: 9, focus: 'تعلم، بحث، تطوير الذات' },
            { text: 'سأخصص وقتي للتأليف أو الرسم أو التصميم', value: 8, focus: 'إبداع، فنون، تصميم' },
            { text: 'سأبدأ مشروعاً اجتماعياً أو بيئياً لحل مشكلة ما', value: 7, focus: 'إنساني، اجتماعي، قيادة' },
            { text: 'سأقضي وقتي في السفر والتجول واكتشاف ثقافات جديدة', value: 6, focus: 'وعي عالمي، تواصل، مغامرة' }
        ],
        9: [
            { text: 'عندما أحل مشكلة معقدة وأجد حلاً مبتكراً', value: 9, focus: 'حل مشكلات، تحليل، ابتكار' },
            { text: 'عندما أساعد شخصاً على النجاح أو أُحدث فرقاً إيجابياً', value: 8, focus: 'إرشاد، اجتماعي، مساعدة' },
            { text: 'عندما أكون منغمساً في عمل إبداعي أو فني', value: 7, focus: 'إبداع، فنون، تصميم' },
            { text: 'عندما أحقق هدفاً رياضياً أو بدنياً صعباً', value: 6, focus: 'حركة، طاقة، إنجاز' }
        ],
        10: [
            { text: 'تطوير مشروع شخصي أو تقني خاص بي', value: 9, focus: 'تقنية، برمجة، عمل حر' },
            { text: 'القراءة والبحث والتحليل في مجال تخصصي', value: 8, focus: 'تعلم، بحث، تحليل' },
            { text: 'العمل التطوعي ومساعدة المحتاجين', value: 7, focus: 'إنساني، اجتماعي، عطاء' },
            { text: 'الرياضة أو المهارات الحركية المعقدة', value: 6, focus: 'حركة، لياقة، إتقان' }
        ],
        // (إضافة خيارات باقي أسئلة الشغف بنفس النمط، مع التركيز على نقاط (تعلم، تحليل، إبداع، اجتماعي، تقنية، إلخ))
        11: [{ text: 'إنشاء شركة تقنية تغير طريقة عيش الناس', value: 9, focus: 'تقنية، ريادة، ابتكار' }, { text: 'تأليف كتاب أو عمل فني خالد', value: 8, focus: 'إبداع، فنون، تأثير' }, { text: 'قيادة منظمة تنموية دولية', value: 7, focus: 'قيادة، إنساني، وعي عالمي' }, { text: 'السفر حول العالم والتعلم منه', value: 6, focus: 'بحث، وعي عالمي، مغامرة' }],
        12: [{ text: 'إنهاء تحليل معقد أو تقرير مفصل', value: 9, focus: 'تحليل، إنجاز، تركيز' }, { text: 'تدريب شخص ما وتطور مستواه بسببي', value: 8, focus: 'إرشاد، تعليم، اجتماعي' }, { text: 'إنهاء عمل فني (تصميم، صورة، مقطوعة)', value: 7, focus: 'إبداع، تصميم، فنون' }, { text: 'تنظيم وترتيب جدول أعمالي ومساحة عملي بالكامل', value: 6, focus: 'تنظيم، إدارة، تخطيط' }],
        13: [{ text: 'كيف أتعامل مع الضغوط والتحديات النفسية', value: 9, focus: 'تحليل نفسي، تطوير الذات' }, { text: 'كيف أتعلم مهارات جديدة بسرعة وفعالية', value: 8, focus: 'تعلم، تحليل، بحث' }, { text: 'نقاط قوتي في القيادة والتأثير على الآخرين', value: 7, focus: 'قيادة، تواصل، اجتماعي' }, { text: 'كيف أستخدم الإبداع في حل المشكلات اليومية', value: 6, focus: 'إبداع، حل مشكلات' }],
        14: [{ text: 'المراكز البحثية والمختبرات التقنية المتقدمة', value: 9, focus: 'تقنية، بحث، تحليل' }, { text: 'المتاحف الفنية والمعارض الثقافية', value: 8, focus: 'فنون، ثقافة، إبداع' }, { text: 'القرى النائية والمدارس في المناطق الفقيرة', value: 7, focus: 'إنساني، اجتماعي، تنمية' }, { text: 'المدن التي تشتهر بتاريخها القديم أو هندستها المعمارية', value: 6, focus: 'وعي عالمي، تصميم، بحث' }],
        15: [{ text: 'التجارب التي تتطلب تحليلاً منطقياً وتخطيطاً دقيقاً', value: 9, focus: 'تحليل، منطق، تخطيط' }, { text: 'التجارب التي تتضمن لقاء وتوجيه مجموعة من الناس', value: 8, focus: 'تواصل، قيادة، إرشاد' }, { text: 'التجارب التي تسمح لي بالتعبير الفني والشخصي', value: 7, focus: 'إبداع، فنون، تصميم' }, { text: 'التجارب التي تتضمن منافسة رياضية أو تحدياً بدنياً', value: 6, focus: 'حركة، طاقة، إنجاز' }],
        16: [{ text: 'عندما أرى بيانات أو معلومات مُنظَّمة بطريقة جديدة', value: 9, focus: 'تحليل، تقنية، منطق' }, { text: 'عندما أستمع إلى الموسيقى أو أرى عملاً فنياً ملهماً', value: 8, focus: 'إبداع، فنون، تصميم' }, { text: 'عندما أشارك في جلسة عصف ذهني مع فريق متنوع', value: 7, focus: 'تواصل، اجتماعي، ابتكار' }, { text: 'عندما أتعرض لمشكلة حياتية لم يسبق لي حلها', value: 6, focus: 'حل مشكلات، مرونة' }],
        17: [{ text: 'كيفية استخدام أحدث الأدوات التقنية والبرمجيات', value: 9, focus: 'تقنية، تعليم، تحليل' }, { text: 'مهارات التواصل والإقناع وبناء الثقة', value: 8, focus: 'تواصل، إرشاد، قيادة' }, { text: 'مهارات التصميم والرسم الرقمي أو اليدوي', value: 7, focus: 'تصميم، إبداع، فنون' }, { text: 'كيفية إدارة الوقت والمشاريع بفعالية', value: 6, focus: 'تنظيم، إدارة، تخطيط' }],
        18: [{ text: 'البرمجة أو العمل على لوحات بيانات معقدة', value: 9, focus: 'تقنية، تحليل، تركيز' }, { text: 'التخطيط لحدث اجتماعي أو تدريبي', value: 8, focus: 'اجتماعي، قيادة، تنظيم' }, { text: 'الرسم، الكتابة، أو صناعة المحتوى', value: 7, focus: 'إبداع، فنون، تصميم' }, { text: 'تنظيف وترتيب مكان عملي أو منزلي', value: 6, focus: 'تنظيم، إدارة، هدوء' }],
        19: [{ text: 'تحليل البيانات وإعداد التقارير الفنية', value: 9, focus: 'تحليل، منطق، بحث' }, { text: 'التفاعل مع الناس وحل خلافاتهم', value: 8, focus: 'تواصل، اجتماعي، إرشاد' }, { text: 'الابتكار في طريقة استخدام الأدوات التقنية', value: 7, focus: 'تقنية، ابتكار، تصميم' }, { text: 'ممارسة هواية حركية أو رياضية', value: 6, focus: 'حركة، لياقة، إتقان' }],
        20: [{ text: 'قدرتي على التحليل المنطقي واتخاذ القرارات العقلانية', value: 9, focus: 'تحليل، منطق، عقلانية' }, { text: 'قدرتي على التأثير الإيجابي في حياة الآخرين', value: 8, focus: 'اجتماعي، إنساني، إرشاد' }, { text: 'قدرتي على تحويل الأفكار المجردة إلى واقع ملموس (تصميم)', value: 7, focus: 'إبداع، تصميم، إنجاز' }, { text: 'التزامي بالنظام والقواعد والتنفيذ الدقيق للمهام', value: 6, focus: 'تنظيم، إدارة، دقة' }],

        // ========== المهارات (Skill) - أمثلة موسعة لجميع الأسئلة الـ 80 ==========
        21: [
            { text: 'في تحليل البيانات وإيجاد الأنماط وحل المشكلات المعقدة', value: 9, focus: 'تحليل، منطق، تقنية' },
            { text: 'في تنظيم المواعيد والمهام وإدارة المشاريع', value: 8, focus: 'إدارة، تخطيط، تنظيم' },
            { text: 'في تقديم العروض والإقناع وبناء العلاقات', value: 7, focus: 'تواصل، قيادة، إقناع' },
            { text: 'في تصميم وتجميل الأشياء (مرئيات، مساحات، أزياء)', value: 6, focus: 'تصميم، إبداع، فنون' }
        ],
        22: [{ text: 'لغات البرمجة أو التعامل مع الأنظمة الجديدة', value: 9, focus: 'تقنية، تحليل، تعلم' }, { text: 'مهارات التفاوض والإقناع (البيع، النقاش)', value: 8, focus: 'تواصل، إقناع، قيادة' }, { text: 'المهارات اليدوية (صيانة، تركيب، طبخ)', value: 7, focus: 'حركة، تطبيق، إتقان' }, { text: 'مهارة البحث وجمع المعلومات وتحليلها', value: 6, focus: 'بحث، تحليل، منطق' }],
        23: [{ text: 'رؤية الأخطاء المنطقية أو الفنية في التصاميم والتقارير', value: 9, focus: 'دقة، تحليل، نقد' }, { text: 'التعاطف مع الناس وفهم دوافعهم وحل خلافاتهم', value: 8, focus: 'اجتماعي، إرشاد، تواصل' }, { text: 'القدرة على الكتابة الإبداعية أو رواية القصص', value: 7, focus: 'إبداع، فنون، تواصل' }, { text: 'تنظيم الأحداث الكبيرة وتنسيق الأفراد', value: 6, focus: 'تنظيم، إدارة، قيادة' }],
        24: [{ text: 'دقة عملي وخلوه من الأخطاء المنطقية والفنية', value: 9, focus: 'تحليل، دقة، منطق' }, { text: 'قدرتي على بناء فريق متماسك وإدارة الأفراد', value: 8, focus: 'قيادة، إدارة، اجتماعي' }, { text: 'أفكاري الإبداعية والمبتكرة لحل مشكلات قديمة', value: 7, focus: 'إبداع، ابتكار، تصميم' }, { text: 'سرعتي في إنجاز المهام التي تتطلب عملاً يدوياً أو فنياً', value: 6, focus: 'تطبيق، إتقان، حركة' }],
        25: [{ text: 'تصميم بنية قواعد بيانات أو نظام تقني معقد', value: 9, focus: 'تقنية، تحليل، تخطيط' }, { text: 'إدارة أزمة أو نزاع بين أعضاء الفريق', value: 8, focus: 'قيادة، إدارة، اجتماعي' }, { text: 'العمل على تصميم جرافيكي أو معماري كبير', value: 7, focus: 'تصميم، إبداع، فنون' }, { text: 'إعداد خطة مالية أو ميزانية سنوية', value: 6, focus: 'تنظيم، إدارة، منطق' }],
        26: [{ text: 'مفاهيم التكنولوجيا والذكاء الاصطناعي', value: 9, focus: 'تقنية، تعليم، تحليل' }, { text: 'مهارات الإقناع والتفاوض والمبيعات', value: 8, focus: 'تواصل، إقناع، قيادة' }, { text: 'مهارات التصميم الجرافيكي أو المونتاج', value: 7, focus: 'إبداع، تصميم، فنون' }, { text: 'مهارات تنظيم المشاريع وإدارة الوقت', value: 6, focus: 'تنظيم، إدارة، تعليم' }],
        27: [{ text: 'في تحليل الأسواق وإعداد دراسات الجدوى', value: 9, focus: 'تحليل، منطق، تخطيط' }, { text: 'في قيادة فريق عمل لتحقيق أهداف محددة', value: 8, focus: 'قيادة، إدارة، اجتماعي' }, { text: 'في بناء وتشغيل نظام تقني أو موقع ويب', value: 7, focus: 'تقنية، تطبيق، هندسة' }, { text: 'في التعامل مع المواد الخام والمعدات اليدوية', value: 6, focus: 'تطبيق، إتقان، حركة' }],
        28: [{ text: 'تحليل البيانات وإعداد نماذج تنبؤية (Modeling)', value: 9, focus: 'تحليل، منطق، تقنية' }, { text: 'إدارة فرق العمل الكبيرة والميزانيات الضخمة', value: 8, focus: 'إدارة، قيادة، تخطيط' }, { text: 'مهارات الإلقاء والخطابة والتواصل الجماهيري', value: 7, focus: 'تواصل، قيادة، إقناع' }, { text: 'مهارات الرسم والتلوين والتشكيل الفني', value: 6, focus: 'إبداع، فنون، تصميم' }],
        29: [{ text: 'المحلل الذي يجد الأخطاء والفرص المخفية', value: 9, focus: 'تحليل، منطق، نقد' }, { text: 'القائد الذي يحفز الفريق ويتخذ القرارات الصعبة', value: 8, focus: 'قيادة، إدارة، اجتماعي' }, { text: 'المُصمم الذي يبتكر حلولاً جمالية ووظيفية', value: 7, focus: 'إبداع، تصميم، ابتكار' }, { text: 'المنظِّم الذي يضمن أن تسير العملية بدقة زمنية عالية', value: 6, focus: 'تنظيم، إدارة، دقة' }],
        30: [{ text: 'التفكير النقدي، الدقة، والانتباه للتفاصيل', value: 9, focus: 'تحليل، منطق، دقة' }, { text: 'التعاطف، الاستماع النشط، وبناء الثقة بسرعة', value: 8, focus: 'اجتماعي، إرشاد، تواصل' }, { text: 'الإبداع في الكلام والكتابة والقدرة على السرد', value: 7, focus: 'إبداع، فنون، تواصل' }, { text: 'المرونة، سرعة التكيف، والقدرة على العمل تحت الضغط', value: 6, focus: 'إدارة، مرونة، إتقان' }],
        31: [{ text: 'تحويل البيانات المعقدة إلى رسوم بيانية وتقارير مفهومة', value: 9, focus: 'تحليل، تقنية، تعليم' }, { text: 'إقناع الأطراف المتنازعة بالوصول إلى حل وسط عادل', value: 8, focus: 'تواصل، إقناع، اجتماعي' }, { text: 'إنشاء محتوى مرئي أو مسموع (فيديو، صوت) احترافي', value: 7, focus: 'إبداع، فنون، تصميم' }, { text: 'تنظيم وتخطيط رحلات أو فعاليات معقدة', value: 6, focus: 'تنظيم، إدارة، تخطيط' }],
        32: [{ text: 'كتابة الأكواد البرمجية الخالية من الأخطاء', value: 9, focus: 'تقنية، تحليل، إتقان' }, { text: 'إدارة اجتماع وتوجيه النقاش نحو هدف واضح', value: 8, focus: 'قيادة، إدارة، تواصل' }, { text: 'تصميم شعار أو واجهة مستخدم جميلة وعملية', value: 7, focus: 'إبداع، تصميم، فنون' }, { text: 'إصلاح عطل أو جهاز ميكانيكي/كهربائي', value: 6, focus: 'هندسة، تطبيق، إتقان' }],
        33: [{ text: 'لغات برمجة متخصصة (مثل Python أو Java أو R)', value: 9, focus: 'تقنية، برمجة، تحليل' }, { text: 'برامج إدارة المشاريع (مثل Asana أو Trello)', value: 8, focus: 'إدارة، تنظيم، تخطيط' }, { text: 'برامج التصميم الجرافيكي أو المونتاج (Adobe Suite)', value: 7, focus: 'تصميم، إبداع، فنون' }, { text: 'نظم إدارة علاقات العملاء (CRM)', value: 6, focus: 'تواصل، إدارة، مبيعات' }],
        34: [{ text: 'إعداد دراسة جدوى مفصلة أو نموذج أعمال', value: 9, focus: 'تحليل، منطق، تخطيط' }, { text: 'حل نزاع بين طرفين وإعادة العلاقات بينهما', value: 8, focus: 'اجتماعي، إرشاد، قيادة' }, { text: 'تصميم هوية بصرية كاملة لشركة جديدة', value: 7, focus: 'إبداع، تصميم، فنون' }, { text: 'تجميع أو تركيب قطعة أثاث أو معدة معقدة', value: 6, focus: 'تطبيق، إتقان، حركة' }],
        35: [{ text: 'تعديل وتطوير الأجهزة الإلكترونية أو الألعاب (Hacking)', value: 9, focus: 'تقنية، ابتكار، تحليل' }, { text: 'العمل كقائد فريق في الألعاب الجماعية أو الكشافة', value: 8, focus: 'قيادة، اجتماعي، تنظيم' }, { text: 'التصوير الفوتوغرافي أو الفيديو وإنتاج القصص', value: 7, focus: 'إبداع، فنون، تواصل' }, { text: 'التنظيم الدقيق لمجموعات الكتب أو التحف (Collection)', value: 6, focus: 'تنظيم، إدارة، دقة' }],
        36: [{ text: 'في مجال الهندسة أو علوم الحاسوب', value: 9, focus: 'تقنية، تحليل، هندسة' }, { text: 'في مجال الإدارة أو الموارد البشرية أو القيادة', value: 8, focus: 'إدارة، قيادة، تخطيط' }, { text: 'في مجال الفنون الجميلة أو التصميم الجرافيكي', value: 7, focus: 'إبداع، فنون، تصميم' }, { text: 'في مجال الإرشاد النفسي أو الاجتماعي', value: 6, focus: 'إرشاد، اجتماعي، تعليم' }],
        37: [{ text: 'أجيد تحليل جذور النزاع وأسباب سوء الفهم', value: 9, focus: 'تحليل، منطق، حل مشكلات' }, { text: 'أجيد تحويل النقاش إلى مسار إيجابي ومحايد للطرفين', value: 8, focus: 'تواصل، اجتماعي، إرشاد' }, { text: 'أجيد استخدام لغة الجسد والنبرة لتهدئة الأجواء', value: 7, focus: 'قيادة، إقناع، تواصل' }, { text: 'أجيد وضع قواعد واضحة لضمان عدم تكرار النزاع', value: 6, focus: 'تنظيم، إدارة، دقة' }],
        38: [{ text: 'القدرة على وضع خطط بعيدة المدى وتوزيع الموارد', value: 9, focus: 'تخطيط، إدارة، منطق' }, { text: 'القدرة على إلهام وتحفيز الفريق نحو رؤية مشتركة', value: 8, focus: 'قيادة، تواصل، اجتماعي' }, { text: 'القدرة على تفويض المهام ومراقبة الأداء بكفاءة', value: 7, focus: 'إدارة، تنظيم، دقة' }, { text: 'القدرة على اتخاذ قرار صعب وسريع تحت الضغط', value: 6, focus: 'قيادة، تحليل، مرونة' }],
        39: [{ text: 'أجيد تقسيم المشكلة إلى أجزاء أصغر ومنطقية', value: 9, focus: 'تحليل، منطق، تقنية' }, { text: 'أجيد البحث عن حلول من خارج الصندوق (Out of the Box)', value: 8, focus: 'ابتكار، إبداع، تصميم' }, { text: 'أجيد استشارة الأطراف المختلفة وتجميع المعلومات الدقيقة', value: 7, focus: 'تواصل، بحث، اجتماعي' }, { text: 'أجيد وضع قائمة بالحلول الممكنة وتقييمها رقمياً', value: 6, focus: 'تنظيم، تخطيط، دقة' }],
        40: [{ text: 'الابتكار في كتابة الأكواد والأنظمة البرمجية', value: 9, focus: 'تقنية، برمجة، ابتكار' }, { text: 'الإبداع في إنشاء المحتوى المرئي والمسموع (فيديو، صوت)', value: 8, focus: 'إبداع، فنون، تصميم' }, { text: 'القدرة على إيجاد طرق جديدة لتدريس مفاهيم صعبة', value: 7, focus: 'تعليم، إرشاد، تواصل' }, { text: 'القدرة على تصميم أزياء أو ديكورات فريدة', value: 6, focus: 'تصميم، إبداع، فنون' }],

        // ========== احتياجات العالم (World) - أمثلة موسعة لجميع الأسئلة الـ 80 ==========
        41: [
            { text: 'قلة الفرص التعليمية والتدريبية للشباب', value: 9, focus: 'تعليم، تنمية، إرشاد' },
            { text: 'قضايا البيئة وتغير المناخ وإدارة النفايات', value: 8, focus: 'بيئة، استدامة، علوم' },
            { text: 'غياب العدالة الاجتماعية والحقوق المدنية', value: 7, focus: 'عدالة، سياسة، قانون' },
            { text: 'نقص الدعم النفسي والوعي بالصحة العقلية', value: 6, focus: 'صحة نفسية، إرشاد، طب' }
        ],
        42: [{ text: 'حلول تقنية بسيطة للوصول إلى الخدمات الأساسية (تعليم، صحة)', value: 9, focus: 'تقنية، تعليم، صحة' }, { text: 'نشر الوعي الثقافي والتسامح الديني والاجتماعي', value: 8, focus: 'اجتماعي، ثقافة، إرشاد' }, { text: 'تطوير مصادر الطاقة المتجددة والمستدامة', value: 7, focus: 'بيئة، استدامة، هندسة' }, { text: 'بناء شبكات دعم نفسية واجتماعية قوية للمحتاجين', value: 6, focus: 'صحة نفسية، إنساني، اجتماعي' }],
        43: [{ text: 'التطورات في الذكاء الاصطناعي وتأثيرها على العمل', value: 9, focus: 'تقنية، تحليل، عمل' }, { text: 'جهود مكافحة الفقر والبطالة في الدول النامية', value: 8, focus: 'تنمية، اقتصادي، اجتماعي' }, { text: 'الحلول المعمارية والهندسية للمدن الذكية', value: 7, focus: 'هندسة، تصميم، تخطيط' }, { text: 'قضايا حماية حقوق المرأة والطفل', value: 6, focus: 'عدالة، اجتماعي، قانون' }],
        44: [{ text: 'إصلاح طرق تدريس العلوم والرياضيات لتصبح أكثر تطبيقاً', value: 9, focus: 'تعليم، تحليل، تقنية' }, { text: 'توفير تأمين صحي شامل وميسور التكلفة للجميع', value: 8, focus: 'صحة، اجتماعي، عدالة' }, { text: 'دمج التعليم الإلكتروني بشكل فعال في المدارس الحكومية', value: 7, focus: 'تعليم، تقنية، تنظيم' }, { text: 'زيادة برامج الإرشاد النفسي والمجتمعي في المدارس', value: 6, focus: 'صحة نفسية، إرشاد، اجتماعي' }],
        45: [{ text: 'توفير برامج تدريب مهني تقني مجانية', value: 9, focus: 'تقنية، تعليم، تنمية' }, { text: 'إنشاء مراكز لدعم ريادة الأعمال للمرأة والشباب', value: 8, focus: 'اقتصادي، قيادة، إدارة' }, { text: 'تطوير قوانين لحماية حقوق العمال واللاجئين', value: 7, focus: 'عدالة، اجتماعي، قانون' }, { text: 'توفير مساحات عامة آمنة للأنشطة الثقافية والفنية', value: 6, focus: 'ثقافة، فنون، اجتماعي' }],
        46: [{ text: 'صعوبة الوصول إلى معلومات موثوقة وغير منحازة', value: 9, focus: 'بحث، تحليل، إعلام' }, { text: 'نقص الدعم الاجتماعي للأسر ذات الدخل المحدود', value: 8, focus: 'اجتماعي، إنساني، تنمية' }, { text: 'الضغط النفسي الناتج عن المقارنة والظهور على السوشيال ميديا', value: 7, focus: 'صحة نفسية، إرشاد، تواصل' }, { text: 'نقص المساحات الخضراء والترفيهية في المدن المكتظة', value: 6, focus: 'بيئة، تصميم، صحة' }],
        47: [{ text: 'غياب البيانات الدقيقة والمحايدة عن القضايا الاقتصادية والاجتماعية', value: 9, focus: 'تحليل، بحث، عدالة' }, { text: 'قضايا الفساد وسوء الإدارة في المؤسسات العامة', value: 8, focus: 'قيادة، عدالة، قانون' }, { text: 'عدم المساواة في الحصول على فرص العمل والتعليم', value: 7, focus: 'تنمية، اجتماعي، عدالة' }, { text: 'قضايا الإدمان والمخدرات وتأثيرها على الأسر', value: 6, focus: 'صحة نفسية، إرشاد، اجتماعي' }],
        48: [{ text: 'التكنولوجيا: الحاجة لتطوير تطبيقات لحل المشكلات المحلية', value: 9, focus: 'تقنية، ابتكار، تطبيق' }, { text: 'البيئة: الحاجة إلى حلول لإعادة تدوير البلاستيك والنفايات الصلبة', value: 8, focus: 'بيئة، استدامة، هندسة' }, { text: 'الزراعة: الحاجة إلى تقنيات توفير المياه في الزراعة الصحراوية', value: 7, focus: 'علوم، بيئة، تقنية' }, { text: 'الصحة: الحاجة إلى أنظمة رقمية لتحسين إدارة المستشفيات', value: 6, focus: 'تنظيم، إدارة، تقنية' }],
        49: [{ text: 'الحاجة إلى حلول لتقليل استهلاك الطاقة في المنازل والصناعة', value: 9, focus: 'بيئة، هندسة، استدامة' }, { text: 'الحاجة إلى حملات توعية بخطر النفايات البلاستيكية', value: 8, focus: 'اجتماعي، إرشاد، بيئة' }, { text: 'الحاجة إلى زراعة الغابات واستصلاح الأراضي الجافة', value: 7, focus: 'علوم، زراعة، بيئة' }, { text: 'الحاجة إلى أنظمة لجمع وتصنيف البيانات البيئية بدقة', value: 6, focus: 'تحليل، تقنية، بحث' }],
        50: [{ text: 'توفير منصات للتدريب المهني والتقني المتخصص', value: 9, focus: 'تعليم، تقنية، تنمية' }, { text: 'توفير فرص عمل مرنة وعن بعد', value: 8, focus: 'اقتصادي، عمل، إدارة' }, { text: 'توفير مساحات آمنة للتعبير عن الذات والإبداع الفني', value: 7, focus: 'إبداع، فنون، اجتماعي' }, { text: 'توفير دعم نفسي وإرشادي لمواجهة ضغوط الحياة الحديثة', value: 6, focus: 'صحة نفسية، إرشاد، تعليم' }],
        51: [{ text: 'دمج الذكاء الاصطناعي والأتمتة في المناهج', value: 9, focus: 'تقنية، تعليم، ابتكار' }, { text: 'تطوير مهارات التفكير النقدي وحل المشكلات بدلاً من التلقين', value: 8, focus: 'تحليل، تعليم، منطق' }, { text: 'زيادة التركيز على التعليم الفني والمهني العملي', value: 7, focus: 'تطبيق، إتقان، تعليم' }, { text: 'تقليل عدد الطلاب في الصفوف لزيادة جودة التفاعل', value: 6, focus: 'تنظيم، إدارة، اجتماعي' }],
        52: [{ text: 'نشر الوعي بأهمية الصحة العقلية والعلاج النفسي', value: 9, focus: 'صحة نفسية، إرشاد، تعليم' }, { text: 'تطوير لقاحات وعلاجات للأمراض المزمنة (السكري، السرطان)', value: 8, focus: 'علوم، بحث، صحة' }, { text: 'توفير الرعاية الصحية الوقائية والابتعاد عن العلاج فقط', value: 7, focus: 'صحة، اجتماعي، تنظيم' }, { text: 'تطبيق أنظمة حوسبة سحابية لإدارة السجلات الطبية', value: 6, focus: 'تقنية، إدارة، صحة' }],
        53: [{ text: 'دعم الصادرات وتطوير الصناعات المحلية التنافسية', value: 9, focus: 'اقتصادي، إدارة، تخطيط' }, { text: 'تسهيل شروط القروض للمشاريع الصغيرة والناشئة', value: 8, focus: 'ريادة، اقتصادي، إدارة' }, { text: 'التركيز على قطاعات الخدمات والسياحة الراقية', value: 7, focus: 'تواصل، إدارة، اقتصادي' }, { text: 'بناء شراكات اقتصادية قوية مع دول الجوار', value: 6, focus: 'وعي عالمي، قيادة، تخطيط' }],
        54: [{ text: 'أتمتة العمليات الحكومية والخدمات العامة للمواطنين', value: 9, focus: 'تقنية، تنظيم، إدارة' }, { text: 'تطوير أنظمة لترجمة اللغات واللهجات المحلية بدقة', value: 8, focus: 'تواصل، تقنية، تعليم' }, { text: 'زيادة أمان الإنترنت والبيانات الشخصية ضد الاختراق', value: 7, focus: 'تقنية، تحليل، أمن' }, { text: 'إنشاء منصات تعليمية تفاعلية ومجانية للعلوم', value: 6, focus: 'تعليم، تقنية، إبداع' }],
        55: [{ text: 'تطبيق معايير استدامة صارمة في الإنتاج والتصنيع', value: 9, focus: 'بيئة، إدارة، استدامة' }, { text: 'زيادة الشفافية والإفصاح عن البيانات المالية والإدارية', value: 8, focus: 'عدالة، إدارة، منطق' }, { text: 'ضمان التنوع والإنصاف في التوظيف والقيادة', value: 7, focus: 'اجتماعي، عدالة، قيادة' }, { text: 'تشجيع العمل عن بعد والمرونة في بيئات العمل', value: 6, focus: 'إدارة، تنظيم، عمل' }],
        56: [{ text: 'الحفاظ على التراث المادي والثقافي من الاندثار', value: 9, focus: 'ثقافة، بحث، تصميم' }, { text: 'دعم وتشجيع الفنانين والمبدعين الشباب مادياً', value: 8, focus: 'إبداع، فنون، اجتماعي' }, { text: 'نشر قصص النجاح المحلية الملهمة في الخارج', value: 7, focus: 'تواصل، إعلام، قيادة' }, { text: 'تعليم الأطفال حول تاريخ المنطقة وهويتها الوطنية', value: 6, focus: 'تعليم، ثقافة، إرشاد' }],
        57: [{ text: 'تطوير تطبيقات تقنية لمساعدتهم في التنقل والتعلم', value: 9, focus: 'تقنية، تصميم، عدالة' }, { text: 'تعديل البنية التحتية للمباني لتكون ميسرة الوصول للجميع', value: 8, focus: 'هندسة، تصميم، عدالة' }, { text: 'توفير فرص عمل مرنة تتناسب مع احتياجاتهم', value: 7, focus: 'عمل، عدالة، إدارة' }, { text: 'إنشاء برامج تدريب مجتمعية لرفع الوعي حول حقوقهم', value: 6, focus: 'اجتماعي، تعليم، إرشاد' }],
        58: [{ text: 'ضعف التواصل والترابط الأسري بسبب الانشغال', value: 9, focus: 'اجتماعي، إرشاد، تواصل' }, { text: 'مشكلة التنمر الإلكتروني في المدارس والجامعات', value: 8, focus: 'صحة نفسية، تعليم، عدالة' }, { text: 'زيادة نسبة الطلاق والمشكلات الزوجية', value: 7, focus: 'إرشاد، اجتماعي، تحليل نفسي' }, { text: 'التأثير السلبي لوسائل التواصل الاجتماعي على الأبناء', value: 6, focus: 'إعلام، تعليم، تواصل' }],
        59: [{ text: 'الاعتماد على التقنيات الحديثة في الري وتوفير المياه', value: 9, focus: 'تقنية، علوم، بيئة' }, { text: 'تطوير سلالات نباتية مقاومة للجفاف والأمراض', value: 8, focus: 'علوم، بحث، بيئة' }, { text: 'إنشاء أسواق مباشرة بين المزارعين والمستهلكين', value: 7, focus: 'اقتصادي، تنظيم، إدارة' }, { text: 'توفير تدريب على أساليب الزراعة المستدامة', value: 6, focus: 'تعليم، بيئة، تطبيق' }],
        60: [{ text: 'توفير المأوى والمساعدات الأساسية للاجئين', value: 9, focus: 'إنساني، اجتماعي، عدالة' }, { text: 'قضايا عمالة الأطفال والفقر المدقع', value: 8, focus: 'عدالة، اجتماعي، تنمية' }, { text: 'غياب التعليم للأطفال في مناطق النزاع', value: 7, focus: 'تعليم، إنساني، عدالة' }, { text: 'نقص الرعاية الصحية للمسنين والمعاقين', value: 6, focus: 'صحة، اجتماعي، إنساني' }],

        // ========== ما يُدفع لك مقابله (Paid) - أمثلة موسعة لجميع الأسئلة الـ 80 ==========
        61: [
            { text: 'المهارات التقنية (مثل البرمجة، تحليل البيانات، الأمن السيبراني)', value: 9, focus: 'تقنية، برمجة، تحليل' },
            { text: 'مهارات الإدارة والقيادة ومهارات التفاوض', value: 8, focus: 'إدارة، قيادة، أعمال' },
            { text: 'مهارات التسويق الرقمي وإنشاء المحتوى والترويج', value: 7, focus: 'تسويق، إبداع، تواصل' },
            { text: 'مهارات اللغات الأجنبية والترجمة الفورية', value: 6, focus: 'لغات، ترجمة، تواصل' }
        ],
        62: [{ text: 'قطاع التكنولوجيا المالية (FinTech) والخدمات الرقمية', value: 9, focus: 'تقنية، اقتصادي، ابتكار' }, { text: 'قطاع الطاقة المتجددة والاستدامة البيئية', value: 8, focus: 'بيئة، هندسة، اقتصادي' }, { text: 'قطاع الرعاية الصحية والخدمات الطبية المتخصصة', value: 7, focus: 'صحة، علوم، عمل' }, { text: 'قطاع صناعة المحتوى والتسويق الرقمي', value: 6, focus: 'تسويق، إبداع، تواصل' }],
        63: [{ text: 'الوظائف التقنية المتخصصة (Data Science, Cloud Computing)', value: 9, focus: 'تقنية، تحليل، عمل' }, { text: 'الوظائف الإدارية العليا في الشركات الكبيرة (COO, CEO)', value: 8, focus: 'قيادة، إدارة، اقتصادي' }, { text: 'الاستشارات الهندسية في المشاريع الكبرى', value: 7, focus: 'هندسة، تخطيط، عمل' }, { text: 'العمل الحر في مجال التصميم أو الترجمة (Freelance)', value: 6, focus: 'إبداع، عمل حر، تواصل' }],
        64: [{ text: 'خدمات التوصيل واللوجستيات الرقمية', value: 9, focus: 'تنظيم، تقنية، عمل' }, { text: 'خدمات التدريب والإرشاد الشخصي والمهني', value: 8, focus: 'تعليم، إرشاد، اجتماعي' }, { text: 'خدمات الصيانة والتركيب المتخصصة (أجهزة، سيارات)', value: 7, focus: 'تطبيق، إتقان، عمل' }, { text: 'منتجات غذائية عضوية ومحلية (Organic/Local Food)', value: 6, focus: 'بيئة، عمل، صحة' }],
        65: [{ text: 'منصات التجارة الإلكترونية التي تبيع منتجات محلية', value: 9, focus: 'تقنية، تسويق، ريادة' }, { text: 'تطبيقات لحجز المواعيد والخدمات الطبية أو التعليمية', value: 8, focus: 'تنظيم، تقنية، صحة' }, { text: 'مشاريع إعادة التدوير والمعالجة البيئية للنفايات', value: 7, focus: 'بيئة، هندسة، ريادة' }, { text: 'خدمات التدريب على المهارات الناعمة (Soft Skills)', value: 6, focus: 'تعليم، إرشاد، اجتماعي' }],
        66: [{ text: 'مجالات الصيانة الفنية والتركيبات الهندسية', value: 9, focus: 'هندسة، تطبيق، عمل' }, { text: 'مجالات الرعاية الصحية والصيدلة والتمريض', value: 8, focus: 'صحة، علوم، عمل' }, { text: 'مجالات التعليم والتدريب (خاصة التقني)', value: 7, focus: 'تعليم، إرشاد، عمل' }, { text: 'مجالات الأمن والحماية السيبرانية', value: 6, focus: 'تقنية، تحليل، أمن' }],
        67: [{ text: 'تطوير تطبيقات الهاتف المحمول (iOS/Android)', value: 9, focus: 'تقنية، برمجة، ابتكار' }, { text: 'إدارة قواعد البيانات الكبيرة (Big Data)', value: 8, focus: 'تحليل، تقنية، منطق' }, { text: 'الأمن السيبراني وحماية البنية التحتية', value: 7, focus: 'تقنية، تحليل، أمن' }, { text: 'التسويق باستخدام الذكاء الاصطناعي (AI Marketing)', value: 6, focus: 'تسويق، تقنية، إبداع' }],
        68: [{ text: 'مطور برمجيات (Software Developer)', value: 9, focus: 'تقنية، برمجة، عمل حر' }, { text: 'مستشار إداري دولي (Management Consultant)', value: 8, focus: 'إدارة، قيادة، عمل حر' }, { text: 'مصمم جرافيك أو واجهات مستخدم (UI/UX)', value: 7, focus: 'تصميم، إبداع، عمل حر' }, { text: 'مترجم فوري أو كاتب محتوى متخصص (Technical Writer)', value: 6, focus: 'تواصل، لغات، بحث' }],
        69: [{ text: 'مشاريع البنية التحتية والمواصلات الذكية', value: 9, focus: 'هندسة، تخطيط، تقنية' }, { text: 'مشاريع الطاقة الشمسية وطاقة الرياح', value: 8, focus: 'بيئة، هندسة، استدامة' }, { text: 'دعم القطاع التعليمي الرقمي', value: 7, focus: 'تعليم، تقنية، تنمية' }, { text: 'تطوير المناطق السياحية والآثار', value: 6, focus: 'ثقافة، سياحة، إدارة' }],
        70: [{ text: 'تطبيقات دليل سياحي تعتمد على الواقع المعزز (AR)', value: 9, focus: 'تقنية، إبداع، سياحة' }, { text: 'خدمات تنظيم جولات سياحة بيئية ومغامرات', value: 8, focus: 'بيئة، تنظيم، سياحة' }, { text: 'تطوير تجارب ثقافية وورش عمل فنية للسياح', value: 7, focus: 'ثقافة، فنون، تواصل' }, { text: 'أنظمة حجز متكاملة وذكية للفنادق والمطاعم', value: 6, focus: 'تنظيم، تقنية، إدارة' }],
        71: [{ text: 'ورش صيانة الأجهزة الإلكترونية والهواتف', value: 9, focus: 'تقنية، تطبيق، عمل' }, { text: 'خدمات التدريب على برامج الحاسوب الأساسية', value: 8, focus: 'تعليم، تقنية، عمل' }, { text: 'متجر صغير لبيع المنتجات المصنوعة يدوياً (حرف)', value: 7, focus: 'إبداع، فنون، تسويق' }, { text: 'مركز استشارات اجتماعية وأسرية بسيطة', value: 6, focus: 'إرشاد، اجتماعي، عمل' }],
        72: [{ text: 'البرمجة والتطوير السريع للأنظمة (Agile Development)', value: 9, focus: 'تقنية، برمجة، إتقان' }, { text: 'التسويق الرقمي وإدارة حسابات التواصل الاحترافية', value: 8, focus: 'تسويق، إبداع، تواصل' }, { text: 'مهارات العرض والإقناع وبناء العلاقات مع العملاء', value: 7, focus: 'تواصل، إقناع، قيادة' }, { text: 'مهارات التحليل المالي والمحاسبة الإدارية', value: 6, focus: 'تحليل، منطق، إدارة' }],
        73: [{ text: 'التخصص في الرعاية المنزلية لكبار السن أو المرضى', value: 9, focus: 'صحة، إنساني، عمل' }, { text: 'تطوير تطبيقات لتتبع الحالات المزمنة', value: 8, focus: 'تقنية، صحة، تحليل' }, { text: 'العلاج الطبيعي والتأهيل الحركي', value: 7, focus: 'صحة، تطبيق، عمل' }, { text: 'الإرشاد الغذائي والتغذية العلاجية', value: 6, focus: 'صحة، تعليم، إرشاد' }],
        74: [{ text: 'الدروس الخصوصية في مواد العلوم والرياضيات المتقدمة', value: 9, focus: 'تعليم، تحليل، عمل' }, { text: 'التدريب على مهارات القيادة وريادة الأعمال للشباب', value: 8, focus: 'قيادة، تعليم، إدارة' }, { text: 'ورش عمل لتعليم التصميم الجرافيكي أو المونتاج', value: 7, focus: 'إبداع، تصميم، تعليم' }, { text: 'الخدمات الإرشادية للقبول في الجامعات الخارجية', value: 6, focus: 'تواصل، إرشاد، بحث' }],
        75: [{ text: 'خدمات التدقيق اللغوي والتحرير للمؤسسات', value: 9, focus: 'تحليل، لغات، عمل' }, { text: 'خدمات تنظيم المؤتمرات والفعاليات الكبيرة', value: 8, focus: 'تنظيم، إدارة، قيادة' }, { text: 'خدمات تصميم المواقع البسيطة للشركات الصغيرة', value: 7, focus: 'تصميم، تقنية، عمل' }, { text: 'خدمات الاستشارات البيئية (Energy Audit)', value: 6, focus: 'بيئة، تحليل، عمل' }],
        76: [{ text: 'هندسة الاتصالات وشبكات الألياف البصرية', value: 9, focus: 'تقنية، هندسة، تحليل' }, { text: 'الهندسة المعمارية المستدامة وتصميم المباني الخضراء', value: 8, focus: 'بيئة، تصميم، هندسة' }, { text: 'هندسة الطرق والمواصلات العامة', value: 7, focus: 'تخطيط، هندسة، إدارة' }, { text: 'هندسة الطاقة الشمسية والحرارية', value: 6, focus: 'هندسة، علوم، استدامة' }],
        77: [{ text: 'خدمات كتابة خطط الأعمال ودراسات الجدوى المالية', value: 9, focus: 'تحليل، إدارة، اقتصادي' }, { text: 'خدمات بناء الهوية البصرية والتسويق الأولي', value: 8, focus: 'تصميم، إبداع، تسويق' }, { text: 'خدمات الإرشاد القانوني والتسجيل للشركات', value: 7, focus: 'قانون، إدارة، تنظيم' }, { text: 'خدمات دعم الموارد البشرية والتوظيف', value: 6, focus: 'إدارة، اجتماعي، تنظيم' }],
        78: [{ text: 'صناعة محتوى تعليمي متخصص في مجالات تقنية', value: 9, focus: 'تعليم، تقنية، إبداع' }, { text: 'إدارة حملات المؤثرين والتسويق عبر الفيديو', value: 8, focus: 'تسويق، تواصل، إبداع' }, { text: 'كتابة المقالات التحليلية والآراء الاقتصادية', value: 7, focus: 'تحليل، بحث، إعلام' }, { text: 'التغطية المباشرة للأحداث الاجتماعية والإنسانية', value: 6, focus: 'إنساني، تواصل، إعلام' }],
        79: [{ text: 'خدمات التحليل المالي الشخصي وإدارة الديون', value: 9, focus: 'تحليل، منطق، إدارة' }, { text: 'خدمات تأسيس الشركات وإدارة المحافظ للمستثمرين الصغار', value: 8, focus: 'ريادة، إدارة، اقتصادي' }, { text: 'تطبيقات للتوفير والميزانية الشهرية', value: 7, focus: 'تقنية، تنظيم، إدارة' }, { text: 'الإرشاد بشأن القروض العقارية وشراء الأصول', value: 6, focus: 'تواصل، إرشاد، اقتصادي' }],
        80: [{ text: 'مشاريع دعم التعليم المهني والتقني للشباب', value: 9, focus: 'تعليم، تقنية، تنمية' }, { text: 'مشاريع التمكين الاقتصادي للمرأة وريادة الأعمال النسوية', value: 8, focus: 'اجتماعي، قيادة، ريادة' }, { text: 'مشاريع إعادة تدوير المياه والموارد الطبيعية', value: 7, focus: 'بيئة، استدامة، هندسة' }, { text: 'مشاريع دعم الصحة النفسية للأطفال واليافعين', value: 6, focus: 'صحة نفسية، إنساني، اجتماعي' }],
    };

    // ==================== دوال التطبيق الرئيسية ====================
    
    function startTest() {
        document.getElementById('start-screen').classList.remove('active');
        document.getElementById('question-screen').classList.add('active');
        appState.currentQuestion = 0;
        updateQuestion();
    }

    function updateQuestion() {
        // حماية من تجاوز الحدود
        if (appState.currentQuestion >= questions.length || appState.currentQuestion < 0) return;
        
        const question = questions[appState.currentQuestion];
        const totalQuestions = questions.length;
        
        // تحديث التقدم
        const progress = ((appState.currentQuestion + 1) / totalQuestions) * 100;
        document.getElementById('progress-fill').style.width = `${progress}%`;
        document.getElementById('progress-text').textContent = `السؤال ${appState.currentQuestion + 1} من ${totalQuestions}`;
        
        // تحديث نص السؤال والفئة
        document.getElementById('question-text').textContent = question.text;
        document.getElementById('question-hint').textContent = question.hint;
        
        const categoryNames = { 'passion': 'الشغف', 'skill': 'المهارة', 'world': 'احتياجات العالم', 'paid': 'المهنة والدخل' };
        const categoryColors = { 'passion': 'tag-passion', 'skill': 'tag-skill', 'world': 'tag-world', 'paid': 'tag-paid' };
        
        const categoryTag = document.getElementById('question-category');
        categoryTag.textContent = categoryNames[question.category];
        categoryTag.className = `category-tag ${categoryColors[question.category]}`;
        
        document.getElementById('category-text').textContent = categoryNames[question.category];
        
        // توليد الخيارات
        generateOptions(question.id);
        
        // تحديث أزرار التنقل
        document.getElementById('prev-btn').disabled = appState.currentQuestion === 0;
        document.getElementById('next-btn').disabled = !appState.answers[question.id];
    }

    function generateOptions(questionId) {
        const optionsContainer = document.getElementById('options-container');
        optionsContainer.innerHTML = '';
        
        const options = questionOptions[questionId];
        
        if (!options) {
            optionsContainer.innerHTML = '<p>حدث خطأ: لم يتم العثور على خيارات للسؤال.</p>';
            return;
        }

        options.forEach((option, index) => {
            const optionElement = document.createElement('div');
            optionElement.className = 'option-card';
            optionElement.innerHTML = `
                <div class="option-number">${index + 1}</div>
                <div class="option-text">${option.text}</div>
            `;
            
            optionElement.addEventListener('click', () => {
                // إزالة التحديد من جميع الخيارات
                document.querySelectorAll('.option-card').forEach(card => {
                    card.classList.remove('selected');
                });
                
                // تحديد الخيار الحالي
                optionElement.classList.add('selected');
                
                // حفظ الإجابة (القيمة ونقطة التركيز)
                appState.answers[questions[appState.currentQuestion].id] = { 
                    value: option.value,
                    focus: option.focus 
                };
                
                // تفعيل زر التالي
                document.getElementById('next-btn').disabled = false;
            });
            
            // تحديد الإجابة السابقة إن وجدت
            if (appState.answers[questionId] && appState.answers[questionId].value === option.value) {
                optionElement.classList.add('selected');
                // تفعيل زر التالي في حال الرجوع للسؤال
                document.getElementById('next-btn').disabled = false; 
            }
            
            optionsContainer.appendChild(optionElement);
        });
        
        // التأكد من حالة زر التالي عند تحميل السؤال
        document.getElementById('next-btn').disabled = !appState.answers[questionId];
    }

    function nextQuestion() {
        const question = questions[appState.currentQuestion];
        
        if (!appState.answers[question.id] || !appState.answers[question.id].value) {
            showNotification('يرجى اختيار إجابة قبل المتابعة');
            return;
        }
        
        if (appState.currentQuestion < questions.length - 1) {
            appState.currentQuestion++;
            updateQuestion();
        } else {
            // انتهاء الأسئلة، الانتقال إلى شاشة التحميل
            document.getElementById('question-screen').classList.remove('active');
            document.getElementById('loading-screen').classList.add('active');
            
            // حساب النتائج بعد فترة بسيطة
            setTimeout(calculateResults, 2000);
        }
    }

    function prevQuestion() {
        if (appState.currentQuestion > 0) {
            appState.currentQuestion--;
            updateQuestion();
        }
    }
    
    // ==================== دوال حساب وعرض النتائج ====================

    function calculateResults() {
        appState.scores = { passion: 0, skill: 0, world: 0, paid: 0 };
        appState.strengths = { passion: {}, skill: {}, world: {}, paid: {} };

        questions.forEach(question => {
            const answer = appState.answers[question.id];
            if (answer && answer.value) {
                appState.scores[question.category] += answer.value;
                
                // تجميع نقاط القوة (Focus)
                const focus = answer.focus;
                appState.strengths[question.category][focus] = 
                    (appState.strengths[question.category][focus] || 0) + answer.value;
            }
        });
        
        // تحويل النقاط إلى نسب مئوية (الحد الأقصى 20 سؤال * 9 نقاط = 180)
        Object.keys(appState.scores).forEach(category => {
            appState.scores[category] = Math.min(100, Math.round((appState.scores[category] / 180) * 100));
        });
        
        // حساب الإيكيغاي الكلي
        const totalScore = (appState.scores.passion + appState.scores.skill + 
                          appState.scores.world + appState.scores.paid) / 4;
        appState.scores.ikigai = Math.round(totalScore);
        
        determineStrengths();
        showResults();
    }

    function determineStrengths() {
        Object.keys(appState.strengths).forEach(category => {
            const focusMap = appState.strengths[category];
            const sortedStrengths = Object.entries(focusMap)
                .sort(([, a], [, b]) => b - a) // ترتيب تنازلي حسب القيمة
                .slice(0, 4) // أخذ أعلى 4 فقط
                .map(([focus]) => focus); 
            
            // التأكد من وجود 4 نقاط قوة (للتعبئة الجمالية)
            while (sortedStrengths.length < 4) {
                 sortedStrengths.push('مجال جيد يحتاج لتطوير');
            }
            
            appState.strengths[category] = sortedStrengths;
        });
    }

    function showResults() {
        document.getElementById('loading-screen').classList.remove('active');
        document.getElementById('results-screen').classList.add('active');
        
        updateBasicResults();
        generateJobRecommendations();
    }

    function updateBasicResults() {
        // تحديث النسب المئوية
        animateCounter('ikigai-score', appState.scores.ikigai);
        animateCounter('passion-score', appState.scores.passion, '%');
        animateCounter('skill-score', appState.scores.skill, '%');
        animateCounter('world-score', appState.scores.world, '%');
        animateCounter('paid-score', appState.scores.paid, '%');
        
        // تحديث النصوص الوصفية
        document.getElementById('ikigai-label').textContent = getIkigaiLabel(appState.scores.ikigai);
        document.getElementById('passion-text').textContent = getCategoryText('passion', appState.scores.passion);
        document.getElementById('skill-text').textContent = getCategoryText('skill', appState.scores.skill);
        document.getElementById('world-text').textContent = getCategoryText('world', appState.scores.world);
        document.getElementById('paid-text').textContent = getCategoryText('paid', appState.scores.paid);
        
        // تحديث نقاط القوة
        updateStrengthsList('passion-strengths', appState.strengths.passion);
        updateStrengthsList('skill-strengths', appState.strengths.skill);
        updateStrengthsList('world-strengths', appState.strengths.world);
        updateStrengthsList('paid-strengths', appState.strengths.paid);
    }
    
    // دوال مساعدة للنتائج
    function animateCounter(id, targetValue, suffix = '') {
        const element = document.getElementById(id);
        let start = 0;
        const duration = 1500;
        const step = targetValue / (duration / 10);
        
        const timer = setInterval(() => {
            start += step;
            if (start >= targetValue) {
                start = targetValue;
                clearInterval(timer);
            }
            element.textContent = Math.round(start) + suffix;
        }, 10);
    }

    function getIkigaiLabel(score) {
        if (score >= 90) return "إيكيغاي متوازن ومُكتمل: أنت على مسار واضح وهدفك محدد.";
        if (score >= 70) return "إيكيغاي قوي: لديك فهم جيد لذاتك ومسار عملك، ولكن هناك مجال للنمو.";
        if (score >= 50) return "إيكيغاي متوسط: بدأت نقاط القوة بالظهور، تحتاج لتركيز جهودك في المجالات الأضعف.";
        return "إيكيغاي يحتاج للبناء: لديك شغف أو مهارة قوية، ركز على ربطها باحتياجات العالم والدخل.";
    }

    function getCategoryText(category, score) {
        if (score >= 80) return "مستوى عالٍ جداً: هذا مجال قوة رئيسي لديك، استثمر فيه بقوة.";
        if (score >= 60) return "مستوى جيد: لديك قدرة ممتازة، لكن بعض الجوانب تحتاج للتطوير لتحقيق الامتياز.";
        if (score >= 40) return "مستوى متوسط: هذا المجال يحتاج إلى جهد إضافي لتطويره وربطه ببقية فئات الإيكيغاي.";
        return "مستوى منخفض: تحتاج إلى استكشاف هذا الجانب والعمل على اكتساب المعرفة والخبرة فيه.";
    }

    function updateStrengthsList(id, strengths) {
        const list = document.getElementById(id);
        list.innerHTML = '';
        strengths.forEach(strength => {
            const li = document.createElement('li');
            li.textContent = strength;
            list.appendChild(li);
        });
    }

    // ==================== دوال التوصيات (حذف الوظائف المالية) ====================

    function getDominantCategory() {
        const scores = appState.scores;
        let maxScore = -1;
        let dominant = 'passion';
        
        for (const [category, score] of Object.entries(scores)) {
            if (category !== 'ikigai' && score > maxScore) {
                maxScore = score;
                dominant = category;
            }
        }
        return dominant;
    }

    function generateJobRecommendations() {
        const jobsGrid = document.getElementById('jobs-grid');
        jobsGrid.innerHTML = '';
        
        const dominantCategory = getDominantCategory();
        const recommendedJobs = getRecommendedJobs(dominantCategory);
        
        // عرض التوصيات
        recommendedJobs.forEach(job => {
            const jobCard = document.createElement('div');
            jobCard.className = 'job-card';
            jobCard.innerHTML = `
                <div class="job-title">${job.title}</div>
                <p>${job.description}</p>
                <div class="job-salary">متوسط الراتب المتوقع: ${job.salary}</div>
                <div class="job-links">
                    <a href="${job.platforms[0].link}" target="_blank" class="job-link">${job.platforms[0].name}</a>
                </div>
            `;
            jobsGrid.appendChild(jobCard);
        });
    }

    function getRecommendedJobs(dominantCategory) {
        // قائمة الوظائف المقترحة بناءً على الفئة المهيمنة (تم حذف المستشار المالي والمدير المالي)
        const jobCategories = {
            passion: [
                {
                    title: 'مدرب ومُحفّز (Life/Career Coach)',
                    description: 'توجيه الأفراد لمساراتهم، يدمج الشغف بالتحليل النفسي والإرشاد. مثالي لـ "إرشاد، تحليل نفسي، تعليم".',
                    salary: '800-1500 دينار',
                    platforms: [{ name: 'LinkedIn Job Search', link: 'https://www.linkedin.com/jobs/search/?keywords=Career%20Coach%20Jordan' }]
                },
                {
                    title: 'صانع محتوى إبداعي وكاتب سيناريو',
                    description: 'إنتاج محتوى مرئي أو مكتوب يلهم ويُعلّم، يركز على "إبداع، فنون، تصميم".',
                    salary: '600-1200 دينار',
                    platforms: [{ name: 'Indeed Job Search', link: 'https://jo.indeed.com/jobs?q=Content+Creator' }]
                }
            ],
            skill: [
                {
                    title: 'مهندس برمجيات متقدم (Senior Developer)',
                    description: 'تطوير أنظمة تقنية معقدة، يعتمد على قوة "تقنية، برمجة، تحليل" لديك.',
                    salary: '1200-2500 دينار',
                    platforms: [{ name: 'LinkedIn Job Search', link: 'https://www.linkedin.com/jobs/search/?keywords=Software%20Engineer%20Jordan' }]
                },
                {
                    title: 'مدير مشاريع (Project Manager)',
                    description: 'تخطيط وتنظيم وقيادة فرق العمل نحو إنجاز الأهداف، مثالي لـ "إدارة، تخطيط، تنظيم".',
                    salary: '1000-2000 دينار',
                    platforms: [{ name: 'Indeed Job Search', link: 'https://jo.indeed.com/jobs?q=Project+Manager' }]
                }
            ],
            world: [
                {
                    title: 'أخصائي بيئة واستدامة (Sustainability Specialist)',
                    description: 'العمل على مبادرات لحل قضايا البيئة واستخدام الطاقة المستدامة، يركز على "بيئة، استدامة، علوم".',
                    salary: '700-1400 دينار',
                    platforms: [{ name: 'LinkedIn Job Search', link: 'https://www.linkedin.com/jobs/search/?keywords=Sustainability%20Jordan' }]
                },
                {
                    title: 'منسق مشاريع تنموية في منظمة دولية',
                    description: 'تخطيط وتطبيق برامج تخدم المجتمع (تعليم، صحة)، يعتمد على "تعليم، تنمية، إرشاد".',
                    salary: '900-1800 دينار',
                    platforms: [{ name: 'ReliefWeb Jobs', link: 'https://reliefweb.int/jobs?country=Jordan' }]
                }
            ],
            paid: [
                {
                    title: 'مسوق رقمي متخصص (Digital Marketing Specialist)',
                    description: 'إدارة الحملات الإعلانية وتحليل أداء التسويق عبر الإنترنت، يركز على "تسويق، إبداع، تواصل".',
                    salary: '800-1700 دينار',
                    platforms: [{ name: 'LinkedIn Job Search', link: 'https://www.linkedin.com/jobs/search/?keywords=Digital%20Marketing%20Jordan' }]
                },
                {
                    title: 'أخصائي أمن سيبراني (Cyber Security Specialist)',
                    description: 'مهنة مطلوبة ذات دخل عالٍ لحماية البيانات والأنظمة، تعتمد على "تقنية، تحليل، أمن".',
                    salary: '1100-2200 دينار',
                    platforms: [{ name: 'Indeed Job Search', link: 'https://jo.indeed.com/jobs?q=Cyber+Security' }]
                }
            ]
        };
        
        // إضافة وظيفة توازن عامة إذا كان الإيكيغاي عالي
        if (appState.scores.ikigai >= 75) {
             jobCategories[dominantCategory].unshift({
                title: 'ريادي أعمال (Entrepreneur)',
                description: 'إنشاء مشروع يجمع بين جميع نقاط قوتك الأربع لتلبية حاجة السوق.',
                salary: 'غير محدود',
                platforms: [{ name: 'دعم ريادة الأعمال', link: 'https://www.intaj.net/' }]
            });
        }

        return jobCategories[dominantCategory];
    }

    // ==================== دوال واجهة المستخدم الأخرى ====================

    function restartTest() {
        appState.currentQuestion = 0;
        appState.answers = {};
        appState.scores = { passion: 0, skill: 0, world: 0, paid: 0 };
        document.getElementById('results-screen').classList.remove('active');
        document.getElementById('start-screen').classList.add('active');
    }

    function showNotification(message) {
        const notification = document.getElementById('notification');
        notification.textContent = message;
        notification.style.display = 'block';
        setTimeout(() => {
            notification.style.display = 'none';
        }, 3000);
    }

    // ==================== تهيئة التطبيق (التصحيح الرئيسي هنا) ====================
    document.addEventListener('DOMContentLoaded', function() {
        // **التصحيح: ربط زر "ابدأ الاختبار الآن" بالدالة عند تحميل الصفحة**
        const startButton = document.getElementById('start-button');
        if (startButton) {
            startButton.addEventListener('click', startTest);
        }
        
        // ربط أزرار التنقل بالدوال
        document.getElementById('prev-btn').addEventListener('click', prevQuestion);
        document.getElementById('next-btn').addEventListener('click', nextQuestion);
    });

</script>
</body>
</html>
