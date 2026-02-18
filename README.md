<!DOCTYPE html>
<html lang="ar" dir="rtl" class="h-full">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>خطة نجمات الانضباط - رمضان</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="/_sdk/data_sdk.js"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">
  <style>
    * { font-family: 'Tajawal', sans-serif; }
    .star-icon { transition: all 0.3s ease; }
    .star-icon:hover { transform: scale(1.2); }
    .card-hover { transition: all 0.3s ease; }
    .card-hover:hover { transform: translateY(-2px); box-shadow: 0 8px 25px rgba(0,0,0,0.25); }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    .float { animation: float 3s ease-in-out infinite; }
    @keyframes confetti {
      0% { transform: translateY(0) rotate(0); opacity: 1; }
      100% { transform: translateY(-100px) rotate(360deg); opacity: 0; }
    }
    .confetti { animation: confetti 1s ease-out forwards; }
    .gradient-bg {
      background: linear-gradient(135deg, #0a1f3d 0%, #0d2d52 50%, #0a1f3d 100%);
    }
    .sky-gradient {
      background: linear-gradient(135deg, #1a3a52 0%, #2a5a8f 50%, #1a3a52 100%);
    }
    .pattern-overlay {
      background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.02'%3E%3Cpath d='M30 30l15-15v30l-15-15zM30 30L15 15v30l15-15z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
    }
    .modal-dark {
      background: linear-gradient(135deg, #0a1f3d 0%, #132d4a 100%);
    }
    .table-dark {
      background: linear-gradient(135deg, #0d2d52 0%, #0a1f3d 100%);
    }
  </style>
</head>
<body class="h-full gradient-bg pattern-overlay text-white overflow-auto">
  <div class="min-h-full p-4 md:p-6">
    <!-- Header Section -->
    <header class="text-center mb-8">
      <div class="inline-block mb-4">
        <div class="text-6xl float">🌙</div>
      </div>
      <h1 id="school-title" class="text-xl md:text-2xl font-bold text-yellow-300 mb-2">الابتدائية الثالثة وثمانون للطفولة المبكرة والروضة الملحقة بها</h1>
      <div class="sky-gradient text-yellow-300 py-3 px-6 rounded-full inline-block shadow-lg mb-4 border border-yellow-400/40">
        <h2 id="program-title" class="text-xl md:text-2xl font-extrabold">✨ نجمات الانضباط ✨</h2>
      </div>
      <p class="text-yellow-200 text-lg mb-3">خطة الانضباط المدرسي في شهر رمضان المبارك</p>
      <div class="bg-gradient-to-r from-blue-950/60 to-indigo-950/60 backdrop-blur rounded-full py-2 px-6 inline-block border border-yellow-400/40">
        <p class="text-yellow-300 font-semibold">📝 إعداد وتصميم: <span id="prepared-by" class="text-yellow-200">أستاذة عائشة الثبيتي</span></p>
      </div>
      <div class="flex justify-center gap-4 mt-4 text-sm flex-wrap">
        <span class="bg-blue-950/40 px-4 py-2 rounded-full text-yellow-300 border border-yellow-400/30">📅 المدة: 12 يوم</span>
        <span class="bg-blue-950/40 px-4 py-2 rounded-full text-yellow-300 border border-yellow-400/30">⭐ الهدف: 12 نجمة</span>
      </div>
    </header>

    <!-- Goals Section -->
    <div class="bg-gradient-to-r from-blue-950/40 to-indigo-950/40 backdrop-blur rounded-2xl p-6 mb-6 max-w-5xl mx-auto card-hover border border-yellow-400/30">
      <div class="flex items-center gap-3 mb-6">
        <div class="w-14 h-14 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center text-2xl shadow-lg">🎯</div>
        <div>
          <h3 class="text-2xl font-bold text-yellow-300">أهداف البرنامج</h3>
        </div>
      </div>
      
      <div id="goals-display" class="space-y-3 grid md:grid-cols-2 gap-4">
        <!-- Goals will be displayed here -->
      </div>
    </div>

    <!-- Implementation Mechanism -->
    <div class="bg-gradient-to-r from-blue-950/40 to-indigo-950/40 backdrop-blur rounded-2xl p-6 mb-6 max-w-5xl mx-auto card-hover border border-yellow-400/30">
      <div class="flex items-center gap-3 mb-6">
        <div class="w-14 h-14 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center text-2xl shadow-lg">⚙️</div>
        <div>
          <h3 class="text-2xl font-bold text-yellow-300">آلية التنفيذ</h3>
          <p class="text-yellow-200 text-sm">خطوات البرنامج بالتفصيل</p>
        </div>
      </div>
      
      <div class="space-y-4">
        <!-- Step 1 -->
        <div class="bg-gradient-to-r from-yellow-600/20 to-yellow-500/10 rounded-xl p-4 border border-yellow-400/40 hover:border-yellow-400/70 transition">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center text-white font-bold text-xl flex-shrink-0 shadow-md">1</div>
            <div class="flex-1">
              <h4 class="text-lg font-bold text-yellow-300 mb-2">📋 إنشاء لوحة النجمات</h4>
              <p class="text-white/90">يتم إنشاء لوحة تتضمن أسماء جميع الطالبات بخط واضح وكبير، مع تخصيص 12 مربع لكل طالبة لتسجيل النجمات اليومية بشكل منظم وسهل الملاحظة.</p>
            </div>
          </div>
        </div>

        <!-- Step 2 -->
        <div class="bg-gradient-to-r from-yellow-600/20 to-yellow-500/10 rounded-xl p-4 border border-yellow-400/40 hover:border-yellow-400/70 transition">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center text-white font-bold text-xl flex-shrink-0 shadow-md">2</div>
            <div class="flex-1">
              <h4 class="text-lg font-bold text-yellow-300 mb-2">⭐ منح النجمات اليومية</h4>
              <p class="text-white/90">كل يوم يتم منح نجمة واحدة للطالبات اللاتي التزمن بالسلوك الحسن والانضباط المدرسي، والاستماع الفعال، واحترام المعلم والزملاء، والتعاون والهدوء التام.</p>
            </div>
          </div>
        </div>

        <!-- Step 3 -->
        <div class="bg-gradient-to-r from-yellow-600/20 to-yellow-500/10 rounded-xl p-4 border border-yellow-400/40 hover:border-yellow-400/70 transition">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center text-white font-bold text-xl flex-shrink-0 shadow-md">3</div>
            <div class="flex-1">
              <h4 class="text-lg font-bold text-yellow-300 mb-2">🎯 التحفيز والتشجيع</h4>
              <p class="text-white/90">يتم تشجيع الطالبات بالكلمات الطيبة والثناء العلني أمام الفصل، مما يعزز الثقة بالنفس والحماس لتحقيق المزيد من النجمات والالتزام بالقيم.</p>
            </div>
          </div>
        </div>

        <!-- Step 4 -->
        <div class="bg-gradient-to-r from-yellow-600/20 to-yellow-500/10 rounded-xl p-4 border border-yellow-400/40 hover:border-yellow-400/70 transition">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center text-white font-bold text-xl flex-shrink-0 shadow-md">4</div>
            <div class="flex-1">
              <h4 class="text-lg font-bold text-yellow-300 mb-2">🎁 الجائزة والتكريم</h4>
              <p class="text-white/90">عند جمع 12 نجمة (في نهاية البرنامج)، تحصل الطالبة على شهادة تقدير مختومة وموقعة، وجائزة قيمة مثل الكتاب أو الهدايا الرمضانية الخاصة.</p>
            </div>
          </div>
        </div>

        <!-- Step 5 -->
        <div class="bg-gradient-to-r from-yellow-600/20 to-yellow-500/10 rounded-xl p-4 border border-yellow-400/40 hover:border-yellow-400/70 transition">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-gradient-to-br from-yellow-400 to-yellow-600 rounded-full flex items-center justify-center text-white font-bold text-xl flex-shrink-0 shadow-md">5</div>
            <div class="flex-1">
              <h4 class="text-lg font-bold text-yellow-300 mb-2">🏆 الاحتفال والتتويج</h4>
              <p class="text-white/90">عقد حفل توديع خاص بالطالبات المتفوقات، مع تتويجهن وتكريمهن أمام الجميع، وتعليق صورهن على لوحة الشرف، مما يعزز روح النجاح والفخر.</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Rewards Section -->
    <div class="bg-gradient-to-r from-blue-950/40 to-indigo-950/40 backdrop-blur rounded-2xl p-5 mb-6 max-w-5xl mx-auto card-hover border border-yellow-400/30">
      <div class="flex items-center gap-3 mb-4">
        <div class="w-12 h-12 bg-yellow-500 rounded-full flex items-center justify-center text-2xl">🎁</div>
        <h3 class="text-xl font-bold text-yellow-300">أمثلة الجوائز والحوافز</h3>
      </div>
      <div class="flex flex-wrap gap-3 justify-center">
        <span class="bg-gradient-to-r from-yellow-600/40 to-yellow-500/30 px-4 py-2 rounded-full text-sm text-yellow-200 border border-yellow-400/30">📖 قصة قصيرة مشهورة</span>
        <span class="bg-gradient-to-r from-yellow-600/40 to-yellow-500/30 px-4 py-2 rounded-full text-sm text-yellow-200 border border-yellow-400/30">👑 تاج نجمة رمضان</span>
        <span class="bg-gradient-to-r from-yellow-600/40 to-yellow-500/30 px-4 py-2 rounded-full text-sm text-yellow-200 border border-yellow-400/30">📜 شهادة تقدير مختومة</span>
        <span class="bg-gradient-to-r from-yellow-600/40 to-yellow-500/30 px-4 py-2 rounded-full text-sm text-yellow-200 border border-yellow-400/30">🌟 ملصقات ذهبية مميزة</span>
        <span class="bg-gradient-to-r from-yellow-600/40 to-yellow-500/30 px-4 py-2 rounded-full text-sm text-yellow-200 border border-yellow-400/30">🍫 حلويات رمضانية فاخرة</span>
      </div>
    </div>

    <!-- Add Student Section -->
    <div class="bg-gradient-to-r from-blue-950/40 to-indigo-950/40 backdrop-blur rounded-2xl p-5 mb-6 max-w-5xl mx-auto border border-yellow-400/30">
      <div class="flex items-center gap-3 mb-4">
        <div class="w-12 h-12 bg-yellow-500 rounded-full flex items-center justify-center text-2xl">➕</div>
        <h3 class="text-xl font-bold text-yellow-300">إضافة طالبة جديدة</h3>
      </div>
      <form id="add-student-form" class="flex flex-col sm:flex-row gap-3">
        <input 
          type="text" 
          id="student-name" 
          placeholder="اسم الطالبة..." 
          class="flex-1 bg-blue-950/60 border border-yellow-400/30 rounded-xl px-4 py-3 text-yellow-100 placeholder-yellow-400/50 focus:outline-none focus:ring-2 focus:ring-yellow-400"
          required
        >
        <button 
          type="submit" 
          id="add-btn"
          class="bg-gradient-to-r from-yellow-500 to-yellow-600 hover:from-yellow-600 hover:to-yellow-700 text-blue-950 font-bold px-6 py-3 rounded-xl transition-all duration-300 flex items-center justify-center gap-2"
        >
          <span>إضافة</span>
          <span>✨</span>
        </button>
      </form>
      <p id="limit-warning" class="hidden text-red-300 text-sm mt-2 text-center">⚠️ تم الوصول للحد الأقصى (999 طالبة)</p>
    </div>

    <!-- Students Table -->
    <div class="table-dark backdrop-blur rounded-2xl p-5 max-w-5xl mx-auto border border-yellow-400/30 shadow-xl">
      <div class="flex items-center justify-between mb-4">
        <div class="flex items-center gap-3">
          <div class="w-12 h-12 bg-yellow-500 rounded-full flex items-center justify-center text-2xl">📊</div>
          <h3 class="text-xl font-bold text-yellow-300">جدول الطالبات والنجمات</h3>
        </div>
        <div id="student-count" class="bg-blue-950/60 px-4 py-2 rounded-full text-sm text-yellow-300 font-bold border border-yellow-400/30">
          العدد: <span id="count-num">0</span>
        </div>
      </div>
      
      <div class="overflow-x-auto">
        <table class="w-full">
          <thead>
            <tr class="border-b border-yellow-400/40 bg-blue-950/70">
              <th class="text-right py-3 px-4 text-yellow-300 font-bold">الاسم</th>
              <th class="text-center py-3 px-4 text-yellow-300 font-bold">النجمات (12)</th>
              <th class="text-center py-3 px-4 text-yellow-300 font-bold">إضافة نجمة</th>
              <th class="text-center py-3 px-4 text-yellow-300 font-bold">شهادة</th>
              <th class="text-center py-3 px-4 text-yellow-300 font-bold">حذف</th>
            </tr>
          </thead>
          <tbody id="students-table">
            <!-- Students will be added here -->
          </tbody>
        </table>
      </div>
      
      <div id="empty-state" class="text-center py-10 text-yellow-400/60">
        <div class="text-5xl mb-3">🌙</div>
        <p class="text-yellow-300">لا توجد طالبات مسجلة حالياً</p>
        <p class="text-sm text-yellow-400/80">أضيفي أسماء الطالبات لبدء البرنامج</p>
      </div>
    </div>

    <!-- Celebration Toast -->
    <div id="celebration-toast" class="fixed bottom-4 left-4 right-4 max-w-sm mx-auto hidden">
      <div class="bg-gradient-to-r from-yellow-500 to-yellow-600 rounded-xl p-4 shadow-lg text-center text-blue-950 font-bold">
        🎉 ممتاز! تم إضافة نجمة جديدة! ⭐
      </div>
    </div>

    <!-- Certificate Modal -->
    <div id="certificate-modal" class="fixed inset-0 bg-black/70 flex items-center justify-center p-4 z-50 hidden">
      <div class="modal-dark rounded-3xl p-8 max-w-lg w-full text-white relative shadow-2xl border border-yellow-400/30">
        <button onclick="closeCertificate()" class="absolute top-4 left-4 text-yellow-400 hover:text-yellow-200 text-2xl transition">&times;</button>
        <div class="text-center">
          <div class="text-6xl mb-4">🏆</div>
          <h2 class="text-2xl font-bold text-yellow-300 mb-2">شهادة تقدير</h2>
          <div class="w-24 h-1 bg-gradient-to-r from-yellow-400 to-yellow-600 mx-auto mb-4 rounded-full"></div>
          <p class="text-lg mb-2 text-white">تُمنح هذه الشهادة للطالبة المتميزة</p>
          <p id="cert-name" class="text-3xl font-extrabold text-yellow-300 mb-4">اسم الطالبة</p>
          <p class="text-white/90 mb-4 leading-relaxed">لتحقيقها الانضباط المثالي والالتزام بقيم رمضان الكريمة وجمعها 12 نجمة في برنامج نجمات الانضباط</p>
          <div class="flex justify-center gap-2 text-4xl mb-4">
            <span>⭐</span><span>🌙</span><span>⭐</span>
          </div>
          <p class="text-sm text-yellow-300 border-t border-yellow-400/30 pt-3 mt-3">الابتدائية الثالثة وثمانون للطفولة المبكرة</p>
        </div>
      </div>
    </div>

    <!-- Footer -->
    <footer class="text-center mt-8 text-yellow-400/60 text-sm">
      <p>🌙 رمضان كريم 🌙</p>
      <p>نسأل الله أن يجعل طالباتنا من المتفوقات المنضبطات الملتزمات</p>
    </footer>
  </div>

  <script>
    // Default configuration
    const defaultConfig = {
      school_name: 'الابتدائية الثالثة وثمانون للطفولة المبكرة والروضة الملحقة بها',
      program_name: 'نجمات الانضباط',
      prepared_by: 'أستاذة عائشة الثبيتي',
      goal_1: 'تعزيز الانضباط الذاتي والتركيز داخل الفصل',
      goal_2: 'تشجيع السلوكيات الإيجابية والالتزام بالقيم',
      goal_3: 'غرس قيم رمضان: الهدوء والاحترام والتعاون',
      goal_4: 'تقليل الفوضى والتأخر والكلام أثناء الشرح',
      goal_5: 'تحسين الانضباط طوال شهر رمضان المبارك'
    };

    let config = { ...defaultConfig };
    let studentsData = [];
    let currentRecordCount = 0;

    // Data Handler for Data SDK
    const dataHandler = {
      onDataChanged(data) {
        studentsData = data;
        currentRecordCount = data.length;
        renderStudentsTable();
      }
    };

    // Initialize Element SDK
    window.elementSdk.init({
      defaultConfig,
      onConfigChange: async (configData) => {
        config = { ...config, ...configData };
        const schoolTitle = document.getElementById('school-title');
        const programTitle = document.getElementById('program-title');
        const preparedBy = document.getElementById('prepared-by');
        
        if (schoolTitle) {
          schoolTitle.textContent = config.school_name || defaultConfig.school_name;
        }
        if (programTitle) {
          programTitle.textContent = `✨ ${config.program_name || defaultConfig.program_name} ✨`;
        }
        if (preparedBy) {
          preparedBy.textContent = config.prepared_by || defaultConfig.prepared_by;
        }
        
        renderGoals();
      },
      mapToCapabilities: (configData) => ({
        recolorables: [],
        borderables: [],
        fontEditable: undefined,
        fontSizeable: undefined
      }),
      mapToEditPanelValues: (configData) => new Map([
        ['school_name', configData.school_name || defaultConfig.school_name],
        ['program_name', configData.program_name || defaultConfig.program_name],
        ['prepared_by', configData.prepared_by || defaultConfig.prepared_by],
        ['goal_1', configData.goal_1 || defaultConfig.goal_1],
        ['goal_2', configData.goal_2 || defaultConfig.goal_2],
        ['goal_3', configData.goal_3 || defaultConfig.goal_3],
        ['goal_4', configData.goal_4 || defaultConfig.goal_4],
        ['goal_5', configData.goal_5 || defaultConfig.goal_5]
      ])
    });

    // Initialize Data SDK
    async function initApp() {
      const result = await window.dataSdk.init(dataHandler);
      if (!result.isOk) {
        console.error('Failed to initialize Data SDK');
      }
      renderGoals();
    }

    // Render goals
    function renderGoals() {
      const display = document.getElementById('goals-display');
      display.innerHTML = '';
      
      for (let i = 1; i <= 5; i++) {
        const goalText = config[`goal_${i}`] || defaultConfig[`goal_${i}`];
        const div = document.createElement('div');
        div.className = 'bg-blue-950/50 rounded-lg p-4 border border-yellow-400/20 hover:border-yellow-400/40 transition';
        div.innerHTML = `
          <div class="flex items-start gap-3">
            <span class="text-yellow-400 text-2xl flex-shrink-0">◆</span>
            <p class="text-yellow-100 leading-relaxed">${escapeHtml(goalText)}</p>
          </div>
        `;
        display.appendChild(div);
      }
    }

    function escapeHtml(text) {
      const div = document.createElement('div');
      div.textContent = text;
      return div.innerHTML;
    }

    // Show celebration
    function showCelebration() {
      const toast = document.getElementById('celebration-toast');
      toast.classList.remove('hidden');
      
      const emojis = ['✨', '🌟', '⭐', '💫', '🎉'];
      for (let i = 0; i < 5; i++) {
        const confetti = document.createElement('div');
        confetti.textContent = emojis[Math.floor(Math.random() * emojis.length)];
        confetti.className = 'confetti fixed text-2xl pointer-events-none';
        confetti.style.left = Math.random() * 100 + '%';
        confetti.style.top = '50%';
        document.body.appendChild(confetti);
        
        setTimeout(() => confetti.remove(), 1000);
      }
      
      setTimeout(() => {
        toast.classList.add('hidden');
      }, 2000);
    }

    // Render students table
    function renderStudentsTable() {
      const tableBody = document.getElementById('students-table');
      const emptyState = document.getElementById('empty-state');
      const countNum = document.getElementById('count-num');
      
      countNum.textContent = studentsData.length;
      
      if (studentsData.length === 0) {
        tableBody.innerHTML = '';
        emptyState.classList.remove('hidden');
        return;
      }
      
      emptyState.classList.add('hidden');
      
      const existingRows = new Map();
      [...tableBody.children].forEach(row => {
        existingRows.set(row.dataset.studentId, row);
      });
      
      const processedIds = new Set();
      
      studentsData.forEach(student => {
        processedIds.add(student.__backendId);
        
        if (existingRows.has(student.__backendId)) {
          const row = existingRows.get(student.__backendId);
          updateRowContent(row, student);
        } else {
          const row = createStudentRow(student);
          tableBody.appendChild(row);
        }
      });
      
      existingRows.forEach((row, id) => {
        if (!processedIds.has(id)) {
          row.remove();
        }
      });
    }

    function createStudentRow(student) {
      const row = document.createElement('tr');
      row.className = 'border-b border-yellow-400/20 hover:bg-blue-950/50 transition text-white';
      row.dataset.studentId = student.__backendId;
      updateRowContent(row, student);
      return row;
    }

    function updateRowContent(row, student) {
      const stars = student.stars || 0;
      const maxStars = 12;
      
      row.innerHTML = `
        <td class="py-3 px-4 font-bold text-yellow-300">${escapeHtml(student.name)}</td>
        <td class="py-3 px-4">
          <div class="flex items-center justify-center gap-1 flex-wrap">
            ${generateStars(stars, maxStars, student.__backendId)}
          </div>
          <div class="text-center text-xs text-yellow-400 mt-1 font-bold">${stars}/${maxStars}</div>
        </td>
        <td class="py-3 px-4 text-center">
          <button 
            onclick="addStar('${student.__backendId}')" 
            class="bg-gradient-to-r from-yellow-500 to-yellow-600 hover:from-yellow-600 hover:to-yellow-700 text-blue-950 px-3 py-1 rounded-lg text-sm transition-all font-bold ${stars >= maxStars ? 'opacity-50 cursor-not-allowed' : ''}"
            ${stars >= maxStars ? 'disabled' : ''}
          >
            +⭐
          </button>
        </td>
        <td class="py-3 px-4 text-center">
          ${stars >= maxStars ? 
            `<button onclick="showCertificate('${escapeHtml(student.name)}')" class="bg-gradient-to-r from-yellow-500 to-yellow-600 hover:from-yellow-600 hover:to-yellow-700 text-blue-950 px-3 py-1 rounded-lg text-sm font-bold transition-all">
              🏆 شهادة
            </button>` : 
            `<span class="text-yellow-400 text-sm font-bold">-${maxStars - stars}</span>`
          }
        </td>
        <td class="py-3 px-4 text-center">
          <button 
            onclick="confirmDelete('${student.__backendId}')" 
            class="bg-red-900/40 hover:bg-red-900/70 text-red-300 px-3 py-1 rounded-lg text-sm transition-all border border-red-500/30"
            data-delete-btn="${student.__backendId}"
          >
            🗑️
          </button>
        </td>
      `;
    }

    function generateStars(count, max, studentId) {
      let html = '';
      for (let i = 0; i < max; i++) {
        if (i < count) {
          html += `<span class="star-icon text-xl cursor-pointer" onclick="removeStar('${studentId}', ${count})" title="انقر لإزالة نجمة">⭐</span>`;
        } else {
          html += `<span class="text-xl text-blue-950/40">☆</span>`;
        }
      }
      return html;
    }

    // Add new student
    document.getElementById('add-student-form').addEventListener('submit', async (e) => {
      e.preventDefault();
      
      if (currentRecordCount >= 999) {
        document.getElementById('limit-warning').classList.remove('hidden');
        return;
      }
      
      const nameInput = document.getElementById('student-name');
      const addBtn = document.getElementById('add-btn');
      const name = nameInput.value.trim();
      
      if (!name) return;
      
      addBtn.disabled = true;
      addBtn.innerHTML = '<span>جاري الإضافة...</span>';
      
      const result = await window.dataSdk.create({
        id: Date.now().toString(),
        name: name,
        stars: 0,
        hasCertificate: false,
        createdAt: new Date().toISOString()
      });
      
      addBtn.disabled = false;
      addBtn.innerHTML = '<span>إضافة</span><span>✨</span>';
      
      if (result.isOk) {
        nameInput.value = '';
      }
    });

    // Add star to student
    async function addStar(studentId) {
      const student = studentsData.find(s => s.__backendId === studentId);
      if (!student || student.stars >= 12) return;
      
      const updatedStudent = { ...student, stars: student.stars + 1 };
      if (updatedStudent.stars >= 12) {
        updatedStudent.hasCertificate = true;
      }
      
      await window.dataSdk.update(updatedStudent);
      showCelebration();
    }

    // Remove star from student
    async function removeStar(studentId, currentStars) {
      const student = studentsData.find(s => s.__backendId === studentId);
      if (!student || currentStars <= 0) return;
      
      const updatedStudent = { ...student, stars: student.stars - 1 };
      await window.dataSdk.update(updatedStudent);
    }

    // Confirm delete with inline UI
    function confirmDelete(studentId) {
      const btn = document.querySelector(`[data-delete-btn="${studentId}"]`);
      if (!btn) return;
      
      btn.innerHTML = 'تأكيد؟';
      btn.className = 'bg-red-700 hover:bg-red-800 text-white px-3 py-1 rounded-lg text-sm transition-all font-bold border border-red-500';
      btn.onclick = () => deleteStudent(studentId);
      
      setTimeout(() => {
        if (btn) {
          btn.innerHTML = '🗑️';
          btn.className = 'bg-red-900/40 hover:bg-red-900/70 text-red-300 px-3 py-1 rounded-lg text-sm transition-all border border-red-500/30';
          btn.onclick = () => confirmDelete(studentId);
        }
      }, 3000);
    }

    // Delete student
    async function deleteStudent(studentId) {
      const student = studentsData.find(s => s.__backendId === studentId);
      if (!student) return;
      
      const btn = document.querySelector(`[data-delete-btn="${studentId}"]`);
      if (btn) {
        btn.innerHTML = 'جاري...';
        btn.disabled = true;
      }
      
      await window.dataSdk.delete(student);
    }

    // Show certificate modal
    function showCertificate(name) {
      document.getElementById('cert-name').textContent = name;
      document.getElementById('certificate-modal').classList.remove('hidden');
    }

    // Close certificate modal
    function closeCertificate() {
      document.getElementById('certificate-modal').classList.add('hidden');
    }

    // Close modal on outside click
    document.getElementById('certificate-modal').addEventListener('click', (e) => {
      if (e.target.id === 'certificate-modal') {
        closeCertificate();
      }
    });

    // Initialize app
    initApp();
  </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9cfbfda3c3932cf4',t:'MTc3MTQwMTYyNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
