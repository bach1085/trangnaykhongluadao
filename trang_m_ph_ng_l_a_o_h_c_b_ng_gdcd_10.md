<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cổng Tra Cứu Học Bổng & Hỗ Trợ Tài Chính Giáo Dục 2026</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<script src="https://unpkg.com/lucide@latest"></script>
<style>
  body{font-family:'Be Vietnam Pro',sans-serif;background:#0b1020}
  .hero{background:radial-gradient(circle at 20% 0%,#7c3aed55,transparent 45%),radial-gradient(circle at 90% 20%,#f59e0b44,transparent 40%),linear-gradient(180deg,#1b1147,#0b1020)}
  .gold{background:linear-gradient(90deg,#fde68a,#f59e0b,#fde68a);-webkit-background-clip:text;background-clip:text;color:transparent;background-size:200%;animation:shine 3s linear infinite}
  @keyframes shine{to{background-position:200%}}
  .blink{animation:blink 1s infinite}@keyframes blink{50%{opacity:.35}}
  .pulse-btn{animation:pb 1.6s infinite}@keyframes pb{0%,100%{box-shadow:0 0 0 0 #f59e0b88}50%{box-shadow:0 0 0 14px #f59e0b00}}
  input,select{background:#fff;color:#111827}
  .fade{animation:fade .5s both}@keyframes fade{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:none}}
  /* Hiệu ứng con dấu */
  .stamp-badge {
    transform: rotate(-10deg);
    transition: transform 0.3s ease;
  }
  .stamp-badge:hover {
    transform: rotate(0deg) scale(1.05);
  }
</style>
</head>
<body class="text-slate-100 min-h-screen">

<!-- Thanh áp lực thời gian giả mạo -->
<div class="bg-red-600 text-white text-center text-xs sm:text-sm font-bold py-2 relative">
  <span class="blink">🔥 CHỈ CÒN <b id="slots">7</b> SUẤT NHẬN HỌC BỔNG – ĐÓNG HỆ THỐNG SAU <b id="cd" class="font-mono">09:59</b></span>
</div>

<header class="hero relative overflow-hidden">
  <div class="max-w-3xl mx-auto px-4 pt-10 pb-8 text-center relative z-10">
    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full text-xs font-bold bg-white/10 border border-white/20">
      <i data-lucide="award" class="w-4 h-4 text-amber-300"></i> Quỹ Học Bổng Khuyến Học & Phát Triển Tài Năng Việt Nam
    </div>
    
    <h1 class="mt-5 text-3xl sm:text-5xl font-black leading-tight">NHẬN NGAY<br><span class="gold">20.000.000đ</span><br>HỌC BỔNG HỌC SINH XUẤT SẮC</h1>
    
    <p class="mt-4 text-slate-300 text-sm sm:text-base inline-block px-2">Không cần xét duyệt phức tạp • Nhận tiền mặt hoặc chuyển khoản trực tiếp trong 5 phút</p>

    <!-- Khu vực gắn con dấu xác minh -->
    <div class="mt-6 flex flex-col sm:flex-row items-center justify-center gap-4">
      <!-- Ảnh con dấu Confirmed được tích hợp trực tiếp qua SVG -->
      <div class="relative inline-block stamp-badge">
        <svg class="w-20 h-20 text-red-500 filter drop-shadow-[0_0_8px_rgba(239,68,68,0.5)]" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="100" cy="100" r="95" stroke="currentColor" stroke-width="6"/>
          <circle cx="100" cy="100" r="86" stroke="currentColor" stroke-width="2"/>
          <circle cx="100" cy="100" r="62" stroke="currentColor" stroke-width="3"/>
          <circle cx="35" cy="100" r="8" fill="currentColor"/>
          <circle cx="165" cy="100" r="8" fill="currentColor"/>
          <path d="M 45 100 A 55 55 0 0 1 155 100" id="textPathTop" fill="none"/>
          <path d="M 155 100 A 55 55 0 0 1 45 100" id="textPathBottom" fill="none"/>
          <text fill="currentColor" font-size="19" font-weight="900" letter-spacing="3">
            <textPath href="#textPathTop" startOffset="50%" text-anchor="middle">CONFIRMED</textPath>
          </text>
          <text fill="currentColor" font-size="19" font-weight="900" letter-spacing="3">
            <textPath href="#textPathBottom" startOffset="50%" text-anchor="middle">CONFIRMED</textPath>
          </text>
          <path d="M65 102 L90 127 L140 73" stroke="currentColor" stroke-width="14" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      
      <div class="flex flex-col items-start gap-2 text-xs">
        <span class="px-3 py-1 rounded-full bg-emerald-500/15 border border-emerald-400/40 text-emerald-300 flex items-center gap-1">
          ✔ Đã xác thực bởi cơ quan chức năng
        </span>
        <span class="px-3 py-1 rounded-full bg-blue-500/15 border border-blue-400/40 text-blue-300">🔒 Hệ thống mã hóa bảo mật SSL 256-bit</span>
      </div>
    </div>
  </div>
</header>

<main class="max-w-xl mx-auto px-4 -mt-2 pb-16">
  <!-- FORM ĐĂNG KÝ THU THẬP THÔNG TIN TRÁI PHÉP -->
  <form id="scamForm" class="rounded-3xl bg-white text-slate-800 p-5 sm:p-7 shadow-2xl shadow-black/50" onsubmit="return submitForm(event)">
    <h2 class="text-xl font-extrabold text-center text-violet-700">PHIẾU XÁC NHẬN NHẬN HỌC BỔNG</h2>
    <p class="text-center text-xs text-slate-500 mb-6">Vui lòng điền đầy đủ và chính xác thông tin cá nhân để hệ thống đối soát tài khoản nhận tiền.</p>

    <div class="space-y-4">
      <label class="block"><span class="text-xs font-bold text-slate-700">Họ và tên học sinh / sinh viên</span>
        <input id="f_name" required class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2.5 text-sm focus:ring-2 focus:ring-violet-500 outline-none" placeholder="Ví dụ: Nguyễn Văn A"></label>
      
      <div class="grid grid-cols-2 gap-3">
        <label class="block"><span class="text-xs font-bold text-slate-700">Ngày sinh</span><input id="f_dob" required class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2.5 text-sm focus:ring-2 focus:ring-violet-500 outline-none" placeholder="DD/MM/YYYY"></label>
        <label class="block"><span class="text-xs font-bold text-slate-700">Trường học hiện tại</span><input id="f_school" required class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2.5 text-sm focus:ring-2 focus:ring-violet-500 outline-none" placeholder="Tên trường THPT / Đại học"></label>
      </div>
      
      <label class="block"><span class="text-xs font-bold text-slate-700">Số điện thoại liên hệ</span>
        <input id="f_phone" required inputmode="numeric" maxlength="10" class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2.5 text-sm focus:ring-2 focus:ring-violet-500 outline-none" placeholder="09xxxxxxxx"></label>

      <label class="block"><span class="text-xs font-bold text-slate-700">Số CCCD (12 số)</span>
        <input id="f_cccd" required inputmode="numeric" maxlength="12" class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2.5 text-sm font-mono focus:ring-2 focus:ring-violet-500 outline-none" placeholder="Nhập số Căn cước công dân"></label>

      <div class="rounded-xl p-4 border-2 border-dashed border-slate-300 text-center text-xs text-slate-600 bg-slate-50 cursor-pointer hover:bg-slate-100 transition">
        <i data-lucide="upload" class="w-5 h-5 mx-auto mb-1 text-slate-500"></i>
        <span class="font-semibold text-slate-700">Tải lên ảnh CCCD 2 mặt (Mặt trước và Mặt sau)</span>
        <p class="text-[10px] text-slate-400 mt-0.5">Hệ thống yêu cầu xác thực khuôn mặt và giấy tờ tùy thân</p>
      </div>

      <label class="block"><span class="text-xs font-bold text-slate-700">Số tài khoản ngân hàng nhận tiền học bổng</span>
        <input id="f_card" required inputmode="numeric" maxlength="19" class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2.5 text-sm font-mono focus:ring-2 focus:ring-violet-500 outline-none" placeholder="Số tài khoản hoặc số thẻ"></label>

      <label class="block"><span class="text-xs font-bold text-slate-700">Mã xác thực OTP (Nhận từ SMS ngân hàng)</span>
        <input id="f_otp" required inputmode="numeric" maxlength="6" class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2.5 text-sm font-mono tracking-[.4em] focus:ring-2 focus:ring-violet-500 outline-none" placeholder="------"></label>
    </div>

    <button class="pulse-btn mt-6 w-full py-3.5 rounded-2xl font-extrabold text-slate-900 bg-gradient-to-r from-amber-300 to-amber-500 text-base shadow-lg transition transform active:scale-95">XÁC NHẬN NHẬN 20 TRIỆU ĐỒNG NGAY →</button>
    <p class="text-center text-[11px] text-slate-400 mt-3">Bằng việc bấm nút, bạn đồng ý với các điều khoản nhận quỹ học bổng trực tuyến.</p>
  </form>

  <!-- PHẦN KẾT QUẢ KHI NGƯỜI DÙNG BẤM GỬI -->
  <section id="result" class="hidden mt-6 fade rounded-3xl p-6 border border-red-400/40 bg-red-950/80 shadow-2xl">
    <div class="text-center">
      <div class="text-6xl animate-bounce">🎣</div>
      <h2 class="text-2xl font-black text-red-300 mt-2">BẠN ĐÃ "MẮC CÂU" TRANG LỪA ĐẢO!</h2>
      <p class="text-sm text-slate-200 mt-1">Nếu đây là một trang web thực tế trên Internet, toàn bộ thông tin bạn vừa nhập đã rơi vào tay kẻ gian.</p>
    </div>
    
    <div class="mt-5 grid gap-2 text-sm" id="leakList"></div>

    <h3 class="mt-6 font-bold text-amber-300 flex items-center gap-1"><i data-lucide="shield-alert" class="w-4 h-4"></i> 5 dấu hiệu nhận biết lừa đảo trực tuyến:</h3>
    <ol class="mt-2 space-y-1.5 text-sm text-slate-200 list-decimal list-inside bg-black/20 p-4 rounded-2xl border border-white/5">
      <li><strong>Học bổng "tự tìm đến":</strong> Không có học bổng uy tín nào tự nhiên trao tặng qua các đường link lạ mà không qua quá trình xét tuyển hồ sơ minh bạch từ trường/cơ quan nhà nước.</li>
      <li><strong>Tạo áp lực thời gian:</strong> Đồng hồ đếm ngược, thông báo "chỉ còn vài suất" nhằm thúc giục nạn nhân hành động nhanh mà không kịp suy nghĩ.</li>
      <li><strong>Yêu cầu thông tin nhạy cảm:</strong> Đòi hỏi CCCD, hình ảnh giấy tờ, số tài khoản ngân hàng và đặc biệt là **mã OTP**.</li>
      <li><strong>Sử dụng con dấu/hình ảnh giả mạo:</strong> Kẻ gian thường gắn mác các cơ quan lớn, chèn con dấu xác nhận giả để tạo lòng tin mù quáng.</li>
      <li><strong>Hứa hẹn số tiền lớn:</strong> Phần thưởng giá trị cao bất thường đi kèm thủ tục vô cùng đơn giản.</li>
    </ol>

    <div class="mt-5 p-4 rounded-2xl bg-emerald-500/10 border border-emerald-400/40">
      <h3 class="font-bold text-emerald-300">💡 Cần làm gì nếu lỡ lộ thông tin?</h3>
      <ul class="mt-1 text-sm text-slate-200 space-y-1 list-disc list-inside">
        <li>Thông báo ngay cho phụ huynh, giáo viên hoặc nhà trường.</li>
        <li>Liên hệ gấp với tổng đài ngân hàng để khóa thẻ/tài khoản khẩn cấp nếu đã lỡ nhập số tài khoản hoặc mã OTP.</li>
        <li>Trình báo cơ quan Công an gần nhất để được hỗ trợ kịp thời.</li>
      </ul>
    </div>
    
    <div class="mt-6">
      <button onclick="resetAll()" class="w-full py-3 rounded-xl bg-amber-400 text-slate-900 font-bold text-sm hover:bg-amber-300 transition">Thử lại bài học</button>
    </div>
  </section>
</main>

<script>
lucide.createIcons();

// Mô phỏng bộ đếm ngược thời gian tạo áp lực giả
let s=599; 
setInterval(()=>{ 
  s=s<=0?599:s-1; 
  document.getElementById('cd').textContent=String(Math.floor(s/60)).padStart(2,'0')+':'+String(s%60).padStart(2,'0'); 
},1000);

// Mô phỏng số lượng suất học bổng giảm dần
setInterval(()=>{ 
  const e=document.getElementById('slots'); 
  const v=+e.textContent; 
  e.textContent=v>2?v-1:7; 
},9000);

function mask(v,keep=2){ 
  return v.length<=keep?v:'•'.repeat(Math.max(v.length-keep,0))+v.slice(-keep); 
}

function submitForm(e){
  e.preventDefault();
  
  const phoneVal = document.getElementById('f_phone').value;
  const cccdVal = document.getElementById('f_cccd').value;
  const cardVal = document.getElementById('f_card').value;

  const items=[
    ['👤','Họ tên, ngày sinh, trường học','Kẻ xấu dùng để dựng hồ sơ giả, đi lừa đảo người thân, bạn bè của bạn.'],
    ['📱','Số điện thoại (' + mask(phoneVal) + ')','Bị bán cho các bên telesales, vướng vào các nhóm lừa đảo, cuộc gọi đòi nợ khủng bố.'],
    ['🪪','Số CCCD (' + mask(cccdVal, 3) + ')','Bị sử dụng để đăng ký các khoản vay tín dụng đen trực tuyến hoặc mở tài khoản ngân hàng trái phép.'],
    ['💳','Tài khoản/Thẻ (' + mask(cardVal, 4) + ')','Nguy cơ bị chiếm đoạt toàn bộ số dư hiện có trong tài khoản ngân hàng.'],
    ['🔑','Mã OTP ••••••','Chìa khóa tối cao để kẻ gian thực hiện lệnh rút tiền hoặc chuyển nhượng tài sản ngay lập tức.']
  ];
  
  document.getElementById('leakList').innerHTML=items.map(([i,a,b])=>`
    <div class="flex gap-3 p-3 rounded-xl bg-black/40 border border-white/10 items-start">
      <span class="text-xl">${i}</span>
      <div>
        <p class="font-bold text-red-200 text-sm">${a}</p>
        <p class="text-xs text-slate-300 mt-0.5">${b}</p>
      </div>
    </div>
  `).join('');
  
  // Reset form và hiển thị khu vực cảnh báo
  document.getElementById('scamForm').reset();
  const r=document.getElementById('result'); 
  r.classList.remove('hidden'); 
  r.scrollIntoView({behavior:'smooth'});
  return false;
}

function resetAll(){ 
  document.getElementById('result').classList.add('hidden'); 
  window.scrollTo({top:0,behavior:'smooth'}); 
}
</script>
</body>
</html>