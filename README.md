# Dr.-Scott
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Scott Eilers | Coaching</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
    <style>
        /* CSS Reset */
        *, *::before, *::after {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        html, body {
            overflow-x: hidden;
            width: 100%;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0A0A0A;
            color: #D1D5DB; /* gray-300 */
            line-height: 1.7;
        }
        .container {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            padding: 0 1.5rem;
        }
        h1, h2 {
            font-weight: 900;
            line-height: 1.2;
            color: #FFFFFF;
        }
        h1 {
            font-size: 2.75rem;
        }
        h2 {
            font-size: 2.25rem;
        }
        /* This is the key for pacing */
        .copy p {
            margin-bottom: 1.75rem;
            max-width: 650px;
            margin-left: auto;
            margin-right: auto;
            font-size: 1.125rem;
            line-height: 1.8;
        }
        .cta-button {
            display: inline-block;
            background: linear-gradient(to right, #F97316, #EA580C);
            color: #FFFFFF;
            padding: 1rem 2.5rem;
            border-radius: 0.5rem;
            text-decoration: none;
            font-weight: 700;
            font-size: 1.125rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 20px rgba(249, 115, 22, 0.25);
            border: 1px solid #F97316;
        }
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(249, 115, 22, 0.4);
        }
        .section {
            padding: 6rem 0;
        }
        .fascination-headline {
            text-align: center;
            font-size: 2.5rem;
            font-weight: 900;
            color: #FFFFFF;
            margin-bottom: 4rem;
            line-height: 1.3;
        }
        .fascination-headline span {
            background: -webkit-linear-gradient(#FDBA74, #F97316);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .vsl-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin: 2.5rem auto;
            cursor: pointer;
            border: 2px solid #374151;
            border-radius: 0.75rem;
            overflow: hidden;
            transition: border-color 0.3s ease;
        }
        .vsl-container:hover {
            border-color: #F97316;
        }
        .vsl-thumbnail {
            width: 100%;
            height: auto;
            display: block;
            background-color: #000;
        }
        .play-button-overlay {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 80px;
            height: 80px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            transition: transform 0.2s ease, background-color 0.2s ease;
            backdrop-filter: blur(5px);
        }
        .vsl-container:hover .play-button-overlay {
            transform: translate(-50%, -50%) scale(1.1);
            background-color: rgba(249, 115, 22, 0.8);
        }
        .play-button-icon {
            color: white;
            font-size: 40px;
            border-style: solid;
            border-width: 20px 0 20px 35px;
            border-color: transparent transparent transparent white;
            margin-left: 5px;
        }
        .vsl-text {
            text-align: center;
            font-weight: 600;
            color: #FDBA74; /* amber-300 */
            margin-top: 1rem;
            letter-spacing: 0.5px;
        }
        .bullet-point {
            display: flex;
            align-items: flex-start;
        }
        .bullet-icon {
            color: #F97316;
            margin-right: 1rem;
            flex-shrink: 0;
            margin-top: 5px;
        }
        .faq-item {
            border-bottom: 1px solid #374151;
            padding: 1.5rem 0;
        }
        .faq-question {
            font-weight: 600;
            font-size: 1.25rem;
            color: #FFFFFF;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .faq-answer {
            margin-top: 1rem;
            color: #9CA3AF; /* gray-400 */
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s ease-in-out;
        }
        .faq-symbol {
            transition: transform 0.3s ease;
            font-size: 1.5rem;
            color: #F97316;
        }
        /* Responsive Adjustments */
        @media (max-width: 768px) {
            h1 { font-size: 2.25rem; }
            h2, .fascination-headline { font-size: 2rem; }
            .section { padding: 4rem 0; }
            .copy p { font-size: 1rem; }
        }
    </style>
</head>
<body>

    <!-- HERO SECTION -->
    <header class="section text-center">
        <div class="container">
            <p class="font-semibold text-orange-500 uppercase tracking-widest">FOR THE HIGH-FUNCTIONING PROFESSIONAL WHO FEELS ANYTHING BUT.</p>
            <h1 class="mt-4">Climb Out of the Void in Weeks, Not Years, Using a Battle-Tested Method That Isn't Therapy.</h1>
            <p class="mt-6 text-xl text-gray-400 max-w-3xl mx-auto">And do it without the endless, unstructured "talk and hope" sessions that have left you feeling more stuck than when you started.</p>

            <a href="https://docs.google.com/document/d/1ORck1Ycv8EazRVce8QrPYTVLeTSdArxMSnWqDXpJZYE/edit?usp=sharing" target="_blank" class="block">
                <div class="vsl-container">
                    <img src="https://placehold.co/600x338/000000/FFFFFF?text=Dr.+Eilers+Coaching" alt="Video thumbnail for coaching overview" class="vsl-thumbnail">
                    <div class="play-button-overlay">
                        <div class="play-button-icon"></div>
                    </div>
                </div>
                <p class="vsl-text">Click Here To See The: VSL I WROTE FOR YOU</p>
            </a>

            <div class="mt-12">
                <a href="#offer" class="cta-button">Schedule Your Session & Start The Climb</a>
            </div>
        </div>
    </header>

    <!-- PROBLEM IDENTIFICATION -->
    <section class="section">
        <div class="container text-center copy">
            <h2 class="fascination-headline">When <span>"I'm Fine"</span> is a Four-Letter Word.</h2>
            <p>On the outside, you have it together.</p>
            <p>The career, the responsibilities, maybe even the family.</p>
            <p>You're competent.</p>
            <p>You're reliable.</p>
            <p>But inside... there’s a void.</p>
            <p>A quiet, persistent numbness that drains the color from everything.</p>
            <p>You feel stretched thin, running on fumes, and the burnout is so deep it feels like part of your personality now.</p>
            <p>You’ve tried the things you're "supposed" to do.</p>
            <p>You sat through therapy sessions, nodding along, hoping for a breakthrough that never came.</p>
            <p>Just talk. More talk.</p>
            <p>You’ve downloaded the meditation apps, tried the self-care checklists... and it all feels like adding more chores to an already impossible list.</p>
            <p>And the worst part?</p>
            <p>The fear that this is it.</p>
            <p>That this gray, exhausting, empty feeling is your new normal.</p>
            <p>That you'll just stay stuck here, forever going through the motions.</p>
            <p>But what if the problem isn't you?</p>
            <p>What if the problem is the approach?</p>
        </div>
    </section>

    <!-- ORIGIN STORY -->
    <section class="section bg-black">
        <div class="container text-center copy">
            <h2 class="fascination-headline">I Had to Go Through Hell to <span>Find the Way Out.</span></h2>
            <p>I know that void. I've lived in it.</p>
            <p>Years ago, my life looked good on paper too. Clinical psychologist, husband, father.</p>
            <p>But I was drowning in a severe depression so crippling it pushed me to the edge of disability.</p>
            <p>I did what I was trained to do. I went to therapy. I talked. And I waited for something to change.</p>
            <p>Nothing did.</p>
            <p>The standard approaches failed me. They felt passive. Theoretical.</p>
            <p>They weren't built for the intensity of the fight I was in.</p>
            <p>My breakthrough didn't come from a textbook. It came from desperation.</p>
            <p>I had to forge my own tools, my own strategies, right there in the trenches.</p>
            <p>Small, concrete actions that created real momentum.</p>
            <p>A system for climbing, not just talking about the hole I was in.</p>
            <p>It was intense. It was practical. And it worked.</p>
            <p>It pulled me out and helped me build a life I never could have imagined.</p>
            <p>I realized then that conventional therapy, with its lack of structure and its focus on just talking, is a broken model for people who are truly "down in it."</p>
            <p>It's why I offer coaching—it's the opposite of that passive model.</p>
        </div>
    </section>

    <!-- SOLUTION REVELATION -->
    <section class="section">
        <div class="container">
            <h2 class="fascination-headline">The Opposite of 'Talk + Hope':<br><span>A System for Real Movement.</span></h2>
            <p class="text-center text-xl max-w-3xl mx-auto mb-16">This isn't about endlessly analyzing your past. It's about building your future, one meaningful step at a time. Here is what this new approach gives you:</p>
            <div class="max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-8">
                
                <div class="bullet-point">
                    <div class="bullet-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" viewBox="0 0 256 256"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">A Framework for Cutting Through the Fog</h3>
                        <p class="text-gray-400 mt-2">So you can make clear, confident decisions without second-guessing... becoming the leader of your own life, not just a passenger.</p>
                    </div>
                </div>

                <div class="bullet-point">
                    <div class="bullet-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" viewBox="0 0 256 256"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">A System to Plug Daily "Energy Drains"</h3>
                        <p class="text-gray-400 mt-2">So you finally have something left in the tank for your family and yourself... becoming someone who has the capacity for joy again, not just responsibility.</p>
                    </div>
                </div>

                <div class="bullet-point">
                    <div class="bullet-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" viewBox="0 0 256 256"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">Intense, One-on-One Strategy Sessions</h3>
                        <p class="text-gray-400 mt-2">So you leave with a concrete plan, not just vague hopes... becoming the architect of your own relief.</p>
                    </div>
                </div>

                <div class="bullet-point">
                    <div class="bullet-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" viewBox="0 0 256 256"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">Actionable, Battle-Tested Tools</h3>
                        <p class="text-gray-400 mt-2">So you have a sense of control and power on the hardest days... becoming resilient in the face of real-world stress.</p>
                    </div>
                </div>

                <div class="bullet-point">
                    <div class="bullet-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" viewBox="0 0 256 256"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">A Method to Interrupt Stuck Patterns</h3>
                        <p class="text-gray-400 mt-2">So you stop having the same bad day over and over... becoming someone who consciously creates their life instead of just reacting to it.</p>
                    </div>
                </div>

                <div class="bullet-point">
                    <div class="bullet-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" viewBox="0 0 256 256"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">Unwavering Accountability</h3>
                        <p class="text-gray-400 mt-2">So you are seen, heard, and held to the standard of the person you want to become... feeling present, connected, and truly alive again.</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- PRODUCT INTRODUCTION -->
    <section class="section bg-black">
        <div class="container text-center copy">
            <h2 class="fascination-headline">This Isn't a Session. <span>It's a Lifeline.</span></h2>
            <p>Forget everything you think you know about "getting help."</p>
            <p>This isn't a passive hour of venting into the void.</p>
            <p>It's an active, collaborative, and intensely focused intervention designed to create a shift.</p>
            <p>Each session is a dedicated block of time where we roll up our sleeves and work.</p>
            <p>We identify the single biggest lever you can pull *right now* to create change, and we build a clear, simple plan to pull it.</p>
            <p>You've already wasted enough time feeling stuck.</p>
            <p>This is your chance to invest in focused, strategic action that yields a real return: your life back.</p>
        </div>
    </section>

    <!-- OFFER STRUCTURE -->
    <section id="offer" class="section">
        <div class="container text-center">
            <h2 class="fascination-headline">Your Path Forward <span>Starts Here.</span></h2>
            <p class="text-xl max-w-2xl mx-auto">Choose the session that fits your needs. There are no long-term commitments, only a single, powerful step forward.</p>
            <div class="flex flex-col md:flex-row justify-center items-stretch gap-8 mt-16">
                <!-- 30 Minute Option -->
                <div class="bg-[#111111] p-8 rounded-lg border border-gray-800 w-full max-w-sm flex flex-col">
                    <h3 class="text-2xl font-bold text-white">30-Minute Session</h3>
                    <p class="text-5xl font-black text-orange-400 my-4">$150</p>
                    <p class="text-gray-400 flex-grow">A focused, high-impact session to tackle a specific challenge or sticking point.</p>
                    <ul class="text-left my-8 space-y-3 text-gray-300">
                        <li class="flex items-center"><svg class="w-5 h-5 text-orange-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>Ideal for targeted problem-solving.</li>
                        <li class="flex items-center"><svg class="w-5 h-5 text-orange-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>Gain immediate clarity and an action plan.</li>
                    </ul>
                    <a href="https://drsccotteilers.as.me/schedule.php?appointmentType=35828471" target="_blank" class="cta-button w-full text-center mt-auto">Book a 30-Min Session</a>
                </div>
                <!-- 60 Minute Option -->
                <div class="bg-[#111111] p-8 rounded-lg border-2 border-orange-500 w-full max-w-sm flex flex-col transform md:scale-105">
                    <h3 class="text-2xl font-bold text-white">60-Minute Session</h3>
                    <p class="text-5xl font-black text-orange-400 my-4">$300</p>
                    <p class="text-gray-400 flex-grow">A deep-dive strategy session to map out a comprehensive path forward.</p>
                    <ul class="text-left my-8 space-y-3 text-gray-300">
                        <li class="flex items-center"><svg class="w-5 h-5 text-orange-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>Best for initial consultations.</li>
                        <li class="flex items-center"><svg class="w-5 h-5 text-orange-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>Develop a multi-step game plan.</li>
                    </ul>
                    <a href="https://drsccotteilers.as.me/schedule.php?appointmentType=35828399" target="_blank" class="cta-button w-full text-center mt-auto">Book a 60-Min Session</a>
                </div>
            </div>
            <p class="mt-12 text-gray-500 max-w-3xl mx-auto"><strong>My Promise:</strong> I am all-in on your breakthrough. I bring the full force of my professional expertise and personal experience to every single session. Your time will be respected, your struggle will be honored, and our work will be 100% focused on getting you results.</p>
            <p class="mt-4 text-gray-400"><strong>For recurring visits, please email me directly at dr.scott.eilers@gmail.com.</strong></p>
        </div>
    </section>

    <!-- FAQ SECTION -->
    <section class="section">
        <div class="container max-w-3xl mx-auto">
            <h2 class="fascination-headline">What You're <span>Probably Thinking...</span></h2>
            <div id="faq-container">
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Is this just therapy under a different name?</span>
                        <span class="faq-symbol">+</span>
                    </div>
                    <div class="faq-answer">
                        <p>No. Therapy is often passive, open-ended, and focused on diagnosis and processing. My coaching is active, structured, and goal-oriented. We are not diagnosing or treating a mental illness; we are building a concrete, personalized strategy for you to get from where you are to where you want to be. It's about forward movement, not just analysis.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>$150-$300 is a lot for one session. Is it worth it?</span>
                        <span class="faq-symbol">+</span>
                    </div>
                    <div class="faq-answer">
                        <p>Consider the cost of staying stuck. How much is another month, or another year, of feeling numb, burnt out, and disconnected worth? This is not an expense; it's an investment in a high-impact intervention designed to save you time and pain by avoiding the slow, often ineffective, traditional route.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>What if this is too intense for me?</span>
                        <span class="faq-symbol">+</span>
                    </div>
                    <div class="faq-answer">
                        <p>The process is intense because the problem is intense. The gentle, "talk and hope" methods haven't worked. This approach is for people who are ready for a real challenge because they are tired of the pain of staying the same. We move at a pace that creates change, but you are always in control.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>I'm so busy. How can I find the time?</span>
                        <span class="faq-symbol">+</span>
                    </div>
                    <div class="faq-answer">
                        <p>How much time and energy is your current state costing you every day? In lost productivity, in strained relationships, in sheer exhaustion? A single, focused 30 or 60-minute session is designed to give you back hours of your life by providing you with tools that create energy, clarity, and efficiency.</p>
                    </div>
                </div>
            </div>
            <div class="text-center mt-16">
                <a href="#offer" class="cta-button">It's Time to Feel Alive Again. Schedule Your Session.</a>
            </div>
        </div>
    </section>
    
    <footer class="text-center py-12 border-t border-gray-900">
        <p class="text-gray-600">&copy; 2024 Dr. Scott Eilers. All Rights Reserved.</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const faqContainer = document.getElementById('faq-container');
            faqContainer.addEventListener('click', function(e) {
                const question = e.target.closest('.faq-question');
                if (question) {
                    const answer = question.nextElementSibling;
                    const symbol = question.querySelector('.faq-symbol');
                    const allAnswers = faqContainer.querySelectorAll('.faq-answer');
                    const allSymbols = faqContainer.querySelectorAll('.faq-symbol');

                    const isOpening = !answer.style.maxHeight || answer.style.maxHeight === '0px';

                    // Close all others
                    allAnswers.forEach(ans => ans.style.maxHeight = '0px');
                    allSymbols.forEach(sym => {
                        sym.textContent = '+';
                        sym.style.transform = 'rotate(0deg)';
                    });

                    // Open the clicked one if it was closed
                    if (isOpening) {
                        answer.style.maxHeight = answer.scrollHeight + 'px';
                        symbol.textContent = '-';
                        symbol.style.transform = 'rotate(45deg)';
                    }
                }
            });
        });
    </script>

</body>
</html>
