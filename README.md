<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strategy 1: Emergency Hospital Delivery</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; background: linear-gradient(135deg, #e74c3c, #c0392b); padding: 20px; }
        .container { max-width: 1400px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .language-toggle { position: sticky; top: 0; z-index: 1000; background: rgba(255,255,255,0.98); padding: 15px 40px; display: flex; justify-content: center; gap: 15px; border-bottom: 3px solid #e74c3c; box-shadow: 0 3px 15px rgba(0,0,0,0.1); }
        .lang-btn { padding: 12px 30px; border: 2px solid #e74c3c; background: white; color: #e74c3c; border-radius: 8px; cursor: pointer; font-size: 1.1em; font-weight: bold; transition: all 0.3s ease; }
        .lang-btn:hover { background: #fff0f0; transform: translateY(-2px); }
        .lang-btn.active { background: #e74c3c; color: white; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
        .header { background: linear-gradient(135deg, #e74c3c, #c0392b); color: white; padding: 60px 40px; text-align: center; }
        .header h1 { font-size: 3.5em; margin-bottom: 15px; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .revenue-amount { font-size: 2.5em; font-weight: bold; color: #27ae60; text-align: center; margin: 30px 0; }
        .product-card { background: #fff5f5; padding: 25px; border-radius: 12px; margin: 20px 0; border-left: 5px solid #e74c3c; }
        .product-card h3 { color: #e74c3c; margin-bottom: 15px; font-size: 1.6em; }
        ul { line-height: 1.9; margin-left: 20px; }
        ul li { margin: 10px 0; }
        .back-link { display: inline-block; background: #3498db; color: white; padding: 12px 30px; border-radius: 8px; text-decoration: none; margin: 20px 0; font-weight: bold; }
        .back-link:hover { background: #2980b9; }
    </style>
</head>
<body>
    <div class="container">
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 English</button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 Русский</button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 O'zbek</button>
        </div>

        <!-- ENGLISH -->
        <div class="lang-content active" id="content-en">
            <div class="header">
                <h1>🚨 STRATEGY 1</h1>
                <h2 style="font-size: 2em; margin-top: 10px;">Emergency Hospital Delivery Service</h2>
                <p style="font-size: 1.3em; margin-top: 15px;">2-4 Hour Guaranteed Delivery to Hospitals & Discharge Units</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back to Portfolio</a>
                
                <div class="revenue-amount">Year 1 Target: $560K - $1.6M</div>

                <h2 style="font-size: 2.5em; color: #e74c3c; margin: 40px 0 30px 0; text-align: center;">Core Concept</h2>
                
                <div class="product-card">
                    <h3>🎯 Business Model</h3>
                    <p><strong>Target:</strong> Hospital discharge departments needing immediate DME delivery for same-day patient releases</p>
                    <ul>
                        <li><strong>Guaranteed 2-4 Hour Delivery</strong> to hospital discharge areas</li>
                        <li><strong>BOC-Licensed Equipment (75-80%)</strong> - wheelchairs, hospital beds, walkers, oxygen</li>
                        <li><strong>Emergency Setup Service (20-25%)</strong> - white-glove installation and patient training</li>
                        <li><strong>Direct Hospital Billing</strong> - insurance pre-authorization during patient stay</li>
                        <li><strong>Premium Pricing</strong> justified by speed and guaranteed delivery</li>
                    </ul>
                </div>

                <h2 style="font-size: 2.5em; color: #e74c3c; margin: 40px 0 30px 0; text-align: center;">Primary BOC Products (75-80%)</h2>

                <div class="product-card">
                    <h3>🦽 Standard Wheelchairs (M06) - $200-$800</h3>
                    <ul>
                        <li>Manual wheelchairs for post-discharge mobility</li>
                        <li>Lightweight transport chairs</li>
                        <li>Heavy-duty models for bariatric patients</li>
                        <li><strong>Revenue Potential:</strong> $80K-$200K Year 1 (200-300 units)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>⚡ Power Wheelchairs (M06A) - $2,500-$20,000</h3>
                    <ul>
                        <li>Complex rehab power chairs</li>
                        <li>Standard power mobility devices</li>
                        <li>Emergency loaner units available</li>
                        <li><strong>Revenue Potential:</strong> $100K-$400K Year 1 (20-40 units)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🛏️ Hospital Beds (DM11) - $800-$3,500</h3>
                    <ul>
                        <li>Semi-electric adjustable beds</li>
                        <li>Full-electric models with air mattresses</li>
                        <li>Bariatric hospital beds (up to 1000 lbs)</li>
                        <li><strong>Revenue Potential:</strong> $120K-$350K Year 1 (80-120 units)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🚶 Walkers & Canes (M05) - $50-$400</h3>
                    <ul>
                        <li>Standard and rolling walkers</li>
                        <li>Knee walkers for lower leg injuries</li>
                        <li>Quad canes and walking aids</li>
                        <li><strong>Revenue Potential:</strong> $40K-$100K Year 1 (250-400 units)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🫁 Oxygen Equipment (DM28/29) - $1,500-$5,000</h3>
                    <ul>
                        <li>Oxygen concentrators (rental and purchase)</li>
                        <li>Portable oxygen systems</li>
                        <li>Emergency oxygen delivery service</li>
                        <li><strong>Revenue Potential:</strong> $100K-$300K Year 1 (40-80 setups)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🛁 Bathroom Safety (DM02/DM03) - $100-$800</h3>
                    <ul>
                        <li>Commodes and bedside toilets</li>
                        <li>Shower chairs and bath benches</li>
                        <li>Grab bars and safety rails</li>
                        <li><strong>Revenue Potential:</strong> $60K-$150K Year 1 (200-350 units)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🏋️ Patient Lifts (DM21/22) - $800-$3,500</h3>
                    <ul>
                        <li>Hoyer-style patient lifts</li>
                        <li>Sit-to-stand lifts</li>
                        <li>Ceiling track systems (installation extra)</li>
                        <li><strong>Revenue Potential:</strong> $60K-$100K Year 1 (20-40 units)</li>
                    </ul>
                </div>

                <h2 style="font-size: 2.5em; color: #e74c3c; margin: 40px 0 30px 0; text-align: center;">Implementation Plan</h2>

                <div class="product-card">
                    <h3>📋 Phase 1: Months 1-3 (Foundation)</h3>
                    <ul>
                        <li><strong>Partner with 2-3 hospitals</strong> - establish discharge coordinator relationships</li>
                        <li><strong>Stock emergency inventory</strong> - 20-30 most common items ready to deploy</li>
                        <li><strong>Hire 2 delivery drivers</strong> - trained in medical equipment handling</li>
                        <li><strong>Set up billing systems</strong> - insurance verification and pre-authorization</li>
                        <li><strong>Target:</strong> $45K-$130K in first 3 months</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>📈 Phase 2: Months 4-8 (Growth)</h3>
                    <ul>
                        <li><strong>Expand to 5-7 hospitals</strong> - increase coverage area</li>
                        <li><strong>Add specialized equipment</strong> - power wheelchairs, oxygen</li>
                        <li><strong>Implement 24/7 service</strong> - weekend and overnight deliveries</li>
                        <li><strong>Hire clinical staff</strong> - RT for oxygen, OT for mobility assessments</li>
                        <li><strong>Target:</strong> $250K-$700K cumulative by month 8</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🚀 Phase 3: Months 9-12 (Scale)</h3>
                    <ul>
                        <li><strong>10+ hospital partnerships</strong> - dominant regional provider</li>
                        <li><strong>Fleet expansion</strong> - 4-6 dedicated delivery vehicles</li>
                        <li><strong>Warehouse optimization</strong> - strategic location near hospitals</li>
                        <li><strong>Technology integration</strong> - real-time tracking and EHR integration</li>
                        <li><strong>Target:</strong> $560K-$1.6M full year</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>💡 Success Factors</h3>
                    <ul>
                        <li>✅ <strong>Speed is Premium:</strong> 2-4 hour delivery allows premium pricing (15-25% above standard)</li>
                        <li>✅ <strong>Insurance Pre-Auth:</strong> Complete billing during hospital stay = faster payment</li>
                        <li>✅ <strong>Relationship-Driven:</strong> Discharge coordinators become your sales team</li>
                        <li>✅ <strong>Low Competition:</strong> Most DME providers take 3-7 days for delivery</li>
                        <li>✅ <strong>Recurring Customers:</strong> Hospitals discharge patients daily</li>
                    </ul>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Back to Portfolio</a>
            </div>
        </div>

        <!-- RUSSIAN -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>🚨 СТРАТЕГИЯ 1</h1>
                <h2 style="font-size: 2em; margin-top: 10px;">Экстренная Больничная Доставка</h2>
                <p style="font-size: 1.3em; margin-top: 15px;">Гарантированная Доставка 2-4 Часа в Больницы и Выписные Отделения</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад к Портфолио</a>
                
                <div class="revenue-amount">Цель на 1-й Год: $560K - $1.6M</div>

                <h2 style="font-size: 2.5em; color: #e74c3c; margin: 40px 0 30px 0; text-align: center;">Основная Концепция</h2>
                
                <div class="product-card">
                    <h3>🎯 Бизнес-Модель</h3>
                    <p><strong>Цель:</strong> Больничные выписные отделения, нуждающиеся в немедленной доставке DME для выписки пациентов в тот же день</p>
                    <ul>
                        <li><strong>Гарантированная Доставка 2-4 Часа</strong> в зоны выписки больниц</li>
                        <li><strong>Лицензированное BOC Оборудование (75-80%)</strong> - коляски, кровати, ходунки, кислород</li>
                        <li><strong>Экстренная Услуга Установки (20-25%)</strong> - белоперчаточная установка и обучение пациентов</li>
                        <li><strong>Прямое Больничное Выставление Счетов</strong> - предварительное разрешение страховки во время пребывания</li>
                        <li><strong>Премиум Цены</strong> оправданы скоростью и гарантированной доставкой</li>
                    </ul>
                </div>

                <h2 style="font-size: 2.5em; color: #e74c3c; margin: 40px 0 30px 0; text-align: center;">Основные Продукты BOC (75-80%)</h2>

                <div class="product-card">
                    <h3>🦽 Стандартные Коляски (M06) - $200-$800</h3>
                    <ul>
                        <li>Ручные инвалидные коляски для мобильности после выписки</li>
                        <li>Легкие транспортные кресла</li>
                        <li>Усиленные модели для пациентов с избыточным весом</li>
                        <li><strong>Потенциал Дохода:</strong> $80K-$200K 1-й Год (200-300 единиц)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>⚡ Электрические Коляски (M06A) - $2,500-$20,000</h3>
                    <ul>
                        <li>Сложные реабилитационные электрические кресла</li>
                        <li>Стандартные электрические мобильные устройства</li>
                        <li>Экстренные прокатные единицы доступны</li>
                        <li><strong>Потенциал Дохода:</strong> $100K-$400K 1-й Год (20-40 единиц)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🛏️ Больничные Кровати (DM11) - $800-$3,500</h3>
                    <ul>
                        <li>Полуэлектрические регулируемые кровати</li>
                        <li>Полностью электрические модели с воздушными матрасами</li>
                        <li>Бариатрические больничные кровати (до 1000 фунтов)</li>
                        <li><strong>Потенциал Дохода:</strong> $120K-$350K 1-й Год (80-120 единиц)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🚶 Ходунки и Трости (M05) - $50-$400</h3>
                    <ul>
                        <li>Стандартные и роликовые ходунки</li>
                        <li>Коленные ходунки для травм нижних конечностей</li>
                        <li>Четвероногие трости и вспомогательные средства для ходьбы</li>
                        <li><strong>Потенциал Дохода:</strong> $40K-$100K 1-й Год (250-400 единиц)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🫁 Кислородное Оборудование (DM28/29) - $1,500-$5,000</h3>
                    <ul>
                        <li>Кислородные концентраторы (аренда и покупка)</li>
                        <li>Портативные кислородные системы</li>
                        <li>Экстренная служба доставки кислорода</li>
                        <li><strong>Потенциал Дохода:</strong> $100K-$300K 1-й Год (40-80 установок)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🛁 Безопасность в Ванной (DM02/DM03) - $100-$800</h3>
                    <ul>
                        <li>Туалеты и прикроватные унитазы</li>
                        <li>Стулья для душа и скамейки для ванны</li>
                        <li>Поручни и защитные перила</li>
                        <li><strong>Потенциал Дохода:</strong> $60K-$150K 1-й Год (200-350 единиц)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🏋️ Подъемники для Пациентов (DM21/22) - $800-$3,500</h3>
                    <ul>
                        <li>Подъемники типа Hoyer</li>
                        <li>Подъемники с положения сидя в положение стоя</li>
                        <li>Потолочные рельсовые системы (установка дополнительно)</li>
                        <li><strong>Потенциал Дохода:</strong> $60K-$100K 1-й Год (20-40 единиц)</li>
                    </ul>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Назад к Портфолио</a>
            </div>
        </div>

        <!-- UZBEK -->
        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>🚨 STRATEGIYA 1</h1>
                <h2 style="font-size: 2em; margin-top: 10px;">Shoshilinch Kasalxona Yetkazib Berish</h2>
                <p style="font-size: 1.3em; margin-top: 15px;">Kasalxonalar va Chiqarish Bo'limlariga 2-4 Soat Kafolatlangan Yetkazib Berish</p>
            </div>

            <div class="section">
                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Portelga Qaytish</a>
                
                <div class="revenue-amount">1-Yil Maqsadi: $560K - $1.6M</div>

                <h2 style="font-size: 2.5em; color: #e74c3c; margin: 40px 0 30px 0; text-align: center;">Asosiy Kontseptsiya</h2>
                
                <div class="product-card">
                    <h3>🎯 Biznes Modeli</h3>
                    <p><strong>Maqsad:</strong> O'sha kun bemorlarni chiqarish uchun zudlik bilan DME yetkazib berishni talab qiladigan kasalxona chiqarish bo'limlari</p>
                    <ul>
                        <li><strong>Kafolatlangan 2-4 Soat Yetkazib Berish</strong> kasalxona chiqarish zonalariga</li>
                        <li><strong>BOC Litsenziyalangan Uskuna (75-80%)</strong> - aravachalar, karavotlar, yurishgichlar, kislorod</li>
                        <li><strong>Shoshilinch O'rnatish Xizmati (20-25%)</strong> - oq qo'lqop o'rnatish va bemorlarni o'rgatish</li>
                        <li><strong>To'g'ridan-To'g'ri Kasalxona Hisob-Kitob</strong> - bemor yotgan paytda sug'urta oldindan ruxsati</li>
                        <li><strong>Premium Narxlar</strong> tezlik va kafolatlangan yetkazib berish bilan oqlanadi</li>
                    </ul>
                </div>

                <h2 style="font-size: 2.5em; color: #e74c3c; margin: 40px 0 30px 0; text-align: center;">Asosiy BOC Mahsulotlari (75-80%)</h2>

                <div class="product-card">
                    <h3>🦽 Standart Aravachalar (M06) - $200-$800</h3>
                    <ul>
                        <li>Chiqarilgandan keyingi harakatlanish uchun qo'l bilan harakatlanadigan aravachalar</li>
                        <li>Yengil transport kreslo</li>
                        <li>Ortiqcha vazn bemorlari uchun mustahkamlangan modellar</li>
                        <li><strong>Daromad Potentsiali:</strong> $80K-$200K 1-Yil (200-300 birlik)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>⚡ Elektr Aravachalar (M06A) - $2,500-$20,000</h3>
                    <ul>
                        <li>Murakkab reabilitatsiya elektr kreslo</li>
                        <li>Standart elektr harakatlanish qurilmalari</li>
                        <li>Shoshilinch ijara birliklari mavjud</li>
                        <li><strong>Daromad Potentsiali:</strong> $100K-$400K 1-Yil (20-40 birlik)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🛏️ Kasalxona Karavotlari (DM11) - $800-$3,500</h3>
                    <ul>
                        <li>Yarim elektr sozlanuvchi karavotlar</li>
                        <li>Havo matras bilan to'liq elektr modellar</li>
                        <li>Bariatrik kasalxona karavotlari (1000 funtgacha)</li>
                        <li><strong>Daromad Potentsiali:</strong> $120K-$350K 1-Yil (80-120 birlik)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🚶 Yurishgichlar va Tayoqlar (M05) - $50-$400</h3>
                    <ul>
                        <li>Standart va g'ildirakli yurishgichlar</li>
                        <li>Pastki oyoq jarohatlari uchun tizza yurishgichlari</li>
                        <li>To'rt oyoqli tayoqlar va yurish yordamchilari</li>
                        <li><strong>Daromad Potentsiali:</strong> $40K-$100K 1-Yil (250-400 birlik)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🫁 Kislorod Uskunalari (DM28/29) - $1,500-$5,000</h3>
                    <ul>
                        <li>Kislorod konsentratorlari (ijara va sotib olish)</li>
                        <li>Ko'chma kislorod tizimlari</li>
                        <li>Shoshilinch kislorod yetkazib berish xizmati</li>
                        <li><strong>Daromad Potentsiali:</strong> $100K-$300K 1-Yil (40-80 o'rnatish)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🛁 Hammom Xavfsizligi (DM02/DM03) - $100-$800</h3>
                    <ul>
                        <li>Hojatxonalar va yotoq yonidagi unitazlar</li>
                        <li>Dush kreslo va vanna skameyka</li>
                        <li>Tutqichlar va xavfsizlik panjaralar</li>
                        <li><strong>Daromad Potentsiali:</strong> $60K-$150K 1-Yil (200-350 birlik)</li>
                    </ul>
                </div>

                <div class="product-card">
                    <h3>🏋️ Bemorlar Ko'targichlari (DM21/22) - $800-$3,500</h3>
                    <ul>
                        <li>Hoyer tipidagi bemorlar ko'targichlari</li>
                        <li>O'tirish-turish ko'targichlari</li>
                        <li>Ship yo'l tizimlari (o'rnatish qo'shimcha)</li>
                        <li><strong>Daromad Potentsiali:</strong> $60K-$100K 1-Yil (20-40 birlik)</li>
                    </ul>
                </div>

                <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad4/" class="back-link">← Portelga Qaytish</a>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(content => content.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            localStorage.setItem('preferred-language', lang);
            window.scrollTo(0, 0);
        }
        window.addEventListener('DOMContentLoaded', function() {
            const savedLang = localStorage.getItem('preferred-language');
            if (savedLang && ['en', 'ru', 'uz'].includes(savedLang)) switchLanguage(savedLang);
        });
    </script>
</body>
</html>
