<MADE BY Anmol singh>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 12 Physics and Maths Formulas</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    <style>
        :root {
            --background-color: #f0f4f8;
            --container-bg: #ffffff;
            --text-color: #333;
            --primary-color: #3f51b5; /* Indigo 600 */
            --secondary-color: #1a237e; /* Indigo 900 */
            --card-bg-color: #e8eaf6; /* Indigo 50 */
            --accent-color: #c5cae9; /* Indigo 200 */
            --toc-link-hover: #000000; /* Black for strong contrast */
        }

        body.dark-mode {
            --background-color: #121212;
            --container-bg: #1e1e1e;
            --text-color: #e0e0e0;
            --primary-color: #6a1b9a; /* Dark Purple */
            --secondary-color: #bb86fc; /* Light Purple (for contrast) */
            --card-bg-color: #2c2c2c;
            --accent-color: #424242;
            --toc-link-hover: #ffffff; /* White for strong contrast in dark mode */
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 20px;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
            transition: background-color 0.5s ease, color 0.5s ease;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            overflow-x: hidden; /* Prevent horizontal scroll from animations */
        }

        .container {
            max-width: 900px;
            margin: auto;
            background: var(--container-bg);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            transition: background 0.5s ease, box-shadow 0.5s ease;
        }

        h1 {
            text-align: center;
            color: var(--secondary-color);
            margin-bottom: 30px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.05);
            animation: textPopIn 1.2s cubic-bezier(0.68, -0.55, 0.27, 1.55) forwards;
            position: relative;
            transform: scale(0.8);
            opacity: 0;
        }

        h2 {
            color: var(--primary-color);
            border-bottom: 3px solid var(--primary-color);
            padding-bottom: 10px;
            margin-top: 40px;
            position: relative;
            animation: slideInLeft 0.8s ease-out;
            transition: border-color 0.5s ease;
        }

        h2::after {
            content: '';
            position: absolute;
            bottom: -3px;
            left: 0;
            width: 0;
            height: 3px;
            background-color: var(--secondary-color);
            transition: width 0.4s ease-out, background-color 0.5s ease;
        }

        .section:hover h2::after {
            width: 100%;
        }

        .formula {
            margin: 15px 0;
            padding: 20px;
            background: var(--card-bg-color);
            border-left: 5px solid var(--primary-color);
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease, background 0.5s ease, border-left-color 0.3s ease;
            cursor: pointer;
            opacity: 0;
            transform: translateY(30px);
            animation: slideUpFadeIn 0.8s forwards cubic-bezier(0.2, 0.8, 0.2, 1);
            will-change: transform, opacity;
        }

        .formula:hover {
            transform: translateY(-8px) scale(1.02);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            border-left-color: var(--secondary-color);
        }

        .formula h3 {
            color: var(--secondary-color);
            margin-top: 0;
            font-weight: 700;
        }

        .formula p {
            margin: 8px 0;
            line-height: 1.6;
            font-size: 1.05em;
        }

        .toc {
            background: var(--accent-color);
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 30px;
            box-shadow: inset 0 2px 5px rgba(0, 0, 0, 0.05);
            animation: fadeIn 1s ease-in-out;
            overflow: hidden;
        }

        .toc h3 {
            margin-top: 0;
            color: var(--secondary-color);
        }

        .toc ul {
            list-style: none;
            padding: 0;
        }

        .toc li {
            margin: 12px 0;
            opacity: 0;
            transform: translateX(-20px);
            animation: slideInToc 0.6s ease-out forwards;
        }

        .toc li:nth-child(1) { animation-delay: 0.2s; }
        .toc li:nth-child(2) { animation-delay: 0.3s; }
        .toc li:nth-child(3) { animation-delay: 0.4s; }
        .toc li:nth-child(4) { animation-delay: 0.5s; }
        .toc li:nth-child(5) { animation-delay: 0.6s; }
        .toc li:nth-child(6) { animation-delay: 0.7s; }
        .toc li:nth-child(7) { animation-delay: 0.8s; }
        .toc li:nth-child(8) { animation-delay: 0.9s; }
        .toc li:nth-child(9) { animation-delay: 1.0s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(1) { animation-delay: 1.3s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(2) { animation-delay: 1.4s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(3) { animation-delay: 1.5s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(4) { animation-delay: 1.6s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(5) { animation-delay: 1.7s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(6) { animation-delay: 1.8s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(7) { animation-delay: 1.9s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(8) { animation-delay: 2.0s; }
        .toc > ul > li:nth-child(2) ul li:nth-child(9) { animation-delay: 2.1s; }


        .toc a {
            text-decoration: none;
            color: var(--primary-color);
            font-weight: bold;
            transition: color 0.3s ease, transform 0.2s ease;
            display: inline-block;
        }

        .toc a:hover {
            color: var(--toc-link-hover);
            transform: translateX(5px);
        }

        #controls {
            position: fixed;
            top: 20px;
            right: 20px;
            z-index: 1000;
        }

        #darkModeToggle, #scrollToTopBtn {
            background-color: var(--primary-color);
            color: white;
            border: none;
            border-radius: 50%;
            width: 45px;
            height: 45px;
            font-size: 1.3em;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
            transition: background-color 0.3s, transform 0.3s, box-shadow 0.3s;
            margin-left: 10px;
            animation: popIn 0.5s ease-out;
        }

        #darkModeToggle:hover, #scrollToTopBtn:hover {
            background-color: var(--secondary-color);
            transform: scale(1.15);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
        }

        #scrollToTopBtn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.5s ease-in-out, visibility 0.5s ease-in-out;
            z-index: 999;
        }

        #scrollToTopBtn.show {
            opacity: 1;
            visibility: visible;
        }

        .watermark {
            position: fixed;
            bottom: 20px;
            left: 20px;
            opacity: 0.3;
            font-size: 20px;
            color: #4CAF50;
            z-index: 1000;
            pointer-events: none;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.2);
            transition: color 0.5s ease;
            font-weight: bold;
            letter-spacing: 1px;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUpFadeIn {
            from { opacity: 0; transform: translateY(50px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideInLeft {
            from { transform: translateX(-80px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }

        @keyframes slideInToc {
            from { opacity: 0; transform: translateX(-40px); }
            to { opacity: 1; transform: translateX(0); }
        }

        @keyframes textPopIn {
            0% { opacity: 0; transform: scale(0.5); }
            70% { opacity: 1; transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        @keyframes popIn {
            from { transform: scale(0); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        /* Staggered animation for physics formula blocks */
        #physics .formula:nth-child(1) { animation-delay: 0.1s; }
        #physics .formula:nth-child(2) { animation-delay: 0.2s; }
        #physics .formula:nth-child(3) { animation-delay: 0.3s; }
        #physics .formula:nth-child(4) { animation-delay: 0.4s; }
        #physics .formula:nth-child(5) { animation-delay: 0.5s; }
        #physics .formula:nth-child(6) { animation-delay: 0.6s; }
        #physics .formula:nth-child(7) { animation-delay: 0.7s; }
        #physics .formula:nth-child(8) { animation-delay: 0.8s; }
        #physics .formula:nth-child(9) { animation-delay: 0.9s; }
        #physics .formula:nth-child(10) { animation-delay: 1.0s; }

        /* Staggered animation for math formula blocks */
        #mathematics .formula:nth-child(1) { animation-delay: 0.1s; }
        #mathematics .formula:nth-child(2) { animation-delay: 0.2s; }
        #mathematics .formula:nth-child(3) { animation-delay: 0.3s; }
        #mathematics .formula:nth-child(4) { animation-delay: 0.4s; }
        #mathematics .formula:nth-child(5) { animation-delay: 0.5s; }
        #mathematics .formula:nth-child(6) { animation-delay: 0.6s; }
        #mathematics .formula:nth-child(7) { animation-delay: 0.7s; }
        #mathematics .formula:nth-child(8) { animation-delay: 0.8s; }
        #mathematics .formula:nth-child(9) { animation-delay: 0.9s; }
        #mathematics .formula:nth-child(10) { animation-delay: 1.0s; }
        #mathematics .formula:nth-child(11) { animation-delay: 1.1s; }
        #mathematics .formula:nth-child(12) { animation-delay: 1.2s; }
        #mathematics .formula:nth-child(13) { animation-delay: 1.3s; }
        #mathematics .formula:nth-child(14) { animation-delay: 1.4s; }
        #mathematics .formula:nth-child(15) { animation-delay: 1.5s; }
        #mathematics .formula:nth-child(16) { animation-delay: 1.6s; }
        #mathematics .formula:nth-child(17) { animation-delay: 1.7s; }
        #mathematics .formula:nth-child(18) { animation-delay: 1.8s; }
        #mathematics .formula:nth-child(19) { animation-delay: 1.9s; }
        #mathematics .formula:nth-child(20) { animation-delay: 2.0s; }
        #mathematics .formula:nth-child(21) { animation-delay: 2.1s; }
        #mathematics .formula:nth-child(22) { animation-delay: 2.2s; }
        #mathematics .formula:nth-child(23) { animation-delay: 2.3s; }
        #mathematics .formula:nth-child(24) { animation-delay: 2.4s; }
        #mathematics .formula:nth-child(25) { animation-delay: 2.5s; }
        #mathematics .formula:nth-child(26) { animation-delay: 2.6s; }
        #mathematics .formula:nth-child(27) { animation-delay: 2.7s; }
        #mathematics .formula:nth-child(28) { animation-delay: 2.8s; }
        #mathematics .formula:nth-child(29) { animation-delay: 2.9s; }
        #mathematics .formula:nth-child(30) { animation-delay: 3.0s; }


        @media (max-width: 768px) {
            body { padding: 10px; }
            .container { padding: 20px; }
            #darkModeToggle, #scrollToTopBtn {
                width: 35px;
                height: 35px;
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div id="controls">
        <button id="darkModeToggle">🌙</button>
    </div>
    <div class="watermark">ANMOL SINGH / rajput_anmolsingh3</div>
    <div class="container">
        <h1>Class 12 Physics and Mathematics Formulas 🎓</h1>

        <div class="toc">
            <h3>Table of Contents</h3>
            <ul>
                <li><a href="#physics">Physics</a></li>
                <ul>
                    <li><a href="#electrostatics">Electrostatics</a></li>
                    <li><a href="#current-electricity">Current Electricity</a></li>
                    <li><a href="#magnetism-and-matter">Magnetism and Matter</a></li>
                    <li><a href="#electromagnetic-induction">Electromagnetic Induction & AC</a></li>
                    <li><a href="#electromagnetic-waves">Electromagnetic Waves</a></li>
                    <li><a href="#ray-optics">Ray & Wave Optics</a></li>
                    <li><a href="#dual-nature">Dual Nature of Radiation & Matter</a></li>
                    <li><a href="#atoms-and-nuclei">Atoms and Nuclei</a></li>
                    <li><a href="#semiconductors">Semiconductor Electronics</a></li>
                    <li><a href="#communication-systems">Communication Systems</a></li>
                </ul>
                <li><a href="#mathematics">Mathematics</a></li>
                <ul>
                    <li><a href="#relations-and-functions">Relations and Functions</a></li>
                    <li><a href="#inverse-trigonometry">Inverse Trigonometry</a></li>
                    <li><a href="#matrices-and-determinants">Matrices and Determinants</a></li>
                    <li><a href="#continuity-and-differentiability">Continuity & Differentiability</a></li>
                    <li><a href="#applications-of-derivatives">Applications of Derivatives</a></li>
                    <li><a href="#integrals">Integrals</a></li>
                    <li><a href="#differential-equations">Differential Equations</a></li>
                    <li><a href="#vectors">Vectors</a></li>
                    <li><a href="#three-d-geometry">3D Geometry</a></li>
                    <li><a href="#linear-programming">Linear Programming</a></li>
                    <li><a href="#probability-class-12">Probability</a></li>
                </ul>
            </ul>
        </div>

        <div id="physics" class="section">
            <h2>Physics Formulas</h2>
            <div id="electrostatics" class="formula">
                <h3>Electrostatics</h3>
                <p><strong>Coulomb's Law:</strong> \( \vec{F} = \frac{1}{4\pi\epsilon_0} \frac{q_1q_2}{r^2} \hat{r} \)</p>
                <p><strong>Electric Field:</strong> \( \vec{E} = \frac{\vec{F}}{q_0} \). For a point charge: \( E = \frac{1}{4\pi\epsilon_0} \frac{q}{r^2} \)</p>
                <p><strong>Electric Potential:</strong> \( V = \frac{W}{q} \). For a point charge: \( V = \frac{1}{4\pi\epsilon_0} \frac{q}{r} \)</p>
                <p><strong>Relation between E and V:</strong> \( E = - \frac{dV}{dr} \)</p>
                <p><strong>Electric Flux:</strong> \( \Phi_E = \int \vec{E} \cdot d\vec{A} \)</p>
                <p><strong>Gauss's Law:</strong> \( \oint \vec{E} \cdot d\vec{A} = \frac{q_{in}}{\epsilon_0} \)</p>
                <p><strong>Capacitance:</strong> \( C = \frac{Q}{V} \). Parallel plate capacitor: \( C = \frac{\epsilon_0 A}{d} \)</p>
                <p><strong>Capacitors in Series:</strong> \( \frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + \dots \)</p>
                <p><strong>Capacitors in Parallel:</strong> \( C_{eq} = C_1 + C_2 + \dots \)</p>
                <p><strong>Energy Stored in Capacitor:</strong> \( U = \frac{1}{2}CV^2 = \frac{Q^2}{2C} = \frac{1}{2}QV \)</p>
            </div>
            <div id="current-electricity" class="formula">
                <h3>Current Electricity</h3>
                <p><strong>Ohm's Law:</strong> \( V = IR \)</p>
                <p><strong>Drift Velocity:</strong> \( v_d = \frac{eE\tau}{m} \)</p>
                <p><strong>Current-Drift Velocity Relation:</strong> \( I = neAv_d \)</p>
                <p><strong>Resistance:</strong> \( R = \frac{\rho L}{A} \), where \( \rho \) is resistivity</p>
                <p><strong>Conductivity:</strong> \( \sigma = \frac{1}{\rho} \)</p>
                <p><strong>Resistors in Series:</strong> \( R_{eq} = R_1 + R_2 + \dots \)</p>
                <p><strong>Resistors in Parallel:</strong> \( \frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots \)</p>
                <p><strong>Kirchhoff's First Law (Junction Rule):</strong> \( \sum I = 0 \)</p>
                <p><strong>Kirchhoff's Second Law (Loop Rule):</strong> \( \sum \Delta V = 0 \)</p>
                <p><strong>Internal Resistance of Cell:</strong> \( r = R\left(\frac{\epsilon}{V}-1\right) \)</p>
                <p><strong>Electric Power:</strong> \( P = VI = I^2R = \frac{V^2}{R} \)</p>
            </div>
            <div id="magnetism-and-matter" class="formula">
                <h3>Magnetism and Matter</h3>
                <p><strong>Biot-Savart Law:</strong> \( d\vec{B} = \frac{\mu_0}{4\pi} \frac{I d\vec{l} \times \hat{r}}{r^2} \)</p>
                <p><strong>Ampere's Circuital Law:</strong> \( \oint \vec{B} \cdot d\vec{l} = \mu_0 I_{enc} \)</p>
                <p><strong>Force on Moving Charge (Lorentz Force):</strong> \( \vec{F} = q(\vec{E} + \vec{v} \times \vec{B}) \)</p>
                <p><strong>Force on Current-Carrying Conductor:</strong> \( \vec{F} = I(\vec{L} \times \vec{B}) \)</p>
                <p><strong>Torque on Current Loop:</strong> \( \vec{\tau} = \vec{M} \times \vec{B} \), where \( \vec{M} = NI\vec{A} \)</p>
                <p><strong>Magnetic Field of Solenoid:</strong> \( B = \mu_0 n I \)</p>
                <p><strong>Magnetic Field of Toroid:</strong> \( B = \mu_0 n I \)</p>
                <p><strong>Magnetic Field on Axis of Circular Loop:</strong> \( B = \frac{\mu_0 I R^2}{2(R^2+x^2)^{3/2}} \)</p>
            </div>
            <div id="electromagnetic-induction" class="formula">
                <h3>Electromagnetic Induction & AC</h3>
                <p><strong>Magnetic Flux:</strong> \( \Phi_B = \vec{B} \cdot \vec{A} = BA \cos\theta \)</p>
                <p><strong>Faraday's Law of Induction:</strong> \( \epsilon = - \frac{d\Phi_B}{dt} \)</p>
                <p><strong>Motional EMF:</strong> \( \epsilon = Blv \)</p>
                <p><strong>Self-Inductance:</strong> \( \Phi = LI \implies \epsilon = -L \frac{dI}{dt} \)</p>
                <p><strong>Mutual Inductance:</strong> \( \Phi_2 = M I_1 \implies \epsilon_2 = -M \frac{dI_1}{dt} \)</p>
                <p><strong>Reactance:</strong> Inductive: \( X_L = \omega L \), Capacitive: \( X_C = \frac{1}{\omega C} \)</p>
                <p><strong>Impedance (LCR Circuit):</strong> \( Z = \sqrt{R^2 + (X_L - X_C)^2} \)</p>
                <p><strong>Resonance Frequency:</strong> \( \omega_0 = \frac{1}{\sqrt{LC}} \)</p>
                <p><strong>Transformer Ratio:</strong> \( \frac{V_s}{V_p} = \frac{N_s}{N_p} = \frac{I_p}{I_s} \)</p>
            </div>
            <div id="electromagnetic-waves" class="formula">
                <h3>Electromagnetic Waves</h3>
                <p><strong>Speed of EM Wave in Vacuum:</strong> \( c = \frac{1}{\sqrt{\mu_0\epsilon_0}} \)</p>
                <p><strong>Speed of EM Wave in Medium:</strong> \( v = \frac{1}{\sqrt{\mu\epsilon}} \)</p>
                <p><strong>Relation between E and B:</strong> \( E_0 = c B_0 \)</p>
                <p><strong>Energy Density of E field:</strong> \( u_E = \frac{1}{2}\epsilon_0 E^2 \)</p>
                <p><strong>Energy Density of B field:</strong> \( u_B = \frac{B^2}{2\mu_0} \)</p>
                <p><strong>Displacement Current:</strong> \( I_d = \epsilon_0 \frac{d\Phi_E}{dt} \)</p>
            </div>
            <div id="ray-optics" class="formula">
                <h3>Ray & Wave Optics</h3>
                <p><strong>Mirror Equation:</strong> \( \frac{1}{f} = \frac{1}{v} + \frac{1}{u} \)</p>
                <p><strong>Lens Equation:</strong> \( \frac{1}{f} = \frac{1}{v} - \frac{1}{u} \)</p>
                <p><strong>Refractive Index:</strong> \( n = \frac{c}{v} \)</p>
                <p><strong>Snell's Law:</strong> \( n_1 \sin \theta_1 = n_2 \sin \theta_2 \)</p>
                <p><strong>Power of a Lens:</strong> \( P = \frac{1}{f} \) (f in meters)</p>
                <p><strong>Total Internal Reflection (Critical Angle):</strong> \( \sin C = \frac{n_2}{n_1} \)</p>
                <p><strong>Young's Double Slit Exp (Fringe Width):</strong> \( \beta = \frac{\lambda D}{d} \)</p>
                <p><strong>Condition for Maxima:</strong> \( d\sin\theta = n\lambda \)</p>
                <p><strong>Condition for Minima:</strong> \( d\sin\theta = (n + \frac{1}{2})\lambda \)</p>
                <p><strong>Diffraction (Single Slit):</strong> \( \sin\theta = \frac{n\lambda}{a} \)</p>
                <p><strong>Malus's Law:</strong> \( I = I_0 \cos^2\theta \)</p>
            </div>
            <div id="dual-nature" class="formula">
                <h3>Dual Nature of Radiation & Matter</h3>
                <p><strong>Photon Energy:</strong> \( E = h\nu = \frac{hc}{\lambda} \)</p>
                <p><strong>Einstein's Photoelectric Equation:</strong> \( h\nu = \phi_0 + KE_{max} \)</p>
                <p><strong>Stopping Potential:</strong> \( eV_0 = KE_{max} \)</p>
                <p><strong>De Broglie Wavelength:</strong> \( \lambda = \frac{h}{p} = \frac{h}{mv} \)</p>
                <p><strong>De Broglie (for Electron):</strong> \( \lambda = \frac{1.22}{\sqrt{V}} \text{ nm} \)</p>
                <p><strong>Heisenberg's Uncertainty Principle:</strong> \( \Delta x \Delta p \geq \frac{\hbar}{2} \)</p>
            </div>
            <div id="atoms-and-nuclei" class="formula">
                <h3>Atoms and Nuclei</h3>
                <p><strong>Bohr's Radius:</strong> \( r_n = \frac{n^2 h^2 \epsilon_0}{\pi m Z e^2} \)</p>
                <p><strong>Bohr's Energy:</strong> \( E_n = -\frac{13.6 Z^2}{n^2} \text{ eV} \)</p>
                <p><strong>Rydberg Formula:</strong> \( \frac{1}{\lambda} = R_H \left(\frac{1}{n_1^2} - \frac{1}{n_2^2}\right) \)</p>
                <p><strong>Mass Defect:</strong> \( \Delta m = (Z m_p + N m_n) - M_{nucleus} \)</p>
                <p><strong>Binding Energy:</strong> \( BE = \Delta m c^2 \)</p>
                <p><strong>Radioactive Decay Law:</strong> \( N(t) = N_0 e^{-\lambda t} \)</p>
                <p><strong>Half-Life:</strong> \( T_{1/2} = \frac{\ln 2}{\lambda} = \frac{0.693}{\lambda} \)</p>
                <p><strong>Average Life:</strong> \( \tau = \frac{1}{\lambda} \)</p>
            </div>
            <div id="semiconductors" class="formula">
                <h3>Semiconductor Electronics</h3>
                <p><strong>Current in Diode:</strong> \( I = I_0(e^{eV/kT} - 1) \)</p>
                <p><strong>Current Gain (Common Emitter):</strong> \( \beta = \frac{\Delta I_C}{\Delta I_B} \)</p>
                <p><strong>Current Gain (Common Base):</strong> \( \alpha = \frac{\Delta I_C}{\Delta I_E} \)</p>
                <p><strong>Relation between Alpha & Beta:</strong> \( \beta = \frac{\alpha}{1-\alpha} \)</p>
                <p><strong>Voltage Gain:</strong> \( A_v = \beta \frac{R_L}{R_{in}} \)</p>
            </div>
            <div id="communication-systems" class="formula">
                <h3>Communication Systems</h3>
                <p><strong>Modulation Index (AM):</strong> \( \mu = \frac{A_m}{A_c} \)</p>
                <p><strong>Bandwidth (AM):</strong> \( 2f_m \)</p>
                <p><strong>Power of AM Wave:</strong> \( P_{total} = P_c \left(1 + \frac{\mu^2}{2}\right) \)</p>
                <p><strong>Line of Sight (LOS) Distance:</strong> \( d = \sqrt{2Rh_T} + \sqrt{2Rh_R} \)</p>
            </div>
        </div>

        <div id="mathematics" class="section">
            <h2>Mathematics Formulas</h2>
            <div id="relations-and-functions" class="formula">
                <h3>Relations and Functions</h3>
                <p><strong>Composite Function:</strong> \( (f \circ g)(x) = f(g(x)) \)</p>
                <p><strong>Inverse Function:</strong> \( f^{-1}(y) = x \iff f(x) = y \)</p>
                <p><strong>One-One Function (Injective):</strong> If \( f(x_1) = f(x_2) \implies x_1 = x_2 \)</p>
                <p><strong>Onto Function (Surjective):</strong> For every \( y \) in the codomain, there exists \( x \) in the domain such that \( f(x) = y \)</p>
            </div>
            <div id="inverse-trigonometry" class="formula">
                <h3>Inverse Trigonometry</h3>
                <p>\( \sin^{-1}x + \cos^{-1}x = \frac{\pi}{2} \)</p>
                <p>\( \tan^{-1}x + \cot^{-1}x = \frac{\pi}{2} \)</p>
                <p>\( \sec^{-1}x + \csc^{-1}x = \frac{\pi}{2} \)</p>
                <p><strong>Sum of Tangents:</strong> \( \tan^{-1}x + \tan^{-1}y = \tan^{-1} \left( \frac{x+y}{1-xy} \right) \)</p>
                <p><strong>Double Angle Identities:</strong> \( 2\tan^{-1}x = \tan^{-1}\left(\frac{2x}{1-x^2}\right) = \sin^{-1}\left(\frac{2x}{1+x^2}\right) = \cos^{-1}\left(\frac{1-x^2}{1+x^2}\right) \)</p>
            </div>
            <div id="matrices-and-determinants" class="formula">
                <h3>Matrices and Determinants</h3>
                <p><strong>Determinant of 2x2:</strong> \( |A| = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc \)</p>
                <p><strong>Properties of Determinants:</strong> \( |AB| = |A||B| \), \( |A^T| = |A| \), \( |kA| = k^n|A| \)</p>
                <p><strong>Adjoint of Matrix:</strong> \( \text{adj}(A) = (\text{cofactor matrix of A})^T \)</p>
                <p><strong>Inverse of Matrix:</strong> \( A^{-1} = \frac{1}{|A|} \text{adj}(A) \)</p>
                <p><strong>System of Linear Eq:</strong> \( AX = B \implies X = A^{-1}B \)</p>
                <p><strong>Singular Matrix:</strong> \( |A| = 0 \)</p>
                <p><strong>Non-Singular Matrix:</strong> \( |A| \neq 0 \)</p>
            </div>
            <div id="continuity-and-differentiability" class="formula">
                <h3>Continuity & Differentiability</h3>
                <p><strong>Continuity at x=a:</strong> \( \lim_{x \to a^-} f(x) = \lim_{x \to a^+} f(x) = f(a) \)</p>
                <p><strong>Differentiability:</strong> A function is differentiable at x=a if \( \lim_{h \to 0} \frac{f(a+h) - f(a)}{h} \) exists.</p>
                <p><strong>Derivative of Common Functions:</strong></p>
                <ul>
                    <li>\( \frac{d}{dx}(x^n) = nx^{n-1} \)</li>
                    <li>\( \frac{d}{dx}(e^x) = e^x \)</li>
                    <li>\( \frac{d}{dx}(\ln x) = \frac{1}{x} \)</li>
                    <li>\( \frac{d}{dx}(\sin x) = \cos x \)</li>
                    <li>\( \frac{d}{dx}(\cos x) = -\sin x \)</li>
                    <li>\( \frac{d}{dx}(\tan x) = \sec^2 x \)</li>
                    <li>\( \frac{d}{dx}(\sin^{-1}x) = \frac{1}{\sqrt{1-x^2}} \)</li>
                    <li>\( \frac{d}{dx}(\tan^{-1}x) = \frac{1}{1+x^2} \)</li>
                    <li>\( \frac{d}{dx}(\sec^{-1}x) = \frac{1}{|x|\sqrt{x^2-1}} \)</li>
                </ul>
                <p><strong>Product Rule:</strong> \( \frac{d}{dx}(uv) = u\frac{dv}{dx} + v\frac{du}{dx} \)</p>
                <p><strong>Quotient Rule:</strong> \( \frac{d}{dx} \left(\frac{u}{v}\right) = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^2} \)</p>
                <p><strong>Chain Rule:</strong> \( \frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} \)</p>
            </div>
            <div id="applications-of-derivatives" class="formula">
                <h3>Applications of Derivatives</h3>
                <p><strong>Slope of Tangent:</strong> \( m = \frac{dy}{dx} \)</p>
                <p><strong>Equation of Tangent:</strong> \( y - y_1 = m(x - x_1) \)</p>
                <p><strong>Equation of Normal:</strong> \( y - y_1 = -\frac{1}{m}(x - x_1) \)</p>
                <p><strong>Increasing Function:</strong> \( f'(x) > 0 \)</p>
                <p><strong>Decreasing Function:</strong> \( f'(x) < 0 \)</p>
                <p><strong>Local Maxima/Minima:</strong> First derivative test: find critical points where \( f'(x) = 0 \). Check for sign change.</p>
                <p><strong>Maxima/Minima (Second Derivative Test):</strong> If \( f'(c)=0 \), then \( f''(c)>0 \) implies local minimum, and \( f''(c)<0 \) implies local maximum.</p>
            </div>
            <div id="integrals" class="formula">
                <h3>Integrals</h3>
                <p><strong>Fundamental Theorem of Calculus:</strong> \( \int_a^b f(x) dx = F(b) - F(a) \)</p>
                <p><strong>Integration by Parts:</strong> \( \int u dv = uv - \int v du \) (ILATE rule for choosing u)</p>
                <p><strong>Area under curve:</strong> \( A = \int_a^b y dx \)</p>
                <p><strong>Standard Indefinite Integrals:</strong></p>
                <ul>
                    <li>\( \int x^n dx = \frac{x^{n+1}}{n+1} + C, (n \neq -1) \)</li>
                    <li>\( \int \frac{1}{x} dx = \ln|x| + C \)</li>
                    <li>\( \int e^x dx = e^x + C \)</li>
                    <li>\( \int a^x dx = \frac{a^x}{\ln a} + C \)</li>
                    <li>\( \int \sin x dx = -\cos x + C \)</li>
                    <li>\( \int \cos x dx = \sin x + C \)</li>
                    <li>\( \int \sec^2 x dx = \tan x + C \)</li>
                    <li>\( \int \csc^2 x dx = -\cot x + C \)</li>
                    <li>\( \int \sec x \tan x dx = \sec x + C \)</li>
                </ul>
                <p><strong>Six Standard Integrals of Special Functions:</strong></p>
                <ul>
                    <li>\( \int \frac{dx}{x^2-a^2} = \frac{1}{2a} \log\left|\frac{x-a}{x+a}\right| + C \)</li>
                    <li>\( \int \frac{dx}{a^2-x^2} = \frac{1}{2a} \log\left|\frac{a+x}{a-x}\right| + C \)</li>
                    <li>\( \int \frac{dx}{x^2+a^2} = \frac{1}{a} \tan^{-1}\left(\frac{x}{a}\right) + C \)</li>
                    <li>\( \int \frac{dx}{\sqrt{x^2-a^2}} = \log|x + \sqrt{x^2-a^2}| + C \)</li>
                    <li>\( \int \frac{dx}{\sqrt{a^2-x^2}} = \sin^{-1}\left(\frac{x}{a}\right) + C \)</li>
                    <li>\( \int \frac{dx}{\sqrt{x^2+a^2}} = \log|x + \sqrt{x^2+a^2}| + C \)</li>
                </ul>
                <p><strong>Six Standard Integrals with \( \sqrt{} \):</strong></p>
                <ul>
                    <li>\( \int \sqrt{x^2-a^2} dx = \frac{x}{2}\sqrt{x^2-a^2} - \frac{a^2}{2}\log|x+\sqrt{x^2-a^2}| + C \)</li>
                    <li>\( \int \sqrt{a^2-x^2} dx = \frac{x}{2}\sqrt{a^2-x^2} + \frac{a^2}{2}\sin^{-1}\left(\frac{x}{a}\right) + C \)</li>
                    <li>\( \int \sqrt{x^2+a^2} dx = \frac{x}{2}\sqrt{x^2+a^2} + \frac{a^2}{2}\log|x+\sqrt{x^2+a^2}| + C \)</li>
                </ul>
            </div>
            <div id="differential-equations" class="formula">
                <h3>Differential Equations</h3>
                <p><strong>Linear D.E.:</strong> \( \frac{dy}{dx} + Py = Q \)</p>
                <p><strong>Integrating Factor:</strong> \( IF = e^{\int P dx} \)</p>
                <p><strong>General Solution:</strong> \( y \cdot (IF) = \int Q \cdot (IF) dx + C \)</p>
                <p><strong>Homogeneous D.E.:</strong> \( \frac{dy}{dx} = f\left(\frac{y}{x}\right) \), substitute \( y=vx \)</p>
            </div>
            <div id="vectors" class="formula">
                <h3>Vectors</h3>
                <p><strong>Dot Product:</strong> \( \vec{a} \cdot \vec{b} = |\vec{a}||\vec{b}| \cos\theta \)</p>
                <p><strong>Cross Product:</strong> \( \vec{a} \times \vec{b} = |\vec{a}||\vec{b}| \sin\theta \hat{n} \)</p>
                <p><strong>Projection of vector a on vector b:</strong> \( \frac{\vec{a} \cdot \vec{b}}{|\vec{b}|} \)</p>
                <p><strong>Area of Parallelogram:</strong> \( |\vec{a} \times \vec{b}| \)</p>
                <p><strong>Area of Triangle:</strong> \( \frac{1}{2} |\vec{a} \times \vec{b}| \)</p>
                <p><strong>Scalar Triple Product (Volume of Parallelopiped):</strong> \( [\vec{a} \cdot (\vec{b} \times \vec{c})] \)</p>
            </div>
            <div id="three-d-geometry" class="formula">
                <h3>3D Geometry</h3>
                <p><strong>Distance between two points:</strong> \( \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2 + (z_2-z_1)^2} \)</p>
                <p><strong>Direction Cosines:</strong> \( l = \cos\alpha, m=\cos\beta, n=\cos\gamma \), where \( l^2+m^2+n^2=1 \)</p>
                <p><strong>Equation of a line:</strong> \( \vec{r} = \vec{a} + \lambda \vec{b} \) or \( \frac{x-x_1}{a} = \frac{y-y_1}{b} = \frac{z-z_1}{c} \)</p>
                <p><strong>Shortest distance between skew lines:</strong> \( d = \left| \frac{(\vec{a_2} - \vec{a_1}) \cdot (\vec{b_1} \times \vec{b_2})}{|\vec{b_1} \times \vec{b_2}|} \right| \)</p>
                <p><strong>Equation of a Plane:</strong> \( \vec{r} \cdot \vec{n} = d \) (Vector Form) or \( Ax+By+Cz=D \) (Cartesian Form)</p>
                <p><strong>Distance of a point from a plane:</strong> \( \left| \frac{Ax_1+By_1+Cz_1-D}{\sqrt{A^2+B^2+C^2}} \right| \)</p>
            </div>
            <div id="linear-programming" class="formula">
                <h3>Linear Programming</h3>
                <p><strong>Objective Function:</strong> \( Z = ax + by \)</p>
                <p><strong>Feasible Region:</strong> The set of all points satisfying all constraints.</p>
                <p><strong>Corner Point Method:</strong> The optimal solution (max/min) occurs at a corner point of the feasible region.</p>
            </div>
            <div id="probability-class-12" class="formula">
                <h3>Probability</h3>
                <p><strong>Conditional Probability:</strong> \( P(A|B) = \frac{P(A \cap B)}{P(B)} \)</p>
                <p><strong>Independent Events:</strong> \( P(A \cap B) = P(A)P(B) \)</p>
                <p><strong>Total Probability:</strong> \( P(A) = \sum_{i=1}^{n} P(E_i)P(A|E_i) \)</p>
                <p><strong>Bayes' Theorem:</strong> \( P(E_i|A) = \frac{P(E_i)P(A|E_i)}{\sum_{j=1}^{n} P(E_j)P(A|E_j)} \)</p>
                <p><strong>Mean of a random variable:</strong> \( E(X) = \sum X_i P(X_i) \)</p>
                <p><strong>Variance:</strong> \( \text{Var}(X) = E(X^2) - [E(X)]^2 \)</p>
                <p><strong>Binomial Distribution:</strong> \( P(X=k) = \binom{n}{k} p^k (1-p)^{n-k} \)</p>
            </div>
        </div>
    </div>
    <button id="scrollToTopBtn">⬆️</button>

    <script>
        // Dark Mode Toggle
        const darkModeToggle = document.getElementById('darkModeToggle');
        darkModeToggle.addEventListener('click', () => {
            document.body.classList.toggle('dark-mode');
            const isDarkMode = document.body.classList.contains('dark-mode');
            localStorage.setItem('darkMode', isDarkMode);
            darkModeToggle.textContent = isDarkMode ? '☀️' : '🌙';
        });

        if (localStorage.getItem('darkMode') === 'true') {
            document.body.classList.add('dark-mode');
            darkModeToggle.textContent = '☀️';
        }

        // Scroll-to-top button
        const scrollToTopBtn = document.getElementById('scrollToTopBtn');

        window.addEventListener('scroll', () => {
            if (window.scrollY > 300) {
                scrollToTopBtn.classList.add('show');
            } else {
                scrollToTopBtn.classList.remove('show');
            }
        });

        scrollToTopBtn.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Intersection Observer for animations
        const formulaObserver = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.animationPlayState = 'running';
                    observer.unobserve(entry.target);
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.formula').forEach(formula => {
            formula.style.animationPlayState = 'paused';
            formulaObserver.observe(formula);
        });

        const h2Observer = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.animationPlayState = 'running';
                    observer.unobserve(entry.target);
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('h2').forEach(h2 => {
            h2.style.animationPlayState = 'paused';
            h2Observer.observe(h2);
        });

        const tocLiObserver = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.animationPlayState = 'running';
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.toc li').forEach(li => {
            li.style.animationPlayState = 'paused';
            tocLiObserver.observe(li);
        });

    </script>
</body>
</html>
