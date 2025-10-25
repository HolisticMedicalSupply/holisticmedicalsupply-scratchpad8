<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strategy 1: Emergency Hospital Same-Day Delivery - COMPLETE</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; line-height: 1.6; color: #333; background: linear-gradient(135deg, #ff6b6b, #ee5a6f); padding: 20px; }
        .container { max-width: 1400px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .language-toggle { position: sticky; top: 20px; z-index: 1000; background: rgba(255,255,255,0.98); padding: 15px 40px; display: flex; justify-content: center; gap: 15px; border-bottom: 3px solid #e74c3c; }
        .lang-btn { padding: 12px 30px; border: 2px solid #e74c3c; background: white; color: #e74c3c; border-radius: 8px; cursor: pointer; font-size: 1.1em; font-weight: bold; }
        .lang-btn.active { background: #e74c3c; color: white; }
        .header { background: linear-gradient(135deg, #c0392b, #e74c3c); color: white; padding: 60px 40px; text-align: center; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .section-title { font-size: 2.5em; color: #c0392b; margin-bottom: 30px; text-align: center; border-bottom: 4px solid #e74c3c; padding-bottom: 15px; }
        .product-card { background: #fff5f5; padding: 20px; border-radius: 10px; border-left: 4px solid #e74c3c; margin: 15px 0; }
        .revenue-box { background: linear-gradient(135deg, #c0392b, #e74c3c); color: white; padding: 30px; border-radius: 15px; text-align: center; margin: 25px 0; }
        .revenue-amount { font-size: 3em; font-weight: bold; margin: 15px 0; }
        .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin: 30px 0; }
        .stat-box { background: linear-gradient(135deg, #c0392b, #e74c3c); color: white; padding: 30px; border-radius: 15px; text-align: center; }
        .stat-number { font-size: 3em; font-weight: bold; margin-bottom: 10px; }
        ul.benefits { list-style: none; padding: 0; }
        ul.benefits li { padding: 12px; margin: 8px 0; background: #fff5f5; border-radius: 6px; border-left: 4px solid #e74c3c; }
        ul.benefits li::before { content: '✓ '; color: #27ae60; font-weight: bold; margin-right: 10px; }
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-top: 20px; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
    </style>
</head>
<body>
    <div class="container">
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 English</button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 Русский</button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 O'zbek</button>
        </div>

        <!-- ENGLISH CONTENT -->
        <div class="lang-content active" id="content-en">
            <div class="header">
                <h1>🚨 STRATEGY 1: Emergency Hospital Same-Day Delivery</h1>
                <p style="font-size: 1.4em;">Rapid Response DME for Hospital Discharge Patients</p>
                <p style="font-size: 1.2em; margin-top: 15px;">Licensed DME Equipment (70-75%) + Complementary Hospital Discharge Products (25-30%)</p>
            </div>

            <div class="section">
                <h2 class="section-title">💰 Revenue Model</h2>
                <div class="revenue-box">
                    <h4 style="font-size: 1.8em;">Year 1 Revenue Target</h4>
                    <div class="revenue-amount">$560K - $1.6M</div>
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 20px; text-align: left;">
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Licensed DME Equipment</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$400K-$1.2M</p>
                            <p>70-75% from BOC-licensed medical equipment</p>
                        </div>
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Complementary Products</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$160K-$400K</p>
                            <p>25-30% from discharge support products</p>
                        </div>
                    </div>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><div class="stat-number">Same-Day</div><div>Delivery Promise</div></div>
                    <div class="stat-box"><div class="stat-number">50-75%</div><div>Gross Margins</div></div>
                    <div class="stat-box"><div class="stat-number">$500-3K</div><div>Average Order Value</div></div>
                    <div class="stat-box"><div class="stat-number">Insurance</div><div>Medicare/Medicaid Coverage</div></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🏥 PRIMARY DME EQUIPMENT (70-75% Revenue)</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <h4>♿ Wheelchairs (M06/M06A/M07)</h4>
                        <p><strong>Products:</strong> Manual wheelchairs (standard, lightweight, transport), power wheelchairs for long-term mobility needs, pediatric wheelchairs for children</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $150-$5,000 depending on type</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $120K-$400K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Essential for patient discharge when mobility is impaired post-surgery, stroke, or injury. Hospitals cannot discharge patients safely without proper mobility equipment at home.</p>
                    </div>

                    <div class="product-card">
                        <h4>🛏️ Hospital Beds (DM11)</h4>
                        <p><strong>Products:</strong> Semi-electric hospital beds with adjustable head/foot sections, full-electric beds for maximum comfort, bariatric beds for higher weight capacity (600-1000 lbs)</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $800-$3,500 per bed</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $100K-$350K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Required for post-operative recovery, long-term bed rest, hospice care, pressure ulcer prevention. Patients transitioning from hospital to home need adjustable beds for safety and recovery.</p>
                    </div>

                    <div class="product-card">
                        <h4>🚶 Walkers & Rollators (M05)</h4>
                        <p><strong>Products:</strong> Standard folding walkers, 2-wheel walkers for stability, 4-wheel rollators with seats and hand brakes, bariatric walkers for higher weight capacity</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $40-$350 each</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $60K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Most common discharge equipment for hip/knee replacement, stroke recovery, general weakness. Prevents falls and provides independence during recovery.</p>
                    </div>

                    <div class="product-card">
                        <h4>🚽 Commodes & Toilet Safety (DM02)</h4>
                        <p><strong>Products:</strong> Bedside commodes (standard and bariatric), raised toilet seats with arms, toilet safety frames, 3-in-1 commode chairs</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $50-$300 each</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $40K-$120K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Critical for patients who cannot safely navigate to bathroom. Required for hip/knee replacement, mobility restrictions, overnight toileting needs.</p>
                    </div>

                    <div class="product-card">
                        <h4>🩺 Patient Lifts (DM21/DM22)</h4>
                        <p><strong>Products:</strong> Ceiling-mounted lifts for permanent installation, portable floor lifts (Hoyer-style), sit-to-stand lifts for partial mobility, sling sets for different body types</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $800-$4,000 per lift + slings</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $50K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Prevents caregiver injury when transferring immobile patients. Required for bariatric patients, paralysis cases, severe weakness, hospice care at home.</p>
                    </div>

                    <div class="product-card">
                        <h4>🛌 Pressure Relief Mattresses (DM16)</h4>
                        <p><strong>Products:</strong> Low air loss mattresses for severe pressure ulcer risk, alternating pressure mattresses for moderate risk, foam overlays for prevention, bariatric pressure mattresses</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $200-$3,000 depending on sophistication</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $30K-$100K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Prevents pressure ulcers in bedridden patients. Required for patients with existing pressure sores, limited mobility, diabetes, hospice care.</p>
                    </div>

                    <div class="product-card">
                        <h4>💉 Wound VAC Systems (DM17)</h4>
                        <p><strong>Products:</strong> Negative pressure wound therapy units (rental and purchase), portable wound VAC for mobility, wound VAC supplies and dressings</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $2,500-$5,000 for unit + $200-500/month supplies</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $25K-$100K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Advanced wound healing for surgical wounds, pressure ulcers, diabetic wounds. Allows patients to leave hospital sooner while continuing wound therapy at home.</p>
                    </div>

                    <div class="product-card">
                        <h4>💨 Oxygen Equipment (DM28/DM29)</h4>
                        <p><strong>Products:</strong> Oxygen concentrators (stationary 5-10L), portable oxygen concentrators for mobility, oxygen cylinders for backup/emergency, humidifiers and accessories</p>
                        <p style="margin: 10px 0;"><strong>Price Range:</strong> $600-$3,500 for equipment + monthly supplies</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $40K-$150K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Hospitals Need This:</strong> Required for COPD, CHF, pneumonia recovery, post-surgical respiratory support. Cannot discharge oxygen-dependent patients without home oxygen setup.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📦 COMPLEMENTARY HOSPITAL DISCHARGE PRODUCTS (25-30%)</h2>
                
                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Pre-Configured Discharge Kits</h3>
                    <ul class="benefits">
                        <li><strong>Hip/Knee Replacement Recovery Kit ($150-300):</strong> Reacher/grabber tool, sock aid, dressing stick, long-handled shoehorn, toilet safety frame, non-slip bath mat, ice therapy wraps</li>
                        <li><strong>Stroke Recovery Home Kit ($200-400):</strong> One-handed utensils and kitchen tools, button hook and zipper pull, non-slip mats throughout house, medication organizers, large-button phone, bath safety equipment</li>
                        <li><strong>Post-Surgery Comfort Kit ($100-250):</strong> Bed wedge pillows, neck support pillows, ice packs and heat therapy, compression stockings, surgical scar treatment, antibacterial wound care</li>
                        <li><strong>Wound Care Supply Kit ($75-200):</strong> Gauze pads and rolls, medical tape, antibiotic ointment, wound cleaning solutions, disposable gloves, bandages assortment</li>
                        <li><strong>Incontinence Management Kit ($120-280):</strong> Adult diapers (2-week supply), disposable underpads (chux), skin barrier cream, moisture wipes, waterproof mattress protector</li>
                        <li><strong>Diabetic Care Kit ($150-350):</strong> Blood glucose meter with 3-month strips, lancets and lancing device, sharps container, glucose tablets, diabetic logbook, carrying case</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Est. Annual Revenue: $80K-$200K</p>
                </div>

                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Bathroom & Home Safety Products</h3>
                    <ul class="benefits">
                        <li><strong>Grab Bars & Safety Rails ($30-150 each):</strong> Suction grab bars for rentals, permanent mount grab bars, bed rails for fall prevention, stair handrails</li>
                        <li><strong>Shower & Bath Safety ($40-200):</strong> Tub transfer benches, shower chairs with backs, non-slip bath mats, handheld shower heads, long-handled bath sponges</li>
                        <li><strong>Lighting & Motion Sensors ($25-100):</strong> Motion-activated nightlights for hallways/bathroom, plug-in LED path lighting, sensor nightlights for bedroom</li>
                        <li><strong>Anti-Slip Solutions ($15-80):</strong> Non-slip stair treads, area rug pads, anti-slip floor treatment, threshold ramps for wheelchairs</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Est. Annual Revenue: $40K-$100K</p>
                </div>

                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Daily Living Aids & Comfort</h3>
                    <ul class="benefits">
                        <li><strong>Reaching & Mobility Tools ($20-80):</strong> Reacher/grabber tools (26-32 inch), dressing sticks, sock aids, long shoehorns, leg lifters for bed transfers</li>
                        <li><strong>Therapeutic Pillows & Cushions ($30-150):</strong> Orthopedic bed wedges, donut cushions for hemorrhoids/pressure relief, neck roll pillows, lumbar support pillows</li>
                        <li><strong>Monitoring & Safety ($50-200):</strong> Medical alert systems (monthly subscription), medication reminder devices, fall detection pendants, emergency call buttons</li>
                        <li><strong>Nutritional Support ($40-120):</strong> Easy-grip utensils, plate guards and scoop dishes, one-handed cutting boards, non-spill cups with handles</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Est. Annual Revenue: $40K-$100K</p>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Implementation Strategy</h2>
                
                <div class="product-card">
                    <h3>Hospital Partnership Approach</h3>
                    <ul class="benefits">
                        <li><strong>Discharge Planner Relationships:</strong> Build strong relationships with social workers and case managers who control discharge equipment decisions</li>
                        <li><strong>Same-Day Delivery Guarantee:</strong> Stock most common items, deliver within 2-4 hours of hospital order, available 7 days a week including evenings</li>
                        <li><strong>Insurance Pre-Verification:</strong> Handle all Medicare/Medicaid paperwork before delivery, reduce hospital administrative burden, guarantee payment acceptance</li>
                        <li><strong>Quality & Safety Standards:</strong> All equipment sanitized and safety-checked before delivery, provide instruction and setup at patient's home, 24/7 customer support for issues</li>
                        <li><strong>Start with 2-3 Hospitals:</strong> Focus on high-volume discharge centers, prove reliability and speed, expand based on performance</li>
                    </ul>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><div class="stat-number">2-4 hrs</div><div>Average Delivery Time</div></div>
                    <div class="stat-box"><div class="stat-number">2-3</div><div>Initial Hospital Partners</div></div>
                    <div class="stat-box"><div class="stat-number">300-800</div><div>Deliveries Year 1</div></div>
                    <div class="stat-box"><div class="stat-number">High</div><div>Recurring Revenue Potential</div></div>
                </div>
            </div>
        </div>

        <!-- RUSSIAN CONTENT - COMPLETE TRANSLATION -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>🚨 СТРАТЕГИЯ 1: Экстренная Доставка в Больницы в Тот Же День</h1>
                <p style="font-size: 1.4em;">Быстрое Реагирование DME для Пациентов Выписываемых из Больницы</p>
                <p style="font-size: 1.2em; margin-top: 15px;">Лицензированное DME Оборудование (70-75%) + Дополнительные Продукты для Выписки (25-30%)</p>
            </div>

            <div class="section">
                <h2 class="section-title">💰 Модель Дохода</h2>
                <div class="revenue-box">
                    <h4 style="font-size: 1.8em;">Целевой Доход за 1-й Год</h4>
                    <div class="revenue-amount">$560K - $1.6M</div>
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 20px; text-align: left;">
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Лицензированное DME Оборудование</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$400K-$1.2M</p>
                            <p>70-75% от BOC-лицензированного медицинского оборудования</p>
                        </div>
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Дополнительные Продукты</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$160K-$400K</p>
                            <p>25-30% от продуктов поддержки выписки</p>
                        </div>
                    </div>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><div class="stat-number">В Тот Же День</div><div>Гарантия Доставки</div></div>
                    <div class="stat-box"><div class="stat-number">50-75%</div><div>Валовая Маржа</div></div>
                    <div class="stat-box"><div class="stat-number">$500-3K</div><div>Средняя Стоимость Заказа</div></div>
                    <div class="stat-box"><div class="stat-number">Страховка</div><div>Покрытие Medicare/Medicaid</div></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🏥 ОСНОВНОЕ DME ОБОРУДОВАНИЕ (70-75% Дохода)</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <h4>♿ Инвалидные Коляски (M06/M06A/M07)</h4>
                        <p><strong>Продукты:</strong> Ручные инвалидные коляски (стандартные, легкие, транспортные), электрические инвалидные коляски для долгосрочных потребностей в мобильности, педиатрические инвалидные коляски для детей</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $150-$5,000 в зависимости от типа</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $120K-$400K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Необходимо для выписки пациентов, когда мобильность нарушена после операции, инсульта или травмы. Больницы не могут безопасно выписать пациентов без надлежащего оборудования для мобильности дома.</p>
                    </div>

                    <div class="product-card">
                        <h4>🛏️ Больничные Кровати (DM11)</h4>
                        <p><strong>Продукты:</strong> Полуэлектрические больничные кровати с регулируемыми секциями головы/ног, полностью электрические кровати для максимального комфорта, бариатрические кровати для более высокой грузоподъемности (600-1000 фунтов)</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $800-$3,500 за кровать</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $100K-$350K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Требуется для послеоперационного восстановления, длительного постельного режима, хосписной помощи, предотвращения пролежней. Пациентам, переходящим из больницы домой, нужны регулируемые кровати для безопасности и восстановления.</p>
                    </div>

                    <div class="product-card">
                        <h4>🚶 Ходунки и Роллаторы (M05)</h4>
                        <p><strong>Продукты:</strong> Стандартные складные ходунки, двухколесные ходунки для стабильности, четырехколесные роллаторы с сиденьями и ручными тормозами, бариатрические ходунки для более высокой грузоподъемности</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $40-$350 каждый</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $60K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Наиболее распространенное оборудование для выписки после замены тазобедренного/коленного сустава, восстановления после инсульта, общей слабости. Предотвращает падения и обеспечивает независимость во время восстановления.</p>
                    </div>

                    <div class="product-card">
                        <h4>🚽 Судна и Туалетная Безопасность (DM02)</h4>
                        <p><strong>Продукты:</strong> Прикроватные судна (стандартные и бариатрические), приподнятые сиденья унитаза с подлокотниками, рамы безопасности унитаза, стулья-судна 3-в-1</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $50-$300 каждое</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $40K-$120K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Критически важно для пациентов, которые не могут безопасно добраться до ванной комнаты. Требуется для замены тазобедренного/коленного сустава, ограничений мобильности, ночных туалетных потребностей.</p>
                    </div>

                    <div class="product-card">
                        <h4>🩺 Подъемники для Пациентов (DM21/DM22)</h4>
                        <p><strong>Продукты:</strong> Потолочные подъемники для постоянной установки, портативные напольные подъемники (тип Хойер), подъемники из положения сидя в положение стоя для частичной мобильности, наборы строп для разных типов тела</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $800-$4,000 за подъемник + стропы</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $50K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Предотвращает травмы ухаживающих при перемещении неподвижных пациентов. Требуется для бариатрических пациентов, случаев паралича, тяжелой слабости, хосписной помощи на дому.</p>
                    </div>

                    <div class="product-card">
                        <h4>🛌 Матрасы для Снятия Давления (DM16)</h4>
                        <p><strong>Продукты:</strong> Матрасы с низкой потерей воздуха для высокого риска пролежней, матрасы с переменным давлением для умеренного риска, пенные накладки для профилактики, бариатрические матрасы от давления</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $200-$3,000 в зависимости от сложности</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $30K-$100K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Предотвращает пролежни у лежачих пациентов. Требуется для пациентов с существующими пролежнями, ограниченной мобильностью, диабетом, хосписной помощью.</p>
                    </div>

                    <div class="product-card">
                        <h4>💉 Системы VAC для Ран (DM17)</h4>
                        <p><strong>Продукты:</strong> Устройства отрицательной терапии давлением ран (аренда и покупка), портативный VAC для мобильности, расходные материалы и перевязочные материалы для VAC</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $2,500-$5,000 за устройство + $200-500/месяц расходные материалы</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $25K-$100K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Продвинутое заживление ран для хирургических ран, пролежней, диабетических ран. Позволяет пациентам покинуть больницу раньше, продолжая терапию ран дома.</p>
                    </div>

                    <div class="product-card">
                        <h4>💨 Кислородное Оборудование (DM28/DM29)</h4>
                        <p><strong>Продукты:</strong> Кислородные концентраторы (стационарные 5-10L), портативные кислородные концентраторы для мобильности, кислородные цилиндры для резервного/экстренного использования, увлажнители и аксессуары</p>
                        <p style="margin: 10px 0;"><strong>Ценовой Диапазон:</strong> $600-$3,500 за оборудование + ежемесячные расходные материалы</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $40K-$150K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Больницам Это Нужно:</strong> Требуется для ХОБЛ, ХСН, восстановления после пневмонии, послеоперационной респираторной поддержки. Нельзя выписать пациентов, зависящих от кислорода, без домашней кислородной установки.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📦 ДОПОЛНИТЕЛЬНЫЕ ПРОДУКТЫ ДЛЯ ВЫПИСКИ ИЗ БОЛЬНИЦЫ (25-30%)</h2>
                
                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Предварительно Настроенные Комплекты для Выписки</h3>
                    <ul class="benefits">
                        <li><strong>Комплект Восстановления после Замены Тазобедренного/Коленного Сустава ($150-300):</strong> Инструмент для доставания/захвата, помощник для носков, палка для одевания, длинная ложка для обуви, рама безопасности унитаза, нескользящий коврик для ванны, обертывания для ледяной терапии</li>
                        <li><strong>Домашний Комплект Восстановления после Инсульта ($200-400):</strong> Посуда и кухонные инструменты для одной руки, крючок для пуговиц и застежка-молния, нескользящие коврики по всему дому, органайзеры для лекарств, телефон с большими кнопками, оборудование для безопасности ванны</li>
                        <li><strong>Комплект Комфорта после Операции ($100-250):</strong> Клиновые подушки для кровати, подушки для поддержки шеи, ледяные пакеты и термотерапия, компрессионные чулки, лечение хирургического рубца, антибактериальный уход за раной</li>
                        <li><strong>Комплект Материалов для Ухода за Ранами ($75-200):</strong> Марлевые прокладки и рулоны, медицинская лента, антибиотическая мазь, растворы для очистки ран, одноразовые перчатки, ассортимент бинтов</li>
                        <li><strong>Комплект Управления Недержанием ($120-280):</strong> Подгузники для взрослых (запас на 2 недели), одноразовые подкладки (чукс), крем для защиты кожи, влажные салфетки, водонепроницаемый защитный чехол для матраса</li>
                        <li><strong>Комплект Диабетической Помощи ($150-350):</strong> Глюкометр с полосками на 3 месяца, ланцеты и устройство для прокалывания, контейнер для острых предметов, таблетки глюкозы, диабетический журнал, переносной чехол</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Оценка Годового Дохода: $80K-$200K</p>
                </div>

                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Продукты для Безопасности Ванной Комнаты и Дома</h3>
                    <ul class="benefits">
                        <li><strong>Поручни и Перила Безопасности ($30-150 каждый):</strong> Присосочные поручни для аренды, постоянные монтируемые поручни, перила кровати для предотвращения падения, перила лестницы</li>
                        <li><strong>Безопасность Душа и Ванны ($40-200):</strong> Скамьи для переноса ванны, душевые стулья со спинками, нескользящие коврики для ванны, ручные душевые головки, длинные мочалки для ванны</li>
                        <li><strong>Освещение и Датчики Движения ($25-100):</strong> Ночники с активацией движения для коридоров/ванной, вставные светодиодные дорожные фонари, сенсорные ночники для спальни</li>
                        <li><strong>Антискользящие Решения ($15-80):</strong> Нескользящие ступени лестниц, подкладки для ковров, антискользящая обработка пола, пороговые пандусы для инвалидных колясок</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Оценка Годового Дохода: $40K-$100K</p>
                </div>

                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Средства для Повседневной Жизни и Комфорта</h3>
                    <ul class="benefits">
                        <li><strong>Инструменты для Доставания и Мобильности ($20-80):</strong> Инструменты для доставания/захвата (26-32 дюйма), палки для одевания, помощники для носков, длинные ложки для обуви, подъемники ног для перехода в кровать</li>
                        <li><strong>Терапевтические Подушки и Подушечки ($30-150):</strong> Ортопедические клиновидные подушки для кровати, подушки-пончики для геморроя/снятия давления, валики для шеи, подушки для поясничной поддержки</li>
                        <li><strong>Мониторинг и Безопасность ($50-200):</strong> Системы медицинской тревоги (ежемесячная подписка), устройства напоминания о лекарствах, подвески обнаружения падения, кнопки экстренного вызова</li>
                        <li><strong>Питательная Поддержка ($40-120):</strong> Посуда с легким захватом, защитные пластины и совки для тарелок, разделочные доски для одной руки, неразливающиеся чашки с ручками</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Оценка Годового Дохода: $40K-$100K</p>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Стратегия Реализации</h2>
                
                <div class="product-card">
                    <h3>Подход к Партнерству с Больницами</h3>
                    <ul class="benefits">
                        <li><strong>Отношения с Планировщиками Выписки:</strong> Строить прочные отношения с социальными работниками и кейс-менеджерами, которые контролируют решения об оборудовании для выписки</li>
                        <li><strong>Гарантия Доставки в Тот Же День:</strong> Запасать наиболее распространенные товары, доставлять в течение 2-4 часов с момента заказа больницы, доступно 7 дней в неделю включая вечера</li>
                        <li><strong>Предварительная Проверка Страховки:</strong> Обрабатывать всю документацию Medicare/Medicaid перед доставкой, снизить административное бремя больницы, гарантировать принятие оплаты</li>
                        <li><strong>Стандарты Качества и Безопасности:</strong> Все оборудование продезинфицировано и проверено на безопасность перед доставкой, предоставить инструкцию и установку в доме пациента, круглосуточная клиентская поддержка для проблем</li>
                        <li><strong>Начать с 2-3 Больниц:</strong> Сосредоточиться на центрах с высоким объемом выписки, доказать надежность и скорость, расширяться на основе производительности</li>
                    </ul>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><div class="stat-number">2-4 часа</div><div>Среднее Время Доставки</div></div>
                    <div class="stat-box"><div class="stat-number">2-3</div><div>Начальные Партнеры-Больницы</div></div>
                    <div class="stat-box"><div class="stat-number">300-800</div><div>Доставок в 1-й Год</div></div>
                    <div class="stat-box"><div class="stat-number">Высокий</div><div>Потенциал Регулярного Дохода</div></div>
                </div>
            </div>
        </div>

        <!-- UZBEK CONTENT - COMPLETE TRANSLATION -->
        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>🚨 STRATEGIYA 1: O'sha Kunning O'zida Shifoxonalarga Favqulodda Yetkazib Berish</h1>
                <p style="font-size: 1.4em;">Shifoxonadan Chiqarilgan Bemorlar uchun Tezkor Javob DME</p>
                <p style="font-size: 1.2em; margin-top: 15px;">Litsenziyalangan DME Uskuna (70-75%) + Chiqarish uchun Qo'shimcha Mahsulotlar (25-30%)</p>
            </div>

            <div class="section">
                <h2 class="section-title">💰 Daromad Modeli</h2>
                <div class="revenue-box">
                    <h4 style="font-size: 1.8em;">1-Yil Uchun Maqsadli Daromad</h4>
                    <div class="revenue-amount">$560K - $1.6M</div>
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 20px; text-align: left;">
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Litsenziyalangan DME Uskuna</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$400K-$1.2M</p>
                            <p>BOC-litsenziyalangan tibbiy uskunadan 70-75%</p>
                        </div>
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Qo'shimcha Mahsulotlar</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$160K-$400K</p>
                            <p>Chiqarish qo'llab-quvvatlash mahsulotlaridan 25-30%</p>
                        </div>
                    </div>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><div class="stat-number">O'sha Kuni</div><div>Yetkazib Berish Kafolati</div></div>
                    <div class="stat-box"><div class="stat-number">50-75%</div><div">Yalpi Marja</div></div>
                    <div class="stat-box"><div class="stat-number">$500-3K</div><div>O'rtacha Buyurtma Qiymati</div></div>
                    <div class="stat-box"><div class="stat-number">Sug'urta</div><div>Medicare/Medicaid Qoplami</div></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🏥 ASOSIY DME USKUNA (70-75% Daromad)</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <h4>♿ Nogironlar Aravachalari (M06/M06A/M07)</h4>
                        <p><strong>Mahsulotlar:</strong> Qo'l aravachalari (standart, engil, transport), uzoq muddatli harakatlanish ehtiyojlari uchun elektr aravachalari, bolalar uchun pediatrik aravachalar</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Turga qarab $150-$5,000</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $120K-$400K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> Operatsiya, insult yoki jarohatlandan keyin harakatlanish buzilganda bemorni chiqarish uchun zarur. Shifoxonalar bemorlarni uyda to'g'ri harakatlanish uskunasiz xavfsiz chiqara olmaydi.</p>
                    </div>

                    <div class="product-card">
                        <h4>🛏️ Shifoxona Karavotlari (DM11)</h4>
                        <p><strong>Mahsulotlar:</strong> Bosh/oyoq bo'limlari bilan sozlanishi mumkin bo'lgan yarim elektr shifoxona karavotlari, maksimal qulaylik uchun to'liq elektr karavotlar, yuqori vazn sig'imi uchun bariatrik karavotlar (600-1000 funt)</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Har bir karavot uchun $800-$3,500</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $100K-$350K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> Operatsiyadan keyingi tiklanish, uzoq muddatli yotoq rejimi, hospis parvarishi, bosim jarohatlarga qarshi himoya uchun talab qilinadi. Shifoxonadan uyga o'tgan bemorlarga xavfsizlik va tiklanish uchun sozlanishi mumkin bo'lgan karavotlar kerak.</p>
                    </div>

                    <div class="product-card">
                        <h4>🚶 Yurishgichlar va Rollatorlar (M05)</h4>
                        <p><strong>Mahsulotlar:</strong> Standart yig'iladigan yurishgichlar, barqarorlik uchun 2 g'ildirakli yurishgichlar, o'rindiqlar va qo'l tormozlari bilan 4 g'ildirakli rollatorlar, yuqori vazn sig'imi uchun bariatrik yurishgichlar</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Har biri $40-$350</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $60K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> Kestirib/tizza almashtirish, insultdan tiklanish, umumiy zaiflik uchun eng keng tarqalgan chiqarish uskunasi. Yiqilishlarni oldini oladi va tiklanish paytida mustaqillikni ta'minlaydi.</p>
                    </div>

                    <div class="product-card">
                        <h4>🚽 Hojatxonalar va Hojatxona Xavfsizligi (DM02)</h4>
                        <p><strong>Mahsulotlar:</strong> Karavot yonidagi hojatxonalar (standart va bariatrik), qo'llar bilan ko'tarilgan hojatxona o'rindiqlari, hojatxona xavfsizlik ramkalari, 3-bitta-1 hojatxona stullari</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Har biri $50-$300</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $40K-$120K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> Hojatxonaga xavfsiz yeta olmaydigan bemorlar uchun muhim ahamiyatga ega. Kestirib/tizza almashtirish, harakatlanish cheklovlari, tungi hojatxona ehtiyojlari uchun talab qilinadi.</p>
                    </div>

                    <div class="product-card">
                        <h4>🩺 Bemorlar Ko'targichlari (DM21/DM22)</h4>
                        <p><strong>Mahsulotlar:</strong> Doimiy o'rnatish uchun shiftga o'rnatiladigan ko'targichlar, portativ pol ko'targichlar (Hoyer turi), qisman harakatlanish uchun o'tirishdan turishga ko'targichlar, turli xil tana turlari uchun osilma to'plamlari</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Ko'targich + osilmalar uchun $800-$4,000</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $50K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> Harakatsiz bemorlarni ko'chirishda parvarishchi jarohatlarini oldini oladi. Bariatrik bemorlar, falaj holatlari, og'ir zaiflik, uyda hospis parvarishi uchun talab qilinadi.</p>
                    </div>

                    <div class="product-card">
                        <h4>🛌 Bosimni Engillashtiradigan Matraslar (DM16)</h4>
                        <p><strong>Mahsulotlar:</strong> Og'ir bosim jarohatlari xavfi uchun past havo yo'qotish matraslari, o'rtacha xavf uchun almashirib turadigan bosim matraslari, oldini olish uchun ko'pikli qoplamalar, bariatrik bosim matraslari</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Murakkablikka qarab $200-$3,000</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $30K-$100K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> Yotgan bemorlarda bosim jarohatlarga qarshi himoya qiladi. Mavjud bosim jarohatlar, cheklangan harakatlanish, diabet, hospis parvarishi bo'lgan bemorlar uchun talab qilinadi.</p>
                    </div>

                    <div class="product-card">
                        <h4>💉 Yara VAC Tizimlari (DM17)</h4>
                        <p><strong>Mahsulotlar:</strong> Salbiy bosim yara terapiyasi birliklari (ijara va sotib olish), harakatlanish uchun portativ yara VAC, yara VAC ta'minoti va bog'lamalar</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Birlik uchun $2,500-$5,000 + oyiga $200-500 ta'minot</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $25K-$100K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> Jarrohlik yaralar, bosim jarohatlari, diabetik yaralar uchun ilg'or yara davolash. Bemorlarga uyda yara terapiyasini davom ettirayotganda shifoxonani tezroq tark etishga imkon beradi.</p>
                    </div>

                    <div class="product-card">
                        <h4>💨 Kislorod Uskunalari (DM28/DM29)</h4>
                        <p><strong>Mahsulotlar:</strong> Kislorod konsentratorlari (statsionar 5-10L), harakatlanish uchun portativ kislorod konsentratorlari, zaxira/favqulodda holat uchun kislorod tsilindrlari, namlagichlar va aksessuarlar</p>
                        <p style="margin: 10px 0;"><strong>Narx Oralig'i:</strong> Uskuna uchun $600-$3,500 + oylik ta'minot</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $40K-$150K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Shifoxonalarga Bu Kerak:</strong> XOBL, YuYe, pnevmoniyadan tiklanish, operatsiyadan keyingi nafas olish qo'llab-quvvatlash uchun talab qilinadi. Kislorodga bog'liq bemorlarni uyda kislorod o'rnatilmasdan chiqarib bo'lmaydi.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📦 SHIFOXONADAN CHIQARISH UCHUN QO'SHIMCHA MAHSULOTLAR (25-30%)</h2>
                
                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Oldindan Sozlangan Chiqarish Komplektlari</h3>
                    <ul class="benefits">
                        <li><strong>Kestirib/Tizza Almashtirish Tiklanish Komplekti ($150-300):</strong> Olish/ushlab olish vositasi, paypoq yordamchisi, kiyinish tayoqchasi, uzun poyabzal qoshiq, hojatxona xavfsizlik ramkasi, hojatxona uchun sirpanmaydigan to'shak, muz terapiyasi o'rashlari</li>
                        <li><strong>Insultdan Tiklanish Uy Komplekti ($200-400):</strong> Bir qo'lli idish-tovoqlar va oshxona vositalari, tugma ilgagi va fermuar tortgichi, uy bo'ylab sirpanmaydigan to'shaklar, dori tashkilotchilari, katta tugmali telefon, hojatxona xavfsizlik uskunalari</li>
                        <li><strong>Operatsiyadan Keyingi Qulaylik Komplekti ($100-250):</strong> Karavot uchun qirqim yostiqlar, bo'yin qo'llab-quvvatlash yostiqlari, muz paketlari va issiqlik terapiyasi, kompressiya paypoqlari, jarrohlik chandiqni davolash, antibakterial yara parvarishi</li>
                        <li><strong>Yara Parvarishi Ta'minoti Komplekti ($75-200):</strong> Doka yostiqlar va rulonlar, tibbiy lenta, antibiotikar malham, yaralarni tozalash yechimlari, bir martalik qo'lqoplar, bog'lamalar assortimenti</li>
                        <li><strong>Nazorat Boshqaruvi Komplekti ($120-280):</strong> Kattalar pamperslari (2 haftalik zahira), bir martalik ostki to'shaklar (chux), teri to'sig'i kremi, namlik artgichlari, suv o'tkazmaydigan matras himoyachisi</li>
                        <li><strong>Diabetik Parvarish Komplekti ($150-350):</strong> 3 oylik chiziqlar bilan qon glyukoza o'lchagichi, lansetlar va lanset qurilmasi, o'tkir narsalar uchun konteyner, glyukoza tabletkalari, diabetik jurnal, ko'tarma quti</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Yillik Daromad Bahosi: $80K-$200K</p>
                </div>

                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Hammom va Uy Xavfsizlik Mahsulotlari</h3>
                    <ul class="benefits">
                        <li><strong>Tutqichlar va Xavfsizlik Panjaralari ($30-150 har biri):</strong> Ijara uchun so'rg'ich tutqichlar, doimiy o'rnatiladigan tutqichlar, yiqilishni oldini olish uchun karavot panjaralari, zinalar tutqichlari</li>
                        <li><strong>Dush va Hammom Xavfsizligi ($40-200):</strong> Vanna o'tish skameykalari, orqasi bilan dush stullari, sirpanmaydigan hammom to'shaklari, qo'lda ushlab turiladigan dush boshlari, uzun hammom gubkalari</li>
                        <li><strong>Yoritish va Harakat Sensorlari ($25-100):</strong> Yo'laklar/hammom uchun harakat bilan faollashadigan tungi chiroqlar, ulash LED yo'l yoritish, yotoqxona uchun sensor tungi chiroqlar</li>
                        <li><strong>Anti-Sirpanish Yechimlari ($15-80):</strong> Sirpanmaydigan zinalar qadamlari, maydon gilamlari yostiqlari, anti-sirpanish pol davolash, nogironlar aravachalari uchun ostonali rampalar</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Yillik Daromad Bahosi: $40K-$100K</p>
                </div>

                <div class="product-card">
                    <h3 style="color: #c0392b; margin-bottom: 15px;">Kundalik Hayot Yordamlari va Qulaylik</h3>
                    <ul class="benefits">
                        <li><strong>Yetib Olish va Harakatlanish Vositalari ($20-80):</strong> Yetib olish/ushlab olish vositalari (26-32 dyuym), kiyinish tayoqchalari, paypoq yordamchilari, uzun poyabzal qoshiqlari, karavotga o'tish uchun oyoq ko'targichlar</li>
                        <li><strong>Terapevtik Yostiqlar va Yostiqchalar ($30-150):</strong> Ortopedik karavot qirqimlari, boshoqlar/bosim engillashtirishlar uchun donut yostiqchalar, bo'yin rulonli yostiqlar, bel qo'llab-quvvatlash yostiqlari</li>
                        <li><strong>Monitoring va Xavfsizlik ($50-200):</strong> Tibbiy ogohlantirish tizimlari (oylik obuna), dori eslatma qurilmalari, yiqilishni aniqlash marjonlari, favqulodda qo'ng'iroq tugmalari</li>
                        <li><strong>Oziq-ovqat Qo'llab-Quvvatlash ($40-120):</strong> Oson tutqichli idish-tovoqlar, tovoq qo'riqchilari va cho'mich idishlar, bir qo'lli kesish taxtalari, tutqichlari bilan to'kilmaydigan piyolalar</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Yillik Daromad Bahosi: $40K-$100K</p>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Amalga Oshirish Strategiyasi</h2>
                
                <div class="product-card">
                    <h3>Shifoxona Hamkorligi Yondashuvi</h3>
                    <ul class="benefits">
                        <li><strong>Chiqarish Rejalashtirgichlari Munosabatlari:</strong> Chiqarish uskunalari qarorlarini nazorat qiluvchi ijtimoiy ishchilar va holat menejerlari bilan mustahkam munosabatlar qurish</li>
                        <li><strong>O'sha Kunning O'zida Yetkazib Berish Kafolati:</strong> Eng keng tarqalgan narsalarni zaxiraga olish, shifoxona buyurtmasidan 2-4 soat ichida yetkazib berish, kechqurunlarni o'z ichiga olgan holda haftada 7 kun mavjud</li>
                        <li><strong>Sug'urta Oldindan Tekshirish:</strong> Yetkazib berishdan oldin barcha Medicare/Medicaid hujjatlarini boshqarish, shifoxona ma'muriy yukini kamaytirish, to'lovni qabul qilishni kafolatlash</li>
                        <li><strong>Sifat va Xavfsizlik Standartlari:</strong> Barcha uskuna yetkazib berishdan oldin dezinfeksiya qilingan va xavfsizlikka tekshirilgan, bemorning uyida ko'rsatma va o'rnatishni taqdim etish, muammolar uchun 24/7 mijozlar qo'llab-quvvatlash</li>
                        <li><strong>2-3 Shifoxona bilan Boshlash:</strong> Yuqori hajmli chiqarish markazlariga e'tibor qaratish, ishonchlilik va tezlikni isbotlash, ishlashga asoslanib kengayish</li>
                    </ul>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><div class="stat-number">2-4 soat</div><div>O'rtacha Yetkazib Berish Vaqti</div></div>
                    <div class="stat-box"><div class="stat-number">2-3</div><div>Dastlabki Shifoxona Hamkorlari</div></div>
                    <div class="stat-box"><div class="stat-number">300-800</div><div>1-Yilda Yetkazib Berishlar</div></div>
                    <div class="stat-box"><div class="stat-number">Yuqori</div><div>Takroriy Daromad Potentsiali</div></div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(c => c.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(b => b.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            window.scrollTo(0, 0);
        }
    </script>
</body>
</html>
