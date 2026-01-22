<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>벤처밸리 푸르지오 - 프리미엄 분양정보</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts (Noto Sans KR, Playfair Display) -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100;300;400;500;700;900&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
            overflow-x: hidden;
        }
        .font-serif {
            font-family: 'Playfair Display', serif;
        }
        .text-prugio {
            color: #005646; /* Prugio Green-ish Tone */
        }
        .bg-prugio {
            background-color: #005646;
        }
        .text-gold {
            color: #C5A059;
        }
        .bg-gold {
            background-color: #C5A059;
        }
        .border-gold {
            border-color: #C5A059;
        }
        .hero-bg {
            background-image: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }
        .animate-fade-up {
            animation: fadeUp 1s ease-out forwards;
            opacity: 0;
            transform: translateY(20px);
        }
        .delay-200 { animation-delay: 0.2s; }
        .delay-400 { animation-delay: 0.4s; }
        .delay-600 { animation-delay: 0.6s; }

        @keyframes fadeUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .premium-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header -->
    <header class="fixed w-full z-50 bg-white/95 backdrop-blur-sm shadow-md transition-all duration-300">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="text-2xl font-bold text-prugio tracking-tighter">
                PRUGIO <span class="text-sm font-normal text-gray-600 ml-1">벤처밸리</span>
            </div>
            <nav class="hidden md:flex space-x-8 font-medium text-gray-700">
                <a href="#benefits" class="hover:text-prugio transition">프리미엄 혜택</a>
                <a href="#unit" class="hover:text-prugio transition">세대안내</a>
                <a href="#location" class="hover:text-prugio transition">입지환경</a>
                <a href="#contact" class="hover:text-prugio transition">방문예약</a>
            </nav>
            <a href="tel:1866-2668" class="bg-prugio text-white px-6 py-2 rounded-full font-bold hover:bg-opacity-90 transition shadow-lg md:hidden">
                <i class="fas fa-phone-alt mr-2"></i>전화걸기
            </a>
            <div class="hidden md:block text-xl font-bold text-prugio">
                <i class="fas fa-headset mr-2"></i>1866-2668
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-bg h-screen flex items-center justify-center text-center px-4 relative">
        <div class="text-white max-w-4xl mx-auto">
            <div class="animate-fade-up">
                <span class="bg-gold text-white px-4 py-1 rounded-sm text-sm md:text-base font-bold tracking-widest uppercase mb-4 inline-block shadow-lg">Last Chance</span>
            </div>
            <h1 class="text-4xl md:text-6xl lg:text-7xl font-bold mb-6 leading-tight animate-fade-up delay-200">
                벤처밸리 푸르지오<br>
                <span class="font-serif italic text-gold">The Premium Life</span>
            </h1>
            <p class="text-lg md:text-2xl mb-8 font-light text-gray-200 animate-fade-up delay-400">
                잔여세대 마감임박! 선착순 동호지정 계약중<br>
                당신이 꿈꾸던 럭셔리 라이프의 시작
            </p>
            <div class="flex flex-col md:flex-row gap-4 justify-center animate-fade-up delay-600">
                <a href="#contact" class="bg-gold text-white px-8 py-4 rounded-sm text-lg font-bold hover:bg-yellow-600 transition shadow-xl w-full md:w-auto">
                    방문예약 신청하기
                </a>
                <a href="tel:1866-2668" class="border-2 border-white text-white px-8 py-4 rounded-sm text-lg font-bold hover:bg-white hover:text-prugio transition w-full md:w-auto">
                    문의 1866-2668
                </a>
            </div>
        </div>
        
        <!-- Urgent Banner -->
        <div class="absolute bottom-0 w-full bg-prugio bg-opacity-90 text-white py-4 overflow-hidden">
            <div class="container mx-auto px-4 flex justify-between items-center overflow-hidden">
                <div class="flex items-center space-x-2 animate-pulse">
                    <i class="fas fa-bell text-gold"></i>
                    <span class="font-bold text-sm md:text-lg">실시간 잔여세대 급속 소진중! 지금 바로 문의하세요.</span>
                </div>
                <div class="hidden md:block font-bold text-gold text-xl">마감임박</div>
            </div>
        </div>
    </section>

    <!-- Special Benefits Section -->
    <section id="benefits" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-prugio font-serif text-3xl md:text-5xl font-bold mb-4">Special Benefits</h2>
                <p class="text-gray-500 text-lg">지금 계약하시는 분들께만 드리는 특별한 파격 혜택</p>
                <div class="w-24 h-1 bg-gold mx-auto mt-6"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Benefit 1 -->
                <div class="premium-card bg-white p-8 rounded-lg shadow-lg border-t-4 border-gold text-center transition-all duration-300 group">
                    <div class="w-16 h-16 bg-gray-50 rounded-full flex items-center justify-center mx-auto mb-6 group-hover:bg-prugio transition-colors duration-300">
                        <i class="fas fa-file-contract text-2xl text-prugio group-hover:text-white transition-colors"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">계약금 500만원</h3>
                    <p class="text-gray-600">초기 자금 부담 없이<br>내 집 마련의 기회</p>
                </div>

                <!-- Benefit 2 -->
                <div class="premium-card bg-white p-8 rounded-lg shadow-lg border-t-4 border-gold text-center transition-all duration-300 group">
                    <div class="w-16 h-16 bg-gray-50 rounded-full flex items-center justify-center mx-auto mb-6 group-hover:bg-prugio transition-colors duration-300">
                        <i class="fas fa-hand-holding-dollar text-2xl text-prugio group-hover:text-white transition-colors"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">중도금 무상</h3>
                    <p class="text-gray-600">입주 시까지 금융비용<br>걱정 없는 안심 조건</p>
                </div>

                <!-- Benefit 3 -->
                <div class="premium-card bg-white p-8 rounded-lg shadow-lg border-t-4 border-gold text-center transition-all duration-300 group">
                    <div class="w-16 h-16 bg-gray-50 rounded-full flex items-center justify-center mx-auto mb-6 group-hover:bg-prugio transition-colors duration-300">
                        <i class="fas fa-maximize text-2xl text-prugio group-hover:text-white transition-colors"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">발코니 확장 무상</h3>
                    <p class="text-gray-600">더 넓고 쾌적한<br>실내 공간 제공</p>
                </div>

                <!-- Benefit 4 -->
                <div class="premium-card bg-white p-8 rounded-lg shadow-lg border-t-4 border-gold text-center transition-all duration-300 group">
                    <div class="w-16 h-16 bg-gray-50 rounded-full flex items-center justify-center mx-auto mb-6 group-hover:bg-prugio transition-colors duration-300">
                        <i class="fas fa-gift text-2xl text-prugio group-hover:text-white transition-colors"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">풀옵션 무상 제공</h3>
                    <p class="text-gray-600">시스템 에어컨 4대<br>붙박이장 등 다수 옵션</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Interior/Lifestyle Section -->
    <section id="unit" class="py-20 bg-gray-900 text-white relative">
        <div class="absolute inset-0 opacity-20" style="background-image: url('https://www.transparenttextures.com/patterns/cubes.png');"></div>
        <div class="container mx-auto px-4 relative z-10">
            <div class="flex flex-col lg:flex-row items-center gap-12">
                <div class="lg:w-1/2">
                    <h2 class="text-3xl md:text-5xl font-bold mb-6 leading-tight">
                        디테일이 다른<br>
                        <span class="text-gold font-serif">Luxury Interior</span>
                    </h2>
                    <p class="text-gray-300 mb-8 text-lg leading-relaxed">
                        시간이 흐를수록 깊어지는 가치, 푸르지오만의 혁신적인 평면 설계와 
                        고급 마감재로 완성된 품격 있는 공간을 만나보세요.
                        <br><br>
                        모든 세대 <strong>시스템 에어컨 4대</strong>와 <strong>고급 붙박이장</strong>이 
                        기본으로 제공되어 입주 즉시 완벽한 생활이 가능합니다.
                    </p>
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-gold mr-3"></i>
                            <span>채광과 통풍을 극대화한 혁신 평면</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-gold mr-3"></i>
                            <span>품격을 높여주는 고급 아트월 및 마감재</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-gold mr-3"></i>
                            <span>편리한 동선의 'ㄷ'자 주방 및 넉넉한 수납공간</span>
                        </li>
                    </ul>
                </div>
                <div class="lg:w-1/2 grid grid-cols-2 gap-4">
                    <img src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Interior 1" class="rounded-lg shadow-lg hover:opacity-90 transition transform hover:scale-105 duration-500">
                    <img src="https://images.unsplash.com/photo-1616137466211-f939a420be84?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Interior 2" class="rounded-lg shadow-lg hover:opacity-90 transition transform hover:scale-105 duration-500 mt-8">
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action Banner -->
    <section class="bg-gold py-12">
        <div class="container mx-auto px-4 text-center">
            <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">선착순 동호지정 계약 진행중!</h3>
            <p class="text-white text-lg mb-8 opacity-90">로얄동/로얄층 선점을 위해 지금 바로 문의주세요.</p>
            <a href="tel:1866-2668" class="inline-block bg-prugio text-white px-10 py-4 rounded-full text-2xl font-bold shadow-lg hover:bg-gray-800 transition transform hover:scale-105">
                <i class="fas fa-phone-volume mr-3"></i>1866-2668
            </a>
        </div>
    </section>

    <!-- Reservation Form Section -->
    <section id="contact" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4 max-w-4xl">
            <div class="bg-white rounded-xl shadow-2xl overflow-hidden flex flex-col md:flex-row">
                <div class="md:w-1/2 bg-prugio p-10 text-white flex flex-col justify-center">
                    <h3 class="text-3xl font-bold mb-4 font-serif">VIP 방문예약</h3>
                    <p class="mb-8 text-gray-200">
                        전문 상담사가 고객님께 딱 맞는 <br>최적의 동호수와 계약 조건을 안내해 드립니다.
                    </p>
                    <div class="space-y-6">
                        <div class="flex items-center">
                            <div class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center mr-4">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gold font-bold">MODEL HOUSE</p>
                                <p>사전예약제 운영중 (주소 문자전송)</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center mr-4">
                                <i class="fas fa-phone"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gold font-bold">INQUIRY</p>
                                <p class="text-2xl font-bold">1866-2668</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="md:w-1/2 p-10">
                    <form id="reservationForm" onsubmit="submitForm(event)">
                        <h4 class="text-xl font-bold text-gray-800 mb-6">관심고객 등록 / 방문예약</h4>
                        
                        <div class="mb-4">
                            <label class="block text-gray-700 text-sm font-bold mb-2" for="name">성함</label>
                            <input class="shadow appearance-none border rounded w-full py-3 px-3 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-prugio focus:border-transparent" id="name" type="text" placeholder="예: 홍길동" required>
                        </div>
                        
                        <div class="mb-4">
                            <label class="block text-gray-700 text-sm font-bold mb-2" for="phone">연락처</label>
                            <input class="shadow appearance-none border rounded w-full py-3 px-3 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-prugio focus:border-transparent" id="phone" type="tel" placeholder="예: 010-1234-5678" required>
                        </div>

                        <div class="mb-6">
                            <label class="flex items-center">
                                <input type="checkbox" class="form-checkbox text-prugio h-5 w-5" required checked>
                                <span class="ml-2 text-sm text-gray-600">개인정보 수집 및 이용에 동의합니다.</span>
                            </label>
                        </div>
                        
                        <button type="submit" class="w-full bg-gray-800 text-white font-bold py-3 px-4 rounded hover:bg-prugio transition duration-300">
                            상담 신청하기
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-10 border-t border-gray-800">
        <div class="container mx-auto px-4 text-center md:text-left">
            <div class="flex flex-col md:flex-row justify-between items-center mb-8">
                <div class="text-2xl font-bold text-white mb-4 md:mb-0">PRUGIO</div>
                <div class="flex space-x-4">
                    <a href="#" class="hover:text-white transition"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="hover:text-white transition"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="hover:text-white transition"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
            <div class="text-xs space-y-2">
                <p>※ 본 사이트에 사용된 이미지는 소비자의 이해를 돕기 위한 것으로 실제와 다를 수 있습니다.</p>
                <p>※ 하자 등에 따른 소비자 피해보상은 건설산업기본법 및 주택법 등 관련 법령에 따라 적용됩니다.</p>
                <p>분양문의: 1866-2668 | 모델하우스는 사전예약제로 운영됩니다.</p>
                <p class="mt-4 text-gray-600">Copyright © 2024 VENTURE VALLEY PRUGIO. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Sticky Bottom Bar (Mobile Only) -->
    <div class="fixed bottom-0 left-0 w-full bg-white border-t border-gray-200 p-3 md:hidden z-50 shadow-[0_-4px_6px_-1px_rgba(0,0,0,0.1)]">
        <div class="flex gap-2">
            <a href="#contact" class="flex-1 bg-gray-800 text-white py-3 rounded text-center font-bold text-sm flex items-center justify-center">
                <i class="far fa-calendar-check mr-2"></i>방문예약
            </a>
            <a href="tel:1866-2668" class="flex-1 bg-prugio text-white py-3 rounded text-center font-bold text-lg flex items-center justify-center animate-pulse">
                <i class="fas fa-phone-alt mr-2"></i>전화문의
            </a>
        </div>
    </div>

    <script>
        function submitForm(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            
            // 실제 서버 전송 로직 대신 알림창 표시
            alert(`[방문예약 접수완료]\n\n성함: ${name}\n연락처: ${phone}\n\n전문 상담사가 빠른 시간 내에 연락드리겠습니다.`);
            
            // 폼 초기화
            document.getElementById('reservationForm').reset();
        }

        // Smooth Scroll for Anchor Links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Header Scroll Effect
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            if (window.scrollY > 50) {
                header.classList.add('py-2');
                header.classList.remove('py-3');
            } else {
                header.classList.add('py-3');
                header.classList.remove('py-2');
            }
        });
    </script>
</body>
</html>
