<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nitin Singhal | Cyber Security Professional</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        /* Custom styles for a professional engineering theme */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0f172a; /* Slate 900 */
            color: #e2e8f0; /* Slate 200 */
            overflow-x: hidden;
        }

        /* Accent color variables - Professional Blue */
        :root {
            --accent-color: #3b82f6; /* Blue 500 */
            --accent-color-hover: #2563eb; /* Blue 600 */
            --card-bg: #1e293b; /* Slate 800 */
        }

        .text-accent { color: var(--accent-color); }
        .bg-accent { background-color: var(--accent-color); }
        .border-accent { border-color: var(--accent-color); }

        .hover\:bg-accent-hover:hover {
            background-color: var(--accent-color-hover);
        }

        /* Subtle Glow effect */
        .text-glow {
            text-shadow: 0 0 8px rgba(59, 130, 246, 0.6);
        }

        /* Section Animation: Fade-in on scroll */
        .fade-in-section {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
            will-change: opacity, visibility;
        }

        .fade-in-section.is-visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Custom button style */
        .btn {
            @apply inline-block font-semibold py-2 px-6 rounded-md transition-all duration-300 transform;
        }
        .btn-primary {
            @apply bg-blue-600 text-white hover:bg-blue-700 hover:-translate-y-1 shadow-lg hover:shadow-blue-500/30;
        }
        .btn-secondary {
            @apply border-2 border-blue-500 text-blue-400 hover:bg-blue-500 hover:text-white;
        }

        /* Card hover effect */
        .info-card {
            border: 1px solid #334155; /* Slate 700 */
            transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;
        }
        .info-card:hover {
            transform: translateY(-5px);
            border-color: var(--accent-color);
            box-shadow: 0 4px 20px rgba(59, 130, 246, 0.15);
        }
    </style>
