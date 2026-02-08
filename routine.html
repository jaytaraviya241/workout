<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jensi's Glow Up Protocol</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
    <style>
        :root {
            --bg: #FAFAF9;
            --surface: #FFFFFF;
            --primary: #57534E;
            --accent: #A8A29E;
            --highlight: #D6D3D1;
            --green: #4ade80;
            --rose: #fda4af;
            --blue-soft: #e0f2fe;
            --blue-dark: #0284c7;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background-color: var(--bg);
            color: var(--primary);
            font-family: 'Plus Jakarta Sans', sans-serif;
            overflow-x: hidden;
        }

        h1, h2, h3, h4, h5 {
            font-family: 'Playfair Display', serif;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        /* HERO SECTION */
        header {
            height: 90vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            opacity: 0;
            animation: fadeIn 1.5s ease forwards;
        }

        h1 {
            font-size: clamp(3rem, 8vw, 6rem);
            line-height: 1;
            margin-bottom: 1rem;
        }

        .subtitle {
            font-size: 1.25rem;
            color: var(--accent);
            letter-spacing: 0.1em;
            text-transform: uppercase;
        }

        .scroll-indicator {
            position: absolute;
            bottom: 2rem;
            animation: bounce 2s infinite;
        }

        /* SECTIONS */
        section {
            margin: 6rem 0;
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease;
        }
        
        section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .section-title {
            font-size: 2.5rem;
            margin-bottom: 3rem;
            text-align: center;
            position: relative;
            display: inline-block;
            left: 50%;
            transform: translateX(-50%);
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 2px;
            background: var(--primary);
        }

        /* CARDS */
        .card {
            background: var(--surface);
            padding: 2rem;
            border-radius: 20px;
            box-shadow: 0 10px 40px -10px rgba(0,0,0,0.05);
            margin-bottom: 2rem;
            border: 1px solid rgba(0,0,0,0.02);
            position: relative;
            overflow: hidden;
        }

        .card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .tag {
            font-family: 'Plus Jakarta Sans', sans-serif;
            font-size: 0.75rem;
            padding: 4px 12px;
            border-radius: 20px;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            font-weight: 700;
        }
        
        .tag-face { background: #ffe4e6; color: #be123c; }
        .tag-body { background: #dcfce7; color: #15803d; }
        .tag-diet { background: #fef9c3; color: #a16207; }

        ul { list-style: none; }
        li {
            margin-bottom: 0.8rem;
            display: flex;
            align-items: flex-start;
            color: #44403C;
            line-height: 1.6;
        }
        
        li::before {
            content: '•';
            color: var(--accent);
            margin-right: 12px;
            font-weight: bold;
        }

        /* TIMELINE */
        .timeline-item {
            display: flex;
            gap: 2rem;
            padding-bottom: 3rem;
            border-left: 1px solid var(--highlight);
            padding-left: 2rem;
            position: relative;
        }
        
        .timeline-item::before {
            content: '';
            position: absolute;
            left: -5px;
            top: 0;
            width: 9px;
            height: 9px;
            background: var(--primary);
            border-radius: 50%;
        }

        .time {
            font-weight: 700;
            min-width: 80px;
            color: var(--accent);
            font-size: 0.9rem;
        }

        /* ANIMATIONS */
        @keyframes fadeIn { to { opacity: 1; } }
        @keyframes bounce { 0%, 20%, 50%, 80%, 100% {transform: translateY(0);} 40% {transform: translateY(-10px);} 60% {transform: translateY(-5px);} }

        /* CHECKLIST */
        .checkbox-wrapper {
            display: flex;
            align-items: center;
            cursor: pointer;
            margin-bottom: 0.5rem;
        }
        
        .checkbox-wrapper input { display: none; }
        
        .custom-check {
            width: 20px;
            height: 20px;
            border: 2px solid var(--highlight);
            border-radius: 50%;
            margin-right: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s;
        }
        
        .checkbox-wrapper input:checked + .custom-check {
            background: var(--primary);
            border-color: var(--primary);
        }
        
        .checkbox-wrapper input:checked + .custom-check::after {
            content: '✓';
            color: white;
            font-size: 12px;
        }

        .completed-text {
            color: var(--accent);
            text-decoration: line-through;
            transition: all 0.2s;
        }

        /* --- WORKOUT TABS --- */
        .workout-tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 1.5rem;
            overflow-x: auto;
            padding-bottom: 10px;
        }

        .tab-btn {
            padding: 8px 16px;
            border: 1px solid var(--highlight);
            border-radius: 20px;
            background: transparent;
            font-family: 'Plus Jakarta Sans', sans-serif;
            cursor: pointer;
            white-space: nowrap;
            transition: all 0.3s;
        }

        .tab-btn.active {
            background: var(--primary);
            color: white;
            border-color: var(--primary);
        }

        .workout-content {
            display: none;
            animation: fadeIn 0.5s;
        }

        .workout-content.active {
            display: block;
        }

        .exercise-item {
            background: #f8fafc;
            padding: 1rem;
            border-radius: 12px;
            margin-bottom: 1rem;
            border-left: 4px solid var(--primary);
        }

        .exercise-item h5 { font-size: 1.1rem; margin-bottom: 0.25rem; }
        .exercise-item p { font-size: 0.9rem; color: #64748b; margin:0;}

        /* MOBILE */
        @media (max-width: 600px) {
            h1 { font-size: 3.5rem; }
            .timeline-item { flex-direction: column; gap: 0.5rem; border-left: none; padding-left: 0; }
            .timeline-item::before { display: none; }
        }
    </style>
</head>
<body>

    <header>
        <p class="subtitle">Personalized Protocol</p>
        <h1>Jensi's<br><em>Transformation</em></h1>
        <p class="subtitle" style="margin-top:1rem; text-transform:none; font-style:italic;">Face Slimming • Posture Correction • Glow Skin</p>
        <div class="scroll-indicator">↓</div>
    </header>

    <div class="container">
        
        <!-- SECTION 1: THE DIAGNOSIS -->
        <section>
            <h2 class="section-title">The Goals</h2>
            <div class="card">
                <h3>1. Face Sculpting <span class="tag tag-face">Urgent</span></h3>
                <p><strong>Diagnosis:</strong> Puffy face due to water retention (salt/sugar) and lack of lymphatic drainage. "Roundness" masks your natural bone structure.</p>
                <div style="margin-top:1rem; padding-top:1rem; border-top:1px dashed #eee;">
                    <strong>The Fix:</strong>
                    <ul>
                        <li>Gua Sha / Manual Lymphatic Massage (Morning & Night)</li>
                        <li>Reduce Sodium intake after 6 PM (No chips/salty snacks).</li>
                        <li><strong>Exercise:</strong> "The Ceiling Kiss" & "Balloon Pose" (See routine)</li>
                    </ul>
                </div>
            </div>

            <div class="card">
                <h3>2. Posture & Core <span class="tag tag-body">Body</span></h3>
                <p><strong>Diagnosis:</strong> "Tall Girl Slouch." Hunching causes the belly to protrude and creates a "pooch" even if you are slim. Side fat (love handles) needs oblique work.</p>
                <div style="margin-top:1rem; padding-top:1rem; border-top:1px dashed #eee;">
                    <strong>The Fix:</strong>
                    <ul>
                        <li><strong>Pilates over Cardio:</strong> Builds deep core strength (transverse abdominis) to flatten the belly.</li>
                        <li><strong>Wall Angels:</strong> To open up rounded shoulders and stand tall (6ft proud!).</li>
                        <li><strong>Plank Dips:</strong> To snatch the waist and target side fat.</li>
                    </ul>
                </div>
            </div>
            
            <div class="card">
                <h3>3. Skin Recovery <span class="tag tag-face">Glow</span></h3>
                <p><strong>Diagnosis:</strong> Tanning, pimples, and dark circles suggest inflammation and sun damage.</p>
                <div style="margin-top:1rem; padding-top:1rem; border-top:1px dashed #eee;">
                    <strong>The Fix:</strong>
                    <ul>
                        <li><strong>Internal:</strong> Anti-inflammatory diet (Turmeric, Green Tea, No Dairy).</li>
                        <li><strong>External:</strong> Strict SPF re-application (Every 3 hours).</li>
                        <li><strong>Dark Circles:</strong> Sleep at 10:30 PM strict (Cortisol management).</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- SECTION 2: THE ROUTINE -->
        <section>
            <h2 class="section-title">Daily Protocol</h2>
            
            <!-- Morning -->
            <div class="timeline-item">
                <div class="time">7:00 AM</div>
                <div style="width:100%">
                    <h3>Wake & Hydrate</h3>
                    <label class="checkbox-wrapper">
                        <input type="checkbox" onclick="toggleTask(this)">
                        <div class="custom-check"></div>
                        <span>1 Glass Warm Water + Lemon (Flushes toxins/Puffiness)</span>
                    </label>
                    <label class="checkbox-wrapper">
                        <input type="checkbox" onclick="toggleTask(this)">
                        <div class="custom-check"></div>
                        <span>1 Amla (Vitamin C for Collagen/Skin)</span>
                    </label>
                    <label class="checkbox-wrapper">
                        <input type="checkbox" onclick="toggleTask(this)">
                        <div class="custom-check"></div>
                        <span><strong>Face Yoga (5 Mins):</strong> 20x Balloon Puffs, 10x Ceiling Kisses.</span>
                    </label>
                </div>
            </div>

            <!-- WORKOUT SECTION -->
            <div class="timeline-item">
                <div class="time">7:10 AM</div>
                <div style="width:100%">
                    <h3>5-Day Sculpting Plan (45 Min)</h3>
                    <p style="margin-bottom:1rem; color:var(--accent); font-size:0.9rem;">Target: Belly Fat, Side Fat, & Posture.</p>
                    
                    <div class="workout-tabs">
                        <button class="tab-btn active" onclick="openTab('mon')">Mon</button>
                        <button class="tab-btn" onclick="openTab('tue')">Tue</button>
                        <button class="tab-btn" onclick="openTab('wed')">Wed</button>
                        <button class="tab-btn" onclick="openTab('thu')">Thu</button>
                        <button class="tab-btn" onclick="openTab('fri')">Fri</button>
                    </div>

                    <!-- MONDAY -->
                    <div id="mon" class="workout-content active">
                        <h4>M: CORE DEEP DIVE (Belly Fat Focus)</h4>
                        <br>
                        <div class="exercise-item">
                            <h5>1. Plank (Hold)</h5>
                            <p>3 sets x 45-60 seconds. Keep back straight. Squeeze glutes.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>2. Leg Raises</h5>
                            <p>3 sets x 15 reps. Targets lower pouch. Don't let feet touch ground.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>3. Dead Bugs</h5>
                            <p>3 sets x 20 reps (slow). Flattens the ribcage.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>4. Cobra Stretch</h5>
                            <p>2 mins. Lengthens abs after crunching.</p>
                        </div>
                    </div>

                    <!-- TUESDAY -->
                    <div id="tue" class="workout-content">
                        <h4>T: POSTURE LIFT (Upper Body)</h4>
                        <br>
                        <div class="exercise-item">
                            <h5>1. Wall Angels</h5>
                            <p>3 sets x 15 reps. Stand against wall, arms up/down like making snow angel.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>2. Supermans</h5>
                            <p>3 sets x 12 reps. Lying on stomach, lift chest and legs. Strengthens lower back.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>3. Bird-Dog</h5>
                            <p>3 sets x 12 reps each side. For balance and core stability.</p>
                        </div>
                    </div>

                    <!-- WEDNESDAY -->
                    <div id="wed" class="workout-content">
                        <h4>W: SWEAT & DETOX (Face Slimming HIIT)</h4>
                        <br>
                        <div class="exercise-item">
                            <h5>1. Jumping Jacks</h5>
                            <p>3 mins total. Gets lymph moving to reduce puffy face.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>2. Mountain Climbers</h5>
                            <p>3 sets x 30 seconds. Burns calories fast.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>3. High Knees</h5>
                            <p>3 sets x 30 seconds. Lift knees to chest.</p>
                        </div>
                    </div>

                    <!-- THURSDAY -->
                    <div id="thu" class="workout-content">
                        <h4>Th: WAIST SNATCHER (Side Fat)</h4>
                        <br>
                        <div class="exercise-item">
                            <h5>1. Russian Twists</h5>
                            <p>3 sets x 20 reps. Twist torso fully side to side.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>2. Side Planks</h5>
                            <p>3 sets x 30 sec hold (each side). Targets love handles.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>3. Bicycle Crunches</h5>
                            <p>3 sets x 20 reps. Elbow to opposite knee.</p>
                        </div>
                    </div>

                    <!-- FRIDAY -->
                    <div id="fri" class="workout-content">
                        <h4>F: PILATES FULL BODY (Lengthening)</h4>
                        <br>
                        <div class="exercise-item">
                            <h5>1. Glute Bridges</h5>
                            <p>3 sets x 20 reps. Squeeze at top.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>2. Donkey Kicks</h5>
                            <p>3 sets x 15 reps each leg.</p>
                        </div>
                        <div class="exercise-item">
                            <h5>3. 100s (Pilates)</h5>
                            <p>Hold legs up, pump arms 100 times. Ultimate core burner.</p>
                        </div>
                    </div>

                </div>
            </div>

            <!-- Skin Prep -->
            <div class="timeline-item">
                <div class="time">8:20 AM</div>
                <div style="width:100%">
                    <h3>Skin Defense Layer</h3>
                    <ul>
                        <li>Face Wash (Gentle - No harsh scrubbing on pimples)</li>
                        <li><strong>Ice Roller:</strong> 2 mins upward strokes (Depuffs eyes/cheeks).</li>
                        <li>Vitamin C Serum (Fades dark spots/Tan)</li>
                        <li>Vitamin B5 (Hydrates without oiliness)</li>
                        <li><strong>SPF 50 (Critical):</strong> Apply even if staying indoors.</li>
                    </ul>
                </div>
            </div>

            <!-- Nutrition -->
            <div class="timeline-item">
                <div class="time">Daytime</div>
                <div style="width:100%">
                    <h3>Internal Repair</h3>
                    <div class="card" style="background:#fcfaf8; border:none;">
                        <h4>🥗 Lunch Idea (Anti-Bloat)</h4>
                        <p>Grilled Chicken/Paneer + Cucumber Salad + Curd. (Avoid excess wheat/rice - carbs retain water).</p>
                    </div>
                    <label class="checkbox-wrapper">
                        <input type="checkbox" onclick="toggleTask(this)">
                        <div class="custom-check"></div>
                        <span>Drink 3L Water (Set hourly reminders)</span>
                    </label>
                </div>
            </div>

            <!-- Night -->
            <div class="timeline-item">
                <div class="time">9:30 PM</div>
                <div style="width:100%">
                    <h3>Recovery & Repair</h3>
                    <label class="checkbox-wrapper">
                        <input type="checkbox" onclick="toggleTask(this)">
                        <div class="custom-check"></div>
                        <span>Doctor's Cream on Dark Spots</span>
                    </label>
                    <label class="checkbox-wrapper">
                        <input type="checkbox" onclick="toggleTask(this)">
                        <div class="custom-check"></div>
                        <span><strong>Posture Check:</strong> Sleep on back (prevents face wrinkles).</span>
                    </label>
                    <label class="checkbox-wrapper">
                        <input type="checkbox" onclick="toggleTask(this)">
                        <div class="custom-check"></div>
                        <span>Haldi Milk (Inflammation killer)</span>
                    </label>
                </div>
            </div>
            
        </section>

    </div>

    <script>
        // Reveal on Scroll
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('section').forEach(section => {
            observer.observe(section);
        });

        // Task Toggle Logic
        function toggleTask(checkbox) {
            const text = checkbox.nextElementSibling.nextElementSibling;
            if (checkbox.checked) {
                text.classList.add('completed-text');
                gsap.to(text, { x: 5, duration: 0.2 });
            } else {
                text.classList.remove('completed-text');
                gsap.to(text, { x: 0, duration: 0.2 });
            }
        }

        // Workout Tabs Logic
        function openTab(dayName) {
            // Hide all
            var i, x, tablinks;
            x = document.getElementsByClassName("workout-content");
            for (i = 0; i < x.length; i++) {
                x[i].style.display = "none";
                x[i].classList.remove('active');
            }
            // Deactivate buttons
            tablinks = document.getElementsByClassName("tab-btn");
            for (i = 0; i < tablinks.length; i++) {
                tablinks[i].className = tablinks[i].className.replace(" active", "");
            }
            // Show target
            document.getElementById(dayName).style.display = "block";
            // Wait a tick for animation
            setTimeout(() => {
                document.getElementById(dayName).classList.add('active');
            }, 10);
            
            // Activate button (need event target, but simpler here: loop find by text/id mapping if needed, or just rely on the onclick binding passing 'this' if we changed it, but here we just used ID. Let's fix the button active state.)
            // Actually, I need to pass the event or find the button. Let's just fix the button logic to be simpler:
            // RERUN logic:
            const buttons = document.querySelectorAll('.tab-btn');
            buttons.forEach(btn => {
                if(btn.textContent.toLowerCase().includes(dayName.substring(0,3))) {
                     btn.classList.add('active');
                }
            });
        }

        // Hero Parallax
        document.addEventListener('mousemove', (e) => {
            const moveX = (e.clientX - window.innerWidth / 2) * 0.01;
            const moveY = (e.clientY - window.innerHeight / 2) * 0.01;
            gsap.to('h1', { x: moveX, y: moveY, duration: 1 });
        });
    </script>
</body>
</html>
