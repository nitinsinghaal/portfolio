<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nitin Singhal | Cyber Security Professional</title>
    
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        /* Custom styles for a crisp, cyber-focused theme */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #030712; /* Near-black background */
            color: #d1d5db; /* Light gray for text */
        }

        /* Accent color variables */
        :root {
            --accent-color: #10b981; /* A sharp emerald green */
            --accent-color-hover: #34d399;
            --card-bg: #111827; /* Dark gray for cards */
        }

        .text-accent {
            color: var(--accent-color);
        }
        
        .bg-accent {
            background-color: var(--accent-color);
        }
        
        .border-accent {
            border-color: var(--accent-color);
        }

        .hover\:bg-accent-hover:hover {
            background-color: var(--accent-color-hover);
        }

        /* Glow effect for accent elements */
        .glow {
            box-shadow: 0 0 5px var(--accent-color), 0 0 10px var(--accent-color);
        }
        .text-glow {
            text-shadow: 0 0 8px var(--accent-color);
        }

        /* Section Animation: Fade-in on scroll */
        .fade-in-section {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
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
            @apply bg-accent text-gray-900 hover:bg-accent-hover hover:scale-105;
        }
        .btn-secondary {
            @apply border-2 border-accent text-accent hover:bg-accent hover:text-gray-900;
        }

        /* Card hover effect */
        .info-card {
            border: 1px solid #374151; /* gray-700 */
            transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;
        }
        .info-card:hover {
            transform: translateY(-5px);
            border-color: var(--accent-color);
            box-shadow: 0 4px 20px rgba(16, 185, 129, 0.1);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header class="sticky top-0 z-50 bg-opacity-80 backdrop-blur-md border-b border-gray-800">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center gap-2" title="Nitin Singhal">
                <svg class="w-10 h-10 text-white" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M50 8.33331L12.5 20.8333V45.8333C12.5 72.0583 28.5333 95.9916 50 100C71.4667 95.9916 87.5 72.0583 87.5 45.8333V20.8333L50 8.33331Z" stroke="white" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
                    <text x="50" y="60" font-family="Inter, sans-serif" font-size="32" font-weight="bold" fill="var(--accent-color)" text-anchor="middle">NS</text>
                </svg>
                <span class="text-xl font-bold text-white hidden sm:block">NITIN SINGHAL</span>
            </a>
            
            <div class="flex items-center space-x-4 md:space-x-8">
                <a href="#about" class="text-gray-300 hover:text-accent transition-colors text-sm md:text-base">About</a>
                <a href="#projects" class="text-gray-300 hover:text-accent transition-colors text-sm md:text-base">Projects</a>
                <a href="#certifications" class="text-gray-300 hover:text-accent transition-colors text-sm md:text-base hidden md:block">Certifications</a>
                
                <a href="#contact" class="px-4 py-2 border border-accent text-accent rounded-md hover:bg-accent hover:text-gray-400 transition-all duration-300 text-sm font-semibold">
                    Get Connected
                </a>

                <a href="https://linkedin.com/in/nitin-singhal-3935aa2a4" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-accent transition-colors" title="LinkedIn">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                </a>
            </div>
        </nav>
    </header>
            </div>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">

        <!-- Hero Section -->
        <section id="home" class="min-h-[80vh] flex flex-col justify-center">
            <div class="max-w-4xl">
                <h1 class="text-4xl md:text-6xl font-bold text-white leading-tight">
                    Aspiring <span class="text-accent text-glow">Cyber Security</span> Learner
                </h1>
                <p class="mt-4 text-lg md:text-xl text-gray-400 max-w-2xl">
Learning cybersecurity with a mindset to defend, detect, and strengthen digital systems.                </p>
                <div class="mt-8 flex flex-col sm:flex-row gap-4">
                    <a href="C:\Users\ADMIN\OneDrive\Desktop\Nitin_Singhal_Resume.pdf" 
                    download="Nitin_Singhal_Resume" 
                    class="btn btn-primary flex items-center justify-center gap-2">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                     <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
                    </svg>
                    Download Resume
                    </a>
                    <a href="#about" class="btn btn-secondary text-center">
                        Learn More &darr;
                    </a>
                </div>
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-24 fade-in-section">
            <div class="text-center max-w-3xl mx-auto">
                <h2 class="text-3xl font-bold mb-4">About Me</h2>
                <div class="w-24 h-1 bg-accent mx-auto mb-8"></div>
                <p class="text-lg text-gray-300 leading-relaxed mb-4">
                    As a dedicated MCA student, I am channeling my strong foundation in computer science and frontend development towards a specialized career in Cyber Security. I am driven by the challenge of anticipating and neutralizing digital threats. 
                </p>
                <p class="text-lg text-gray-300 leading-relaxed">
                    My current focus is on gaining hands-on experience and industry-recognized certifications in key areas like penetration testing, security analysis, and incident response. I am committed to a path of continuous learning to stay ahead in this dynamic field.
                </p>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-24 fade-in-section">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-3xl font-bold">Practical Experience & Projects</h2>
                <div class="w-24 h-1 bg-accent mx-auto mt-4"></div>
                <p class="mt-4 text-lg text-gray-400">Applying security concepts to real-world scenarios.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <!-- Project Card 1 -->
                <div class="info-card bg-card-bg p-6 rounded-lg">
                    <h3 class="text-xl font-semibold text-white mb-2">Password Strength Checker</h3>
                    <p class="text-gray-400 mb-4">A simple tool built with vanilla JavaScript to check the strength of a password based on multiple criteria.</p>
                    <a href="C:\Users\ADMIN\OneDrive\Desktop\project\Password Analyzer.html"target="_blank" class="font-semibold text-accent hover:underline">View Project  &rarr;</a>
                </div>
                <!-- Project Card 2 -->
                <div class="info-card bg-card-bg p-6 rounded-lg">
                    <h3 class="text-xl font-semibold text-white mb-2">Secure Authentication System</h3>
                    <p class="text-gray-400 mb-4">Implemented a full-stack login system with Node.js and React, featuring password hashing, JWTs, and rate limiting to prevent brute-force attacks.</p>
                    <a href="#" class="font-semibold text-accent hover:underline">View on GitHub &rarr;</a>
                </div>
                <!-- Project Card 3 -->
                <div class="info-card bg-card-bg p-6 rounded-lg">
                    <h3 class="text-xl font-semibold text-white mb-2">Phishing Email Analyzer</h3>
                    <p class="text-gray-400 mb-4">A tool to analyze email headers and content to identify suspicious links and common phishing indicators, aiming to classify potential threats.</p>
                    <a href="#" class="font-semibold text-accent hover:underline">View on GitHub &rarr;</a>
                </div>
            </div>
        </section>


        <!-- Certifications Section -->
        <section id="certifications" class="py-24 fade-in-section">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-3xl font-bold">IT Certifications & Skills</h2>
                 <div class="w-24 h-1 bg-accent mx-auto mt-4"></div>
                <p class="mt-4 text-lg text-gray-400">My journey of continuous learning and professional development.</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
                
                <!-- Certification Card 1 -->
                <div class="info-card bg-card-bg p-6 rounded-lg text-center">
                    <div class="text-accent mx-auto mb-4 h-12 w-12 flex items-center justify-center rounded-full bg-gray-800">
                         <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" /></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-2">CompTIA Security+</h3>
                    <p class="text-gray-400">Covers baseline skills necessary to perform core security functions and pursue an IT security career.</p>
                </div>

                <!-- Certification Card 2 -->
                <div class="info-card bg-card-bg p-6 rounded-lg text-center">
                     <div class="text-accent mx-auto mb-4 h-12 w-12 flex items-center justify-center rounded-full bg-gray-800">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" /></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-2">Certified Ethical Hacker (CEH)</h3>
                    <p class="text-gray-400"><span class="font-semibold text-accent">[In Progress]</span> Mastering ethical hacking methodologies to lawfully assess and secure computer systems.</p>
                </div>

                <!-- Certification Card 3 -->
                <div class="info-card bg-card-bg p-6 rounded-lg text-center">
                    <div class="text-accent mx-auto mb-4 h-12 w-12 flex items-center justify-center rounded-full bg-gray-800">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path d="M12 14l9-5-9-5-9 5 9 5z" /><path d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-5.998 12.078 12.078 0 01.665-6.479L12 14z" /><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-5.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222 4 2.222V20" /></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-white mb-2">Cisco CyberOps Associate</h3>
                    <p class="text-gray-400">Training for real-world tasks of security analysts in a Security Operations Center (SOC).</p>
                </div>
                
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-24 text-center fade-in-section">
            <h2 class="text-3xl font-bold text-white">Let's Connect</h2>
            <div class="w-24 h-1 bg-accent mx-auto mt-4"></div>
            <p class="text-gray-400 max-w-xl mx-auto my-8">
                I am actively seeking internship and full-time opportunities in the cyber security domain. If you have a role that aligns with my skills and passion, I would be thrilled to hear from you.
            </p>
            <a href="mailto:nitin.singhal.sec@example.com" class="btn btn-primary text-lg">
                singhal30n@gmail.com
            </a>
        </section>
<section id="contact" class="py-24 fade-in-section">
            <div class="max-w-4xl mx-auto px-6 bg-card-bg p-10 rounded-2xl border border-gray-800 info-card">
                <div class="text-center mb-10">
                    <h2 class="text-3xl font-bold text-white">Get In Touch</h2>
                    <div class="w-24 h-1 bg-accent mx-auto mt-4"></div>
                    <p class="text-gray-400 mt-6">
                        Hey! Drop your E-Mail ID Here , So I could be able to get connect with you.
                    </p>
                </div>

                <form action="https://formspree.io/f/YOUR_UNIQUE_ID" method="POST" class="max-w-md mx-auto">
                    <div class="flex flex-col gap-4">
                        <div class="relative">
                            <input 
                                type="email" 
                                name="email" 
                                placeholder="Enter your email address" 
                                required
                                class="w-full bg-gray-900 border border-gray-700 text-white py-3 px-4 rounded-lg focus:outline-none focus:border-accent transition-all"
                            >
                        </div>
                        <button type="submit" class="btn btn-primary w-full shadow-lg">
                            Establish Connection
                        </button>
                    </div>
                </form>
                
                <div class="mt-10 text-center">
                    <p class="text-sm text-gray-500 mb-2">Direct Channel:</p>
                    <a href="mailto:singhal30n@gmail.com" class="text-accent hover:underline font-medium">
                        singhal30n@gmail.com
                    </a>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="border-t border-gray-800">
        <div class="container mx-auto px-6 py-6 text-center text-gray-500">
            <p>&copy; 2025 Nitin Singhal. Building a Secure Digital Future.</p>
        </div>
    </footer>

    <!-- JavaScript for animations -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const sections = document.querySelectorAll('.fade-in-section');

            const observer = new IntersectionObserver(entries => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('is-visible');
                        observer.unobserve(entry.target);
                    }
                });
            }, {
                threshold: 0.15 
            });

            sections.forEach(section => {
                observer.observe(section);
            });
        });
    </script>
</body>
</html>