</head>
<body class="antialiased">

    <header class="fixed w-full top-0 z-50 bg-[#0f172a]/90 backdrop-blur-md border-b border-slate-800">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="flex items-center gap-3" title="Nitin Singhal">
                <svg class="w-10 h-10 text-white" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M50 8.33331L12.5 20.8333V45.8333C12.5 72.0583 28.5333 95.9916 50 100C71.4667 95.9916 87.5 72.0583 87.5 45.8333V20.8333L50 8.33331Z" stroke="currentColor" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
                    <text x="50" y="60" font-family="Inter, sans-serif" font-size="32" font-weight="bold" fill="var(--accent-color)" text-anchor="middle">NS</text>
                </svg>
                <span class="text-xl font-bold text-white tracking-wide hidden sm:block">NITIN SINGHAL</span>
            </a>
            
            <div class="flex items-center space-x-6 md:space-x-8">
                <a href="#about" class="text-slate-300 hover:text-white transition-colors text-sm md:text-base font-medium">About</a>
                <a href="#projects" class="text-slate-300 hover:text-white transition-colors text-sm md:text-base font-medium">Projects</a>
                <a href="#certifications" class="text-slate-300 hover:text-white transition-colors text-sm md:text-base font-medium hidden md:block">Certifications</a>
                
                <a href="#contact" class="px-5 py-2 bg-blue-600 text-white rounded-md hover:bg-blue-700 transition-all duration-300 text-sm font-semibold shadow-md shadow-blue-500/20">
                    Get Connect
                </a>

                <a href="https://linkedin.com/in/nitin-singhal-3935aa2a4" target="_blank" rel="noopener noreferrer" class="text-slate-400 hover:text-white transition-colors" title="LinkedIn">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                </a>
            </div>
        </nav>
    </header>

    <main class="container mx-auto px-6 pt-32 pb-12">

        <section id="home" class="min-h-[70vh] flex flex-col justify-center fade-in-section is-visible">
            <div class="max-w-4xl">
                <h1 class="text-5xl md:text-7xl font-extrabold text-white leading-tight tracking-tight">
                    Aspiring <span class="text-accent text-glow">Cyber Security</span> Learner
                </h1>
                <p class="mt-6 text-xl text-slate-400 max-w-2xl leading-relaxed">
                    Learning cybersecurity with a mindset to defend, detect, and strengthen digital systems against modern threats.
                </p>
                <div class="mt-10 flex flex-col sm:flex-row gap-5">
                    <a href="Nitin_Singhal_Resume.pdf" download="Nitin_Singhal_Resume" class="btn btn-primary flex items-center justify-center gap-2 text-lg px-8 py-3">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                         <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
                        </svg>
                        Download Resume
                    </a>
                    <a href="#about" class="btn btn-secondary flex items-center justify-center text-lg px-8 py-3">
                        Learn More &darr;
                    </a>
                </div>
            </div>
        </section>

        <section id="about" class="py-24 fade-in-section">
            <div class="text-center max-w-3xl mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-white">About Me</h2>
                <div class="w-24 h-1 bg-accent mx-auto mb-10 rounded-full"></div>
                <p class="text-lg text-slate-300 leading-relaxed mb-6">
                    As a dedicated MCA student, I am channeling my strong foundation in computer science and frontend development towards a specialized career in Cyber Security. I am driven by the challenge of anticipating and neutralizing digital threats. 
                </p>
                <p class="text-lg text-slate-300 leading-relaxed">
                    My current focus is on gaining hands-on experience and industry-recognized certifications in key areas like penetration testing, security analysis, and incident response. I am committed to a path of continuous learning to stay ahead in this dynamic field.
                </p>
            </div>
        </section>

        <section id="projects" class="py-24 fade-in-section">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white">Practical Experience & Projects</h2>
                <div class="w-24 h-1 bg-accent mx-auto mt-4 rounded-full"></div>
                <p class="mt-6 text-lg text-slate-400">Applying security concepts to real-world engineering scenarios.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <div class="info-card bg-card-bg p-8 rounded-xl flex flex-col justify-between">
                    <div>
                        <h3 class="text-2xl font-bold text-white mb-3">Password Analyzer</h3>
                        <p class="text-slate-400 mb-6 leading-relaxed">A robust tool built with JavaScript to assess password entropy and strength based on complex cryptographic criteria.</p>
                    </div>
                    <a href="#" class="font-semibold text-accent hover:text-white flex items-center gap-2 transition-colors">View Project <span>&rarr;</span></a>
                </div>
                <div class="info-card bg-card-bg p-8 rounded-xl flex flex-col justify-between">
                    <div>
                        <h3 class="text-2xl font-bold text-white mb-3">Secure Auth System</h3>
                        <p class="text-slate-400 mb-6 leading-relaxed">Implemented a full-stack login architecture utilizing Node.js, bcrypt hashing, JWTs, and strict rate-limiting.</p>
                    </div>
                    <a href="#" class="font-semibold text-accent hover:text-white flex items-center gap-2 transition-colors">View on GitHub <span>&rarr;</span></a>
                </div>
                <div class="info-card bg-card-bg p-8 rounded-xl flex flex-col justify-between">
                    <div>
                        <h3 class="text-2xl font-bold text-white mb-3">Phishing Analyzer</h3>
                        <p class="text-slate-400 mb-6 leading-relaxed">An analysis tool that parses email headers and body content to flag suspicious URLs and identify spoofing indicators.</p>
                    </div>
                    <a href="#" class="font-semibold text-accent hover:text-white flex items-center gap-2 transition-colors">View on GitHub <span>&rarr;</span></a>
                </div>
            </div>
        </section>

        <section id="certifications" class="py-24 fade-in-section">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white">IT Certifications & Skills</h2>
                 <div class="w-24 h-1 bg-accent mx-auto mt-4 rounded-full"></div>
                <p class="mt-6 text-lg text-slate-400">My journey of continuous learning and professional development.</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <div class="info-card bg-card-bg p-8 rounded-xl text-center">
                    <div class="text-white mx-auto mb-6 h-16 w-16 flex items-center justify-center rounded-full bg-blue-600 shadow-lg shadow-blue-500/30">
                         <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" /></svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">CompTIA Security+</h3>
                    <p class="text-slate-400">Covers baseline skills necessary to perform core security functions and pursue an IT security career.</p>
                </div>

                <div class="info-card bg-card-bg p-8 rounded-xl text-center">
                     <div class="text-white mx-auto mb-6 h-16 w-16 flex items-center justify-center rounded-full bg-blue-600 shadow-lg shadow-blue-500/30">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" /></svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">CEH (Ethical Hacker)</h3>
                    <p class="text-slate-400"><span class="font-semibold text-blue-400">[In Progress]</span> Mastering ethical hacking methodologies to lawfully assess systems.</p>
                </div>

                <div class="info-card bg-card-bg p-8 rounded-xl text-center">
                    <div class="text-white mx-auto mb-6 h-16 w-16 flex items-center justify-center rounded-full bg-blue-600 shadow-lg shadow-blue-500/30">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path d="M12 14l9-5-9-5-9 5 9 5z" /><path d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-5.998 12.078 12.078 0 01.665-6.479L12 14z" /><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-5.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222 4 2.222V20" /></svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Cisco CyberOps</h3>
                    <p class="text-slate-400">Training for real-world tasks of security analysts in a Security Operations Center (SOC).</p>
                </div>
            </div>
        </section>

        <section id="contact" class="py-24 fade-in-section">
            <div class="max-w-4xl mx-auto px-6 bg-card-bg p-12 rounded-2xl border border-slate-700 info-card shadow-2xl">
                <div class="text-center mb-10">
                    <h2 class="text-3xl md:text-4xl font-bold text-white">Get In Touch</h2>
                    <div class="w-24 h-1 bg-accent mx-auto mt-4 rounded-full"></div>
                    <p class="text-slate-300 mt-6 text-lg max-w-xl mx-auto">
                        I am actively seeking internship and full-time opportunities. Drop your E-Mail ID below, and I will establish a connection with you.
                    </p>
                </div>

                <form action="https://formspree.io/f/YOUR_UNIQUE_ID" method="POST" class="max-w-md mx-auto">
                    <div class="flex flex-col gap-5">
                        <div class="relative">
                            <input 
                                type="email" 
                                name="email" 
                                placeholder="Enter your secure email address" 
                                required
                                class="w-full bg-slate-900 border border-slate-600 text-white py-3 px-4 rounded-lg focus:outline-none focus:border-blue-500 focus:ring-1 focus:ring-blue-500 transition-all shadow-inner"
                            >
                        </div>
                        <button type="submit" class="btn btn-primary w-full text-lg py-3">
                            Establish Connection
                        </button>
                    </div>
                </form>
                
                <div class="mt-12 text-center pt-8 border-t border-slate-700">
                    <p class="text-sm text-slate-400 mb-2 uppercase tracking-wider font-semibold">Direct Channel</p>
                    <a href="mailto:singhal30n@gmail.com" class="text-blue-400 hover:text-white hover:underline font-medium text-lg transition-colors">
                        singhal30n@gmail.com
                    </a>
                </div>
            </div>
        </section>
    </main>

    <footer class="border-t border-slate-800 bg-[#0f172a]">
        <div class="container mx-auto px-6 py-8 text-center text-slate-500">
            <p>&copy; 2026 Nitin Singhal. Building a Secure Digital Future.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const sections = document.querySelectorAll('.fade-in-section');

            const observer = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('is-visible');
                        observer.unobserve(entry.target); 
                    }
                });
            }, {
                root: null,
                rootMargin: '0px',
                threshold: 0.15 
            });

            sections.forEach(section => {
                observer.observe(section);
            });
            
            // Trigger animation immediately for sections already in viewport on load
            setTimeout(() => {
                const homeSection = document.getElementById('home');
                if(homeSection) homeSection.classList.add('is-visible');
            }, 100);
        });
    </script>
</body>
</html>
