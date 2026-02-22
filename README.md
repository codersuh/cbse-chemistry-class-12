<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suhu Study Care - Chemistry Class 12 CBSE Complete</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #6366f1;
            --secondary: #ec4899;
            --success: #10b981;
            --warning: #f59e0b;
            --danger: #ef4444;
            --dark: #1f2937;
            --light: #f9fafb;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: var(--dark);
            line-height: 1.6;
        }

        .navbar {
            background: rgba(255, 255, 255, 0.95);
            padding: 15px 30px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .navbar-brand {
            font-size: 1.8em;
            font-weight: bold;
            background: linear-gradient(135deg, #6366f1, #ec4899);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .nav-buttons {
            display: flex;
            gap: 15px;
        }

        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background: var(--primary);
            color: white;
        }

        .btn-primary:hover {
            background: #4f46e5;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(99, 102, 241, 0.4);
        }

        .btn-secondary {
            background: var(--secondary);
            color: white;
        }

        .btn-secondary:hover {
            background: #db2777;
            transform: translateY(-2px);
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 30px 20px;
        }

        .welcome-banner {
            background: rgba(255, 255, 255, 0.95);
            padding: 40px;
            border-radius: 15px;
            text-align: center;
            margin-bottom: 40px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
        }

        .welcome-banner h1 {
            font-size: 2.5em;
            margin-bottom: 15px;
            color: var(--dark);
        }

        .welcome-banner p {
            font-size: 1.1em;
            color: #6b7280;
            margin-bottom: 20px;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }

        .feature-card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: all 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
        }

        .feature-icon {
            font-size: 3em;
            margin-bottom: 15px;
        }

        .feature-card h3 {
            color: var(--primary);
            margin-bottom: 10px;
            font-size: 1.3em;
        }

        .feature-card p {
            color: #6b7280;
            margin-bottom: 15px;
        }

        .chapters-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .chapter-card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            cursor: pointer;
            transition: all 0.3s ease;
            border-left: 5px solid var(--primary);
        }

        .chapter-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
        }

        .chapter-card h3 {
            color: var(--dark);
            margin-bottom: 10px;
        }

        .chapter-card p {
            color: #6b7280;
            font-size: 0.95em;
            margin-bottom: 15px;
        }

        .badge {
            display: inline-block;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.8em;
            font-weight: 600;
        }

        .badge-content {
            background: #e0e7ff;
            color: #3730a3;
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: 2000;
            overflow-y: auto;
            padding: 20px 0;
        }

        .modal.active {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .modal-content {
            background: white;
            padding: 40px;
            border-radius: 15px;
            max-width: 1000px;
            width: 90%;
            max-height: 85vh;
            overflow-y: auto;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
        }

        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            border-bottom: 2px solid var(--light);
            padding-bottom: 20px;
        }

        .modal-header h2 {
            color: var(--dark);
            font-size: 1.8em;
        }

        .close-btn {
            font-size: 2em;
            background: none;
            border: none;
            color: #6b7280;
            cursor: pointer;
            padding: 0;
            width: 40px;
            height: 40px;
        }

        .close-btn:hover {
            color: var(--dark);
        }

        .tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
            border-bottom: 2px solid #e5e7eb;
            flex-wrap: wrap;
        }

        .tab-btn {
            padding: 10px 20px;
            background: transparent;
            border: none;
            color: #6b7280;
            font-weight: 600;
            cursor: pointer;
            border-bottom: 3px solid transparent;
            margin-bottom: -2px;
        }

        .tab-btn.active {
            color: var(--primary);
            border-bottom-color: var(--primary);
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
            animation: fadeIn 0.3s ease;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .content-section {
            background: #f9fafb;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .content-section h3 {
            color: var(--primary);
            margin-bottom: 15px;
            font-size: 1.3em;
            border-bottom: 2px solid var(--primary);
            padding-bottom: 10px;
        }

        .content-section h4 {
            color: var(--secondary);
            margin-top: 15px;
            margin-bottom: 10px;
            font-size: 1.1em;
        }

        .content-section p {
            color: #374151;
            margin-bottom: 12px;
            line-height: 1.8;
            text-align: justify;
        }

        .content-section ul, .content-section ol {
            margin-left: 25px;
            margin-bottom: 15px;
        }

        .content-section li {
            margin-bottom: 8px;
            color: #374151;
            line-height: 1.6;
        }

        .formula-box {
            background: #e0e7ff;
            border-left: 4px solid var(--primary);
            padding: 15px;
            margin: 15px 0;
            border-radius: 6px;
            font-family: 'Courier New', monospace;
            color: #3730a3;
        }

        .example-box {
            background: #fef3c7;
            border-left: 4px solid var(--warning);
            padding: 15px;
            margin: 15px 0;
            border-radius: 6px;
            color: #92400e;
        }

        .important-box {
            background: #fecaca;
            border-left: 4px solid var(--danger);
            padding: 15px;
            margin: 15px 0;
            border-radius: 6px;
            color: #7f1d1d;
        }

        .note-box {
            background: #d1fae5;
            border-left: 4px solid var(--success);
            padding: 15px;
            margin: 15px 0;
            border-radius: 6px;
            color: #065f46;
        }

        .diagram {
            background: #f3f4f6;
            border: 2px dashed var(--primary);
            padding: 20px;
            margin: 15px 0;
            border-radius: 6px;
            font-family: monospace;
            overflow-x: auto;
            text-align: center;
        }

        .table-responsive {
            overflow-x: auto;
            margin: 15px 0;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        table th {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 12px;
            text-align: left;
            font-weight: 600;
        }

        table td {
            padding: 10px 12px;
            border-bottom: 1px solid #e5e7eb;
        }

        table tr:hover {
            background: #f9fafb;
        }

        .question {
            background: #f3f4f6;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 15px;
            border-left: 4px solid var(--primary);
        }

        .question h4 {
            color: var(--dark);
            margin-bottom: 15px;
            font-size: 1.05em;
        }

        .options {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .option-btn {
            padding: 12px 15px;
            background: white;
            border: 2px solid #e5e7eb;
            border-radius: 6px;
            text-align: left;
            cursor: pointer;
            transition: all 0.3s ease;
            color: var(--dark);
        }

        .option-btn:hover {
            border-color: var(--primary);
            background: #f0f4ff;
        }

        .option-btn.correct {
            background: var(--success);
            color: white;
            border-color: var(--success);
        }

        .option-btn.incorrect {
            background: var(--danger);
            color: white;
            border-color: var(--danger);
        }

        .answer-explanation {
            background: #f0fdf4;
            border-left: 4px solid var(--success);
            padding: 15px;
            border-radius: 6px;
            margin-top: 15px;
            font-size: 0.95em;
            color: #15803d;
            display: none;
        }

        .answer-explanation.show {
            display: block;
        }

        .footer {
            background: rgba(255, 255, 255, 0.95);
            text-align: center;
            padding: 30px;
            margin-top: 50px;
            border-top: 2px solid #e5e7eb;
            color: #6b7280;
        }

        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                gap: 15px;
            }

            .nav-buttons {
                width: 100%;
                justify-content: space-between;
            }

            .modal-content {
                padding: 20px;
                width: 95%;
            }

            .chapters-grid {
                grid-template-columns: 1fr;
            }
        }

        .print-btn {
            background: #10b981;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-bottom: 20px;
        }

        .print-btn:hover {
            background: #059669;
        }

        @media print {
            .navbar, .close-btn, .print-btn {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="navbar-brand">📚 Suhu Study Care</div>
        <div class="nav-buttons">
            <button class="btn-primary" onclick="showHome()">Home</button>
            <button class="btn-secondary" onclick="showAllChapters()">All Chapters</button>
        </div>
    </div>

    <div class="container">
        <div id="home-section">
            <div class="welcome-banner">
                <h1>🎓 Welcome to Suhu Study Care</h1>
                <p>Complete Chemistry Class 12 CBSE Study Material</p>
                <p style="font-size: 1em; color: #9ca3af;">Detailed Content • MCQs • Revision Notes • Self Assessment</p>
            </div>

            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">📖</div>
                    <h3>Complete Content</h3>
                    <p>NCERT-style detailed explanations for all 13 chapters</p>
                    <button class="btn-primary" onclick="showAllChapters()">Start Learning</button>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">❓</div>
                    <h3>MCQ Practice</h3>
                    <p>100+ practice questions with detailed explanations</p>
                    <button class="btn-primary" onclick="showAllChapters()">Practice Now</button>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">⭐</div>
                    <h3>Quick Notes</h3>
                    <p>Quick reference notes for exam preparation</p>
                    <button class="btn-primary" onclick="showAllChapters()">View Notes</button>
                </div>
            </div>

            <h2 style="color: white; margin: 40px 0 20px; text-align: center; font-size: 2em;">All 13 Chapters</h2>
            <div class="chapters-grid" id="chapters-container"></div>
        </div>

        <div id="chapters-section" style="display: none;">
            <h2 style="color: white; margin-bottom: 30px;">Chemistry Class 12 - All Chapters</h2>
            <div class="chapters-grid" id="chapters-list"></div>
        </div>
    </div>

    <div class="modal" id="modal">
        <div class="modal-content">
            <div class="modal-header">
                <h2 id="modal-title">Chapter</h2>
                <button class="close-btn" onclick="closeModal()">&times;</button>
            </div>
            <div id="modal-body"></div>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 2026 Suhu Study Care | Chemistry Class 12 CBSE | Powered by Complete Learning</p>
        <p>Study Smart, Score Better! 🌟</p>
    </div>

    <script>
        const chapters = [
            { id: 1, name: "Solid State", icon: "💎" },
            { id: 2, name: "Solutions", icon: "🧪" },
            { id: 3, name: "Electrochemistry", icon: "⚡" },
            { id: 4, name: "Chemical Kinetics", icon: "⏱️" },
            { id: 5, name: "Surface Chemistry", icon: "🌊" },
            { id: 6, name: "General Principles of Extraction", icon: "🔧" },
            { id: 7, name: "P-Block Elements", icon: "🧬" },
            { id: 8, name: "D & F Block Elements", icon: "🎨" },
            { id: 9, name: "Coordination Compounds", icon: "🔗" },
            { id: 10, name: "Organic Chemistry - I", icon: "🍃" },
            { id: 11, name: "Organic Chemistry - II", icon: "🌿" },
            { id: 12, name: "Polymers & Biomolecules", icon: "🧬" },
            { id: 13, name: "Chemistry in Everyday Life", icon: "🏥" }
        ];

        const detailedContent = {
            1: {
                title: "Chapter 1: Solid State",
                content: `
                    <div class="content-section">
                        <h3>1. Introduction to Solid State</h3>
                        <p>Solids are states of matter characterized by definite shape, volume, and rigidity. They possess strong intermolecular forces that keep atoms/molecules in fixed positions. The study of solids involves understanding their structure at atomic, molecular, and macroscopic levels.</p>
                        
                        <h4>Characteristics:</h4>
                        <ul>
                            <li>Definite shape and volume</li>
                            <li>Incompressible due to close-packed atoms</li>
                            <li>Cannot flow under normal conditions</li>
                            <li>High density</li>
                            <li>Rigid structure maintained by strong intermolecular forces</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>2. Classification of Solids</h3>
                        <h4>Crystalline Solids:</h4>
                        <p>Have regular 3D arrangement with repeating pattern. Show sharp melting points and anisotropy (properties vary with direction).</p>
                        <ul>
                            <li><strong>Ionic:</strong> NaCl, CaCl₂ - hard, brittle, high melting points</li>
                            <li><strong>Covalent/Network:</strong> Diamond, SiO₂ - extremely hard, very high melting points</li>
                            <li><strong>Molecular:</strong> Ice, CO₂ - soft, low melting points</li>
                            <li><strong>Metallic:</strong> Fe, Cu - malleable, ductile, conduct electricity</li>
                        </ul>

                        <h4>Amorphous Solids:</h4>
                        <p>Lack long-range order. Random atomic arrangement. No sharp melting point. Isotropic (same properties in all directions). Examples: Glass, rubber, plastic.</p>
                    </div>

                    <div class="content-section">
                        <h3>3. Crystal Lattice and Unit Cell</h3>
                        <p><strong>Crystal Lattice:</strong> 3D arrangement of atoms/ions at fixed positions.</p>
                        <p><strong>Unit Cell:</strong> Smallest repeating unit containing all characteristics of the crystal.</p>

                        <h4>Seven Crystal Systems:</h4>
                        <div class="table-responsive">
                            <table>
                                <tr>
                                    <th>System</th>
                                    <th>a, b, c</th>
                                    <th>α, β, γ</th>
                                </tr>
                                <tr>
                                    <td>Cubic</td>
                                    <td>a = b = c</td>
                                    <td>90° each</td>
                                </tr>
                                <tr>
                                    <td>Tetragonal</td>
                                    <td>a = b ≠ c</td>
                                    <td>90° each</td>
                                </tr>
                                <tr>
                                    <td>Orthorhombic</td>
                                    <td>a ≠ b ≠ c</td>
                                    <td>90° each</td>
                                </tr>
                                <tr>
                                    <td>Monoclinic</td>
                                    <td>a ≠ b ≠ c</td>
                                    <td>α = γ = 90°, β ≠ 90°</td>
                                </tr>
                                <tr>
                                    <td>Triclinic</td>
                                    <td>a ≠ b ≠ c</td>
                                    <td>All different</td>
                                </tr>
                                <tr>
                                    <td>Hexagonal</td>
                                    <td>a = b ≠ c</td>
                                    <td>α = β = 90°, γ = 120°</td>
                                </tr>
                                <tr>
                                    <td>Rhombohedral</td>
                                    <td>a = b = c</td>
                                    <td>All equal (≠ 90°)</td>
                                </tr>
                            </table>
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>4. Types of Unit Cells</h3>
                        
                        <h4>Simple Cubic (SC):</h4>
                        <ul>
                            <li>Atoms only at corners: 8 × (1/8) = 1 atom/cell</li>
                            <li>Coordination number = 6</li>
                            <li>Packing efficiency = 52%</li>
                            <li>Examples: Po</li>
                        </ul>

                        <h4>Body-Centered Cubic (BCC):</h4>
                        <ul>
                            <li>Corners + body center: 8 × (1/8) + 1 = 2 atoms/cell</li>
                            <li>Coordination number = 8</li>
                            <li>Packing efficiency = 68%</li>
                            <li>Examples: Fe, Cr, W</li>
                        </ul>

                        <h4>Face-Centered Cubic (FCC) / Cubic Close Packing (CCP):</h4>
                        <ul>
                            <li>Corners + faces: 8 × (1/8) + 6 × (1/2) = 4 atoms/cell</li>
                            <li>Coordination number = 12</li>
                            <li>Packing efficiency = 74%</li>
                            <li>Examples: Cu, Ag, Au, Al, Pb</li>
                        </ul>

                        <h4>Hexagonal Close Packing (HCP):</h4>
                        <ul>
                            <li>ABABAB... arrangement</li>
                            <li>Coordination number = 12</li>
                            <li>Packing efficiency = 74%</li>
                            <li>Examples: Mg, Zn, Cd, Ti</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Imperfections in Crystals</h3>
                        
                        <h4>Point Defects (0-D):</h4>
                        <ul>
                            <li><strong>Schottky Defect:</strong> Atom missing from lattice position. Leaves vacancy. Affects density (decreases).</li>
                            <li><strong>Frenkel Defect:</strong> Atom displaced to interstitial position. No change in density.</li>
                            <li><strong>Color Centers:</strong> F-centers (electron in anion vacancy) give color. Example: Yellow NaCl</li>
                        </ul>

                        <h4>Line Defects (1-D):</h4>
                        <p>Dislocation: Linear defect affecting mechanical properties (plasticity, ductility).</p>

                        <h4>Plane Defects (2-D):</h4>
                        <p>Stacking faults and grain boundaries in polycrystalline materials.</p>
                    </div>

                    <div class="content-section">
                        <h3>6. Density Calculations</h3>
                        <div class="formula-box">
                            Density = (Z × M) / (a³ × Nₐ)
                            <br>Z = atoms/formula units per cell
                            <br>M = Molar mass (g/mol)
                            <br>a = Edge length (cm)
                            <br>Nₐ = Avogadro's number
                        </div>

                        <div class="example-box">
                            <strong>Example:</strong> FCC Cu: a = 3.61 × 10⁻⁸ cm, M = 63.5
                            <br>Z = 4, Density = (4 × 63.5) / ((3.61 × 10⁻⁸)³ × 6.022 × 10²³)
                            <br>= <strong>8.94 g/cm³</strong>
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>7. X-ray Crystallography & Bragg's Law</h3>
                        <div class="formula-box">
                            nλ = 2d sin θ
                            <br>n = order of diffraction
                            <br>λ = X-ray wavelength
                            <br>d = d-spacing between planes
                            <br>θ = angle of incidence
                        </div>
                        <p>Used to determine crystal structure and d-spacings.</p>
                    </div>
                `
            },
            2: {
                title: "Chapter 2: Solutions",
                content: `
                    <div class="content-section">
                        <h3>1. Introduction to Solutions</h3>
                        <p>A solution is a homogeneous mixture of two or more substances at molecular level. Solvent: major component. Solute: minor component. Solutions can be gaseous, liquid, or solid.</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Ways to Express Concentration</h3>
                        
                        <h4>A. Molarity (M):</h4>
                        <div class="formula-box">
                            M = moles of solute / L of solution
                            <br>Temperature dependent (volume changes)
                        </div>

                        <h4>B. Molality (m):</h4>
                        <div class="formula-box">
                            m = moles of solute / kg of solvent
                            <br>Temperature independent
                        </div>

                        <h4>C. Normality (N):</h4>
                        <div class="formula-box">
                            N = equivalents of solute / L of solution
                        </div>

                        <h4>D. Mole Fraction (x):</h4>
                        <div class="formula-box">
                            x_A = n_A / (n_A + n_B + ...)
                            <br>Sum of all mole fractions = 1
                        </div>

                        <h4>E. Mass % (w/w) and Volume % (v/v)</h4>
                    </div>

                    <div class="content-section">
                        <h3>3. Raoult's Law</h3>
                        <div class="formula-box">
                            P_A = x_A × P°_A
                            <br>P_total = x_A P°_A + x_B P°_B
                            <br>Relative Lowering = (P° - P)/P° = x_solute
                        </div>
                        <p>For ideal solutions. Vapor pressure lowers with involatile solute.</p>
                    </div>

                    <div class="content-section">
                        <h3>4. Colligative Properties</h3>
                        <p>Depend only on number of solute particles, not their identity.</p>
                        
                        <h4>A. Boiling Point Elevation:</h4>
                        <div class="formula-box">
                            ΔT_b = K_b × m × i
                            <br>K_b (water) = 0.52 K·kg/mol
                        </div>

                        <h4>B. Freezing Point Depression:</h4>
                        <div class="formula-box">
                            ΔT_f = K_f × m × i
                            <br>K_f (water) = 1.86 K·kg/mol
                        </div>

                        <h4>C. Osmotic Pressure:</h4>
                        <div class="formula-box">
                            π = iCRT = iMRT
                            <br>R = 0.0821 L·atm/(mol·K)
                        </div>

                        <h4>D. Van't Hoff Factor (i):</h4>
                        <ul>
                            <li>Non-electrolyte: i = 1</li>
                            <li>Strong electrolyte: i ≈ 2 (NaCl), 3 (CaCl₂)</li>
                        </ul>

                        <div class="note-box">
                            <strong>Solutions Types:</strong> Hypertonic (water flows out), Hypotonic (water flows in), Isotonic (no net flow)
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>5. Ideal vs Non-Ideal Solutions</h3>
                        
                        <h4>Ideal Solutions:</h4>
                        <ul>
                            <li>Follow Raoult's law perfectly</li>
                            <li>ΔH_mix = 0, ΔV_mix = 0</li>
                            <li>Example: Benzene + Toluene</li>
                        </ul>

                        <h4>Non-Ideal Solutions:</h4>
                        <ul>
                            <li><strong>Positive Deviation:</strong> ΔH_mix > 0, P > expected. Example: Water + Ethanol</li>
                            <li><strong>Negative Deviation:</strong> ΔH_mix < 0, P < expected. Example: Acetic acid + Benzene</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>6. Henry's Law</h3>
                        <div class="formula-box">
                            P = K_H × x_gas
                            <br>C = K_H × P
                        </div>
                        <p>Solubility of gases in liquids depends on partial pressure and temperature. Applications: Carbonated drinks, oxygen in water, scuba diving (nitrogen narcosis).</p>
                    </div>
                `
            },
            3: {
                title: "Chapter 3: Electrochemistry",
                content: `
                    <div class="content-section">
                        <h3>1. Introduction</h3>
                        <p>Study of relationship between electrical energy and chemical reactions. Involves electron transfer in spontaneous and non-spontaneous reactions.</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Galvanic Cells (Voltaic Cells)</h3>
                        <p>Convert chemical energy to electrical energy through spontaneous redox reactions.</p>
                        
                        <h4>Components:</h4>
                        <ul>
                            <li><strong>Anode:</strong> Negative terminal, oxidation occurs</li>
                            <li><strong>Cathode:</strong> Positive terminal, reduction occurs</li>
                            <li><strong>Electrolyte:</strong> Completes circuit</li>
                            <li><strong>Salt Bridge:</strong> Maintains electrical neutrality</li>
                        </ul>

                        <h4>Daniell Cell:</h4>
                        <div class="formula-box">
                            Anode: Zn → Zn²⁺ + 2e⁻
                            <br>Cathode: Cu²⁺ + 2e⁻ → Cu
                            <br>Overall: Zn + Cu²⁺ → Zn²⁺ + Cu
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>3. Standard Electrode Potentials</h3>
                        <p><strong>Standard Hydrogen Electrode (SHE):</strong> Reference electrode with E° = 0.00 V</p>
                        
                        <h4>Interpretation:</h4>
                        <ul>
                            <li>More positive E°: Stronger oxidizing agent, more easily reduced</li>
                            <li>More negative E°: Stronger reducing agent, more easily oxidized</li>
                        </ul>

                        <h4>Common E° Values:</h4>
                        <div class="table-responsive">
                            <table>
                                <tr><th>Half-Reaction</th><th>E° (V)</th></tr>
                                <tr><td>F₂ + 2e⁻ → 2F⁻</td><td>+2.87</td></tr>
                                <tr><td>Cl₂ + 2e⁻ → 2Cl⁻</td><td>+1.36</td></tr>
                                <tr><td>Cu²⁺ + 2e⁻ → Cu</td><td>+0.34</td></tr>
                                <tr><td>2H⁺ + 2e⁻ → H₂</td><td>0.00</td></tr>
                                <tr><td>Zn²⁺ + 2e⁻ → Zn</td><td>-0.76</td></tr>
                                <tr><td>Na⁺ + e⁻ → Na</td><td>-2.71</td></tr>
                            </table>
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>4. Cell Potential & Spontaneity</h3>
                        <div class="formula-box">
                            E°cell = E°cathode - E°anode
                            <br>E°cell > 0: Spontaneous
                            <br>E°cell < 0: Non-spontaneous
                            <br>E°cell = 0: Equilibrium
                        </div>

                        <div class="example-box">
                            <strong>Daniell Cell:</strong> E° = 0.34 - (-0.76) = <strong>+1.10 V</strong>
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>5. Gibbs Free Energy</h3>
                        <div class="formula-box">
                            ΔG° = -nFE°cell
                            <br>F = 96,500 C/mol
                            <br>E° = (0.059/n) log K at 25°C
                        </div>
                        <p>Connects thermodynamics to electrochemistry. Positive E° → Negative ΔG° (spontaneous).</p>
                    </div>

                    <div class="content-section">
                        <h3>6. Nernst Equation</h3>
                        <div class="formula-box">
                            E = E° - (0.059/n) log Q at 25°C
                            <br>Q = reaction quotient with actual concentrations
                        </div>
                        <p>Calculates cell potential under non-standard conditions.</p>
                    </div>

                    <div class="content-section">
                        <h3>7. Electrolytic Cells</h3>
                        <p>Use external electrical energy to drive non-spontaneous reactions.</p>
                        
                        <h4>Key Differences from Galvanic:</h4>
                        <div class="table-responsive">
                            <table>
                                <tr><th>Property</th><th>Galvanic</th><th>Electrolytic</th></tr>
                                <tr><td>Reaction</td><td>Spontaneous</td><td>Non-spontaneous</td></tr>
                                <tr><td>E°cell</td><td>Positive</td><td>Negative</td></tr>
                                <tr><td>Anode</td><td>Negative</td><td>Positive</td></tr>
                                <tr><td>Cathode</td><td>Positive</td><td>Negative</td></tr>
                            </table>
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>8. Faraday's Laws of Electrolysis</h3>
                        <div class="formula-box">
                            Moles = (I × t) / (n × F)
                            <br>First Law: Amount ∝ charge
                            <br>Second Law: Amounts ∝ equivalent weights
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>9. Applications</h3>
                        <ul>
                            <li><strong>Electroplating:</strong> Metal coating (object = cathode)</li>
                            <li><strong>Chlor-alkali:</strong> 2NaCl + 2H₂O → Cl₂ + H₂ + 2NaOH</li>
                            <li><strong>Corrosion Prevention:</strong> Cathodic protection, sacrificial anodes</li>
                            <li><strong>Batteries:</strong> Lead-acid (12V), Dry cells (1.5V)</li>
                        </ul>
                    </div>
                `
            },
            4: {
                title: "Chapter 4: Chemical Kinetics",
                content: `
                    <div class="content-section">
                        <h3>1. Introduction</h3>
                        <p>Study of reaction rates and mechanisms. Tells us how fast a reaction occurs and through what steps.</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Rate of Reaction</h3>
                        <div class="formula-box">
                            Average Rate = -Δ[A]/Δt or +Δ[P]/Δt
                            <br>Instantaneous Rate = slope at specific time
                        </div>
                        <p>For aA + bB → cC + dD: -1/a d[A]/dt = -1/b d[B]/dt = 1/c d[C]/dt = 1/d d[D]/dt</p>
                    </div>

                    <div class="content-section">
                        <h3>3. Rate Law & Order</h3>
                        <div class="formula-box">
                            Rate = k[A]^m[B]^n
                            <br>Order = m + n (determined experimentally)
                            <br>k = rate constant
                        </div>
                        <ul>
                            <li>Zero-order: Rate independent of concentration</li>
                            <li>First-order: Rate ∝ [reactant]</li>
                            <li>Second-order: Rate ∝ [reactant]² or [A][B]</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>4. First-Order Reactions</h3>
                        <div class="formula-box">
                            Rate = k[A]
                            <br>ln[A]_t = ln[A]₀ - kt
                            <br>t₁/₂ = 0.693/k (independent of concentration)
                            <br>Unit of k: s⁻¹
                        </div>
                        <p>Radioactive decay, decomposition reactions follow first-order kinetics.</p>
                    </div>

                    <div class="content-section">
                        <h3>5. Second-Order Reactions</h3>
                        <div class="formula-box">
                            Rate = k[A]²
                            <br>1/[A]_t = 1/[A]₀ + kt
                            <br>t₁/₂ = 1/(k[A]₀) (depends on initial concentration)
                            <br>Unit of k: L/(mol·s)
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>6. Arrhenius Equation</h3>
                        <div class="formula-box">
                            k = Ae^(-E_a/RT)
                            <br>ln(k₂/k₁) = (E_a/R)(T₂ - T₁)/(T₁T₂)
                            <br>A = pre-exponential factor (frequency factor)
                            <br>E_a = activation energy
                        </div>
                        <p>Relationship between rate constant, temperature, and activation energy.</p>
                    </div>

                    <div class="content-section">
                        <h3>7. Catalysts & Reaction Mechanisms</h3>
                        <p><strong>Catalyst:</strong> Substance that increases reaction rate by lowering activation energy. Not consumed in reaction.</p>
                        
                        <h4>Reaction Mechanism:</h4>
                        <ul>
                            <li>Step-by-step process of elementary reactions</li>
                            <li>Rate-determining step (slowest) controls overall rate</li>
                            <li>Intermediates: formed in one step, consumed in another</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>8. Collision Theory</h3>
                        <ul>
                            <li>Reactions occur when molecules collide with sufficient energy and correct orientation</li>
                            <li>E_a = minimum energy required</li>
                            <li>Fraction with E ≥ E_a increases exponentially with temperature</li>
                        </ul>
                    </div>
                `
            },
            5: {
                title: "Chapter 5: Surface Chemistry",
                content: `
                    <div class="content-section">
                        <h3>1. Adsorption</h3>
                        <p>Accumulation of substance on surface due to imbalanced forces at surface.</p>
                        
                        <h4>Physical Adsorption:</h4>
                        <ul>
                            <li>Van der Waals forces</li>
                            <li>Weak, reversible</li>
                            <li>ΔH = -5 to -20 kJ/mol</li>
                            <li>Low temperature favors</li>
                        </ul>

                        <h4>Chemical Adsorption:</h4>
                        <ul>
                            <li>Covalent bonding</li>
                            <li>Strong, irreversible</li>
                            <li>ΔH = -50 to -400 kJ/mol</li>
                            <li>High temperature favors</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>2. Freundlich & Langmuir Isotherms</h3>
                        
                        <h4>Freundlich:</h4>
                        <div class="formula-box">
                            x/m = kC^(1/n)
                            <br>log(x/m) = log k + (1/n)log C
                        </div>

                        <h4>Langmuir:</h4>
                        <div class="formula-box">
                            x/m = abc/(1 + bc)
                            <br>Assumes monolayer adsorption
                        </div>

                        <h4>BET Equation:</h4>
                        <p>For multilayer adsorption. Used to determine surface area.</p>
                    </div>

                    <div class="content-section">
                        <h3>3. Colloids</h3>
                        <p>Dispersions with particle size 1-1000 nm (between solutions and suspensions).</p>
                        
                        <h4>Types:</h4>
                        <ul>
                            <li><strong>Lyophilic:</strong> Solvent-loving, stable</li>
                            <li><strong>Lyophobic:</strong> Solvent-hating, require stabilizer</li>
                        </ul>

                        <h4>Properties:</h4>
                        <ul>
                            <li><strong>Tyndall Effect:</strong> Scattering of light</li>
                            <li><strong>Brownian Motion:</strong> Random zigzag movement</li>
                            <li><strong>Electrophoresis:</strong> Movement in electric field</li>
                            <li><strong>Zeta Potential:</strong> Electrical potential at particle surface</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>4. Emulsions</h3>
                        <p>Colloidal dispersion of two immiscible liquids.</p>
                        <ul>
                            <li><strong>O/W:</strong> Oil droplets in water (milk, mayonnaise)</li>
                            <li><strong>W/O:</strong> Water droplets in oil (butter)</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Catalysis</h3>
                        <ul>
                            <li><strong>Homogeneous:</strong> Catalyst in same phase as reactants</li>
                            <li><strong>Heterogeneous:</strong> Catalyst in different phase (surface catalysis)</li>
                            <li><strong>Enzyme:</strong> Biological catalyst, highly specific</li>
                        </ul>
                    </div>
                `
            },
            6: {
                title: "Chapter 6: General Principles of Extraction",
                content: `
                    <div class="content-section">
                        <h3>1. Occurrence & Extraction Steps</h3>
                        <p>Metals exist as ores (mineral forms). Extraction involves: concentration, conversion to oxide, reduction, and refining.</p>
                        
                        <h4>Concentration Methods:</h4>
                        <ul>
                            <li><strong>Gravity Separation:</strong> Based on density differences</li>
                            <li><strong>Magnetic Separation:</strong> For magnetic ores (Fe₃O₄)</li>
                            <li><strong>Froth Flotation:</strong> Hydrophobic minerals float</li>
                            <li><strong>Leaching:</strong> Dissolve ore in solvent</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>2. Roasting & Calcination</h3>
                        <ul>
                            <li><strong>Roasting:</strong> Heating in air, removes volatile impurities</li>
                            <li><strong>Calcination:</strong> Heating without air, decomposition</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>3. Extraction Methods</h3>
                        
                        <h4>Blast Furnace (Iron):</h4>
                        <ul>
                            <li>Fe₂O₃ reduced by CO</li>
                            <li>Heat from coke combustion</li>
                            <li>Limestone removes impurities (slag)</li>
                        </ul>

                        <h4>Thermite Process:</h4>
                        <div class="formula-box">
                            Fe₂O₃ + 2Al → 2Fe + Al₂O₃
                            <br>Highly exothermic, for Cr, Mn, Ti extraction
                        </div>

                        <h4>Cyanide Process (Au, Ag):</h4>
                        <ul>
                            <li>2Au + 4CN⁻ + O₂ + 2H₂O → 2[Au(CN)₂]⁻ + 4OH⁻</li>
                            <li>Reduction by Zn: 2[Au(CN)₂]⁻ + Zn → 2Au + [Zn(CN)₄]²⁻</li>
                        </ul>

                        <h4>Hall-Héroult Process (Aluminum):</h4>
                        <ul>
                            <li>Al₂O₃ dissolved in molten cryolite (Na₃AlF₆)</li>
                            <li>Cathode: Al³⁺ + 3e⁻ → Al</li>
                            <li>Anode: 2O²⁻ → O₂ + 4e⁻</li>
                            <li>Temperature ~1000°C, requires huge electricity</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>4. Refining Methods</h3>
                        
                        <h4>Electrorefining:</h4>
                        <ul>
                            <li>Impure metal as anode</li>
                            <li>Pure metal as cathode</li>
                            <li>Selective reduction at cathode</li>
                            <li>Anode mud contains precious metals</li>
                        </ul>

                        <h4>Zone Refining:</h4>
                        <p>Movement of molten zone for ultra-pure semiconductors (Si, Ge).</p>
                    </div>

                    <div class="content-section">
                        <h3>5. Important Alloys</h3>
                        <ul>
                            <li><strong>Steel:</strong> Fe + C (0.1-2%), Cr, Ni (stainless)</li>
                            <li><strong>Brass:</strong> Cu + Zn (20-40%)</li>
                            <li><strong>Bronze:</strong> Cu + Sn (8-14%)</li>
                            <li><strong>Duralumin:</strong> Al + Cu + Mg + Mn</li>
                        </ul>
                    </div>
                `
            },
            7: {
                title: "Chapter 7: P-Block Elements",
                content: `
                    <div class="content-section">
                        <h3>1. Overview</h3>
                        <p>Groups 13-18 (IIIA-VIIIA). ns²np¹ to ns²np⁶ configuration. Properties vary from non-metallic to metallic.</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Group 13 (Boron Group)</h3>
                        <p>ns²np¹, valence = 3</p>
                        <ul>
                            <li><strong>Boron:</strong> Non-metallic, amphoteric. Forms boric acid H₃BO₃</li>
                            <li><strong>Aluminum:</strong> Amphoteric oxide. AlCl₃ is covalent (electron deficient)</li>
                            <li><strong>Ga, In, Tl:</strong> Increasing metallic character</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>3. Group 14 (Carbon Group)</h3>
                        <p>ns²np², valence = 2, 4</p>
                        <ul>
                            <li><strong>Carbon:</strong> Allotropes: diamond (3D network), graphite (layers), C₆₀</li>
                            <li><strong>Silicon:</strong> Metalloid, SiO₂ (covalent network)</li>
                            <li><strong>Ge, Sn, Pb:</strong> Increasing metallic character</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>4. Group 15 (Nitrogen Group)</h3>
                        <p>ns²np³, valence = 3, 5</p>
                        <ul>
                            <li><strong>Nitrogen:</strong> N₂ (very stable, triple bond). Forms NO₂, N₂O, HNO₃</li>
                            <li><strong>Phosphorus:</strong> White (P₄ tetrahedral), Red (polymeric), Black (graphite-like)</li>
                            <li><strong>Arsenic, Antimony:</strong> Metalloid character</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Group 16 (Oxygen Group)</h3>
                        <p>ns²np⁴, valence = 2, 4, 6</p>
                        <ul>
                            <li><strong>Oxygen:</strong> O₂ (diatomic), O₃ (ozone), most electronegative except F</li>
                            <li><strong>Sulfur:</strong> S₈ (crown-shaped ring), forms H₂SO₄</li>
                            <li><strong>Se, Te:</strong> Less electronegative, metalloid-like</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>6. Group 17 (Halogens)</h3>
                        <p>ns²np⁵, valence = 1, 3, 5, 7</p>
                        <ul>
                            <li><strong>Reactivity:</strong> F₂ > Cl₂ > Br₂ > I₂</li>
                            <li><strong>Oxidizing Power:</strong> F₂ > Cl₂ > Br₂ > I₂</li>
                            <li><strong>Acid Strength:</strong> HF < HCl < HBr < HI</li>
                            <li><strong>Interhalogen Compounds:</strong> ClF₅, BrF₃, I₂Cl₆</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>7. Group 18 (Noble Gases)</h3>
                        <p>ns²np⁶ (except He), completely filled valence shell</p>
                        <ul>
                            <li>Very inert, unreactive</li>
                            <li>Xe forms XeF₂, XeF₄, XeF₆, XeO₃, XeO₄ (exceptions)</li>
                            <li>Used in lamps, anesthesia, inert atmosphere</li>
                        </ul>
                    </div>
                `
            },
            8: {
                title: "Chapter 8: D & F Block Elements",
                content: `
                    <div class="content-section">
                        <h3>1. Transition Metals (D-Block)</h3>
                        <p>(n-1)d¹⁻¹⁰ ns¹⁻². Sc to Zn in period 4.</p>
                        
                        <h4>Characteristics:</h4>
                        <ul>
                            <li>Variable oxidation states (multiple oxidation states stable)</li>
                            <li>Colored compounds (d-d electronic transitions)</li>
                            <li>Paramagnetic (unpaired electrons in d-orbitals)</li>
                            <li>Form stable complex ions</li>
                            <li>Good catalysts (e.g., Fe, Ni, Pt)</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>2. Oxidation States</h3>
                        <ul>
                            <li>Sc: +3</li>
                            <li>Ti: +2, +3, +4</li>
                            <li>V: +2, +3, +4, +5</li>
                            <li>Cr: +2, +3, +6</li>
                            <li>Mn: +2, +3, +4, +6, +7</li>
                            <li>Fe: +2, +3</li>
                            <li>Cu: +1, +2</li>
                            <li>Zn: +2</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>3. Important Compounds</h3>
                        <ul>
                            <li><strong>KMnO₄:</strong> Purple, strong oxidizer. MnO₄⁻ → Mn²⁺ in acidic solution</li>
                            <li><strong>K₂Cr₂O₇:</strong> Orange, strong oxidizer. Cr₂O₇²⁻ → Cr³⁺ in acidic solution</li>
                            <li><strong>FeSO₄:</strong> Pale green (Fe²⁺)</li>
                            <li><strong>FeCl₃:</strong> Brown (Fe³⁺)</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>4. Lanthanides (4f Block)</h3>
                        <p>[Xe]4f¹⁻¹⁴5d⁰⁻¹6s²</p>
                        <ul>
                            <li>Similar chemical properties (lanthanide contraction)</li>
                            <li>Mostly +3 oxidation state</li>
                            <li>Form colored ions (f-f transitions)</li>
                            <li>Used in magnets, phosphors, catalysts</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Actinides (5f Block)</h3>
                        <p>[Rn]5f¹⁻¹⁴6d⁰⁻¹7s²</p>
                        <ul>
                            <li>Mostly radioactive</li>
                            <li>Variable oxidation states, especially U (+3 to +6)</li>
                            <li>Form complex compounds</li>
                            <li>Examples: U (uranium), Pu (plutonium), Th (thorium)</li>
                        </ul>
                    </div>
                `
            },
            9: {
                title: "Chapter 9: Coordination Compounds",
                content: `
                    <div class="content-section">
                        <h3>1. Basic Concepts</h3>
                        <p><strong>Complex:</strong> Central metal atom + ligands</p>
                        <p><strong>Ligand:</strong> Molecule/ion donating electron pair (acts as Lewis base)</p>
                        <p><strong>Coordination Number:</strong> Number of ligands bonded</p>
                        <p><strong>Coordination Sphere:</strong> Metal + ligands together</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Types of Ligands</h3>
                        
                        <h4>Based on Donor Atoms:</h4>
                        <ul>
                            <li><strong>Monodentate:</strong> One binding site (NH₃, Cl⁻, H₂O, CO)</li>
                            <li><strong>Bidentate:</strong> Two binding sites (ethylene diamine, oxalate)</li>
                            <li><strong>Polydentate:</strong> Multiple binding sites (EDTA)</li>
                        </ul>

                        <h4>Based on Charge:</h4>
                        <ul>
                            <li><strong>Neutral:</strong> NH₃, H₂O, CO</li>
                            <li><strong>Anionic:</strong> Cl⁻, CN⁻, OH⁻</li>
                            <li><strong>Cationic:</strong> Rare (ammonium ligands)</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>3. Nomenclature</h3>
                        <ul>
                            <li>Name ligands first (alphabetical), then metal</li>
                            <li>Anionic complex: metal name + -ate (ferrocyanide)</li>
                            <li>Number ligands: di-, tri-, tetra-, etc.</li>
                            <li>Examples: [Co(NH₃)₆]³⁺ (hexaamminecobalt(III))</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>4. Isomerism</h3>
                        
                        <h4>Structural Isomerism:</h4>
                        <ul>
                            <li>Linkage isomerism (SCN⁻ vs NCS⁻)</li>
                            <li>Coordination isomerism</li>
                            <li>Ionization isomerism</li>
                        </ul>

                        <h4>Stereoisomerism:</h4>
                        <ul>
                            <li><strong>Geometric:</strong> cis-trans (square planar, octahedral)</li>
                            <li><strong>Optical:</strong> d,l isomers (non-superimposable)</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Crystal Field Theory</h3>
                        <p>d-orbitals split in ligand field due to electrostatic repulsion.</p>
                        
                        <h4>Octahedral Splitting:</h4>
                        <ul>
                            <li>dz² and dx²-y² higher energy (e_g)</li>
                            <li>dxy, dxz, dyz lower energy (t₂g)</li>
                            <li>Splitting energy = Δ₀ (crystal field splitting parameter)</li>
                        </ul>

                        <h4>High-Spin vs Low-Spin:</h4>
                        <ul>
                            <li><strong>Weak Field (High-Spin):</strong> Δ < Pairing energy, electrons spread</li>
                            <li><strong>Strong Field (Low-Spin):</strong> Δ > Pairing energy, electrons pair</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>6. Color & Magnetism</h3>
                        <p><strong>Color:</strong> d-d electronic transitions absorb visible light. Complementary color observed.</p>
                        <p><strong>Magnetism:</strong> Unpaired electrons make complex paramagnetic. All paired = diamagnetic.</p>
                    </div>

                    <div class="content-section">
                        <h3>7. Stability of Complexes</h3>
                        <p><strong>Stability Constant:</strong> K_stab = [complex]/([metal][ligand]^n)</p>
                        <p>Larger K_stab = more stable complex. EDTA forms very stable complexes.</p>
                    </div>
                `
            },
            10: {
                title: "Chapter 10: Organic Chemistry - I (Haloalkanes & Haloarenes)",
                content: `
                    <div class="content-section">
                        <h3>1. Haloalkanes</h3>
                        <p>Alkanes with halogen substitution. Classified by halogen substitution position.</p>
                        
                        <h4>Classification:</h4>
                        <ul>
                            <li><strong>Primary (1°):</strong> Halogen on CH₂</li>
                            <li><strong>Secondary (2°):</strong> Halogen on CH</li>
                            <li><strong>Tertiary (3°):</strong> Halogen on C with three C atoms</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>2. Nucleophilic Substitution Reactions</h3>
                        
                        <h4>SN1 Mechanism (Unimolecular):</h4>
                        <ul>
                            <li>Two-step process</li>
                            <li>Rate = k[RX] (unimolecular)</li>
                            <li>Rate: 3° > 2° > 1° (carbocation stability)</li>
                            <li>Racemization occurs (loss of stereochemistry)</li>
                            <li>Polar aprotic solvents (DMSO, DMF) accelerate</li>
                        </ul>

                        <h4>SN2 Mechanism (Bimolecular):</h4>
                        <ul>
                            <li>One-step concerted process</li>
                            <li>Rate = k[RX][Nu] (bimolecular)</li>
                            <li>Rate: 1° > 2° > 3° (steric hindrance)</li>
                            <li>Inversion of configuration (Walden inversion)</li>
                            <li>Polar aprotic solvents accelerate</li>
                        </ul>

                        <h4>Comparing SN1 vs SN2:</h4>
                        <div class="table-responsive">
                            <table>
                                <tr><th>Factor</th><th>SN1</th><th>SN2</th></tr>
                                <tr><td>Mechanism</td><td>Two-step</td><td>One-step</td></tr>
                                <tr><td>Rate Order</td><td>3° > 2° > 1°</td><td>1° > 2° > 3°</td></tr>
                                <tr><td>Stereochemistry</td><td>Racemization</td><td>Inversion</td></tr>
                                <tr><td>Solvent</td><td>Polar</td><td>Polar aprotic</td></tr>
                            </table>
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>3. Elimination Reactions</h3>
                        
                        <h4>E1 Mechanism:</h4>
                        <ul>
                            <li>Two-step via carbocation</li>
                            <li>Rate = k[RX]</li>
                            <li>Prefers 3° alkyl halides</li>
                            <li>Competes with SN1</li>
                        </ul>

                        <h4>E2 Mechanism:</h4>
                        <ul>
                            <li>One-step concerted</li>
                            <li>Rate = k[RX][base]</li>
                            <li>Anti-periplanar arrangement required</li>
                            <li>Strong base required</li>
                        </ul>

                        <h4>Zaitsev's Rule:</h4>
                        <p>Major product has more substituted double bond (more stable alkene).</p>
                    </div>

                    <div class="content-section">
                        <h3>4. Haloarenes</h3>
                        <p>Halogen directly bonded to benzene ring. Much less reactive than haloalkanes (resonance stabilization).</p>
                        
                        <h4>Nucleophilic Aromatic Substitution:</h4>
                        <ul>
                            <li>Requires electron-withdrawing groups</li>
                            <li>Mechanism: Addition-elimination (benzyne intermediate)</li>
                        </ul>

                        <h4>Sandmeyer Reaction:</h4>
                        <div class="formula-box">
                            PhN₂⁺ + CuX → PhX + N₂
                            <br>Used to prepare haloarenes from amines
                        </div>
                    </div>

                    <div class="content-section">
                        <h3>5. Important Reactions</h3>
                        
                        <h4>Grignard Reaction:</h4>
                        <div class="formula-box">
                            RX + Mg → RMgX (Grignard reagent)
                            <br>RMgX + C=O → R-CH(OMgX) → R-CH-OH (alcohol)
                        </div>

                        <h4>Wurtz Reaction:</h4>
                        <div class="formula-box">
                            2RX + 2Na → R-R (alkane coupling)
                        </div>

                        <h4>Elimination by Alcoholate:</h4>
                        <div class="formula-box">
                            RX + RONa → Alkene (Hofmann elimination for ammonium)
                        </div>
                    </div>
                `
            },
            11: {
                title: "Chapter 11: Organic Chemistry - II (O & N Compounds)",
                content: `
                    <div class="content-section">
                        <h3>1. Alcohols</h3>
                        <p>Compounds with -OH group attached to sp³ carbon.</p>
                        
                        <h4>Classification:</h4>
                        <ul>
                            <li><strong>Primary (1°):</strong> CH₂OH</li>
                            <li><strong>Secondary (2°):</strong> CHOH</li>
                            <li><strong>Tertiary (3°):</strong> COH</li>
                        </ul>

                        <h4>Preparation:</h4>
                        <ul>
                            <li>Nucleophilic substitution (SN2 on primary)</li>
                            <li>Reduction of carbonyl compounds</li>
                            <li>Grignard reaction with aldehydes/ketones</li>
                        </ul>

                        <h4>Oxidation:</h4>
                        <ul>
                            <li>1° alcohol → aldehyde → carboxylic acid</li>
                            <li>2° alcohol → ketone</li>
                            <li>3° alcohol → no oxidation</li>
                        </ul>

                        <h4>Acidity:</h4>
                        <p>1° > 2° > 3° alcohols (alkyl groups destabilize alkoxide)</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Phenols</h3>
                        <p>-OH attached directly to benzene ring. Much more acidic than alcohols (pKa ≈ 10).</p>
                        
                        <h4>Acidity:</h4>
                        <p>Phenoxide ion stabilized by resonance. Can donate H⁺ to bases.</p>

                        <h4>Reactions:</h4>
                        <ul>
                            <li>Electrophilic aromatic substitution (OH is ortho/para directing)</li>
                            <li>Acylation to form esters</li>
                            <li>Oxidation to quinones</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>3. Ethers</h3>
                        <p>R-O-R' compounds. Unreactive, used as solvents.</p>
                        
                        <h4>Preparation:</h4>
                        <div class="formula-box">
                            Williamson Synthesis: R⁻O⁻Na + R'X → R-O-R' + NaX
                            <br>SN2 mechanism
                        </div>

                        <h4>Cleavage:</h4>
                        <p>HX (conc.) cleaves C-O bond forming alcohol and alkyl halide.</p>
                    </div>

                    <div class="content-section">
                        <h3>4. Aldehydes & Ketones</h3>
                        <p>Carbonyl (C=O) compounds. Aldehydes more reactive (less hindered).</p>
                        
                        <h4>Preparation:</h4>
                        <ul>
                            <li>Oxidation of primary alcohols → aldehydes</li>
                            <li>Oxidation of secondary alcohols → ketones</li>
                            <li>Friedel-Crafts acylation</li>
                        </ul>

                        <h4>Nucleophilic Addition:</h4>
                        <div class="formula-box">
                            C=O + Nu⁻ → C-O⁻-Nu → product
                            <br>With H₂O: hydrate formation
                            <br>With alcohols: acetal/ketal formation
                            <br>With HCN: cyanohydrin formation
                        </div>

                        <h4>Important Reactions:</h4>
                        <ul>
                            <li><strong>Aldol Condensation:</strong> Two aldehyde/ketone molecules condense with base</li>
                            <li><strong>Cannizzaro Reaction:</strong> Formaldehyde disproportionation</li>
                            <li><strong>Grignard Reaction:</strong> RMgX converts C=O to alcohol</li>
                            <li><strong>Wittig Reaction:</strong> C=O → C=C alkene</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Carboxylic Acids</h3>
                        <p>-COOH compounds. Acidic (pKa 4-5) due to resonance-stabilized carboxylate anion.</p>
                        
                        <h4>Preparation:</h4>
                        <ul>
                            <li>Oxidation of aldehyde or primary alcohol</li>
                            <li>Hydrolysis of nitriles (RCN + H₂O → RCOOH)</li>
                            <li>Grignard + CO₂</li>
                        </ul>

                        <h4>Reactions:</h4>
                        <ul>
                            <li><strong>Esterification:</strong> RCOOH + R'OH → RCOOR' + H₂O (Fischer)</li>
                            <li><strong>Acyl Chloride Formation:</strong> RCOOH + SOCl₂ → RCOCl</li>
                            <li><strong>Decarboxylation:</strong> Heat removes CO₂</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>6. Amines</h3>
                        <p>Nitrogen derivatives. RNH₂ (primary), R₂NH (secondary), R₃N (tertiary).</p>
                        
                        <h4>Preparation:</h4>
                        <ul>
                            <li>Reduction of nitriles: RCN + 4H → RCH₂NH₂</li>
                            <li>Reduction of amides</li>
                            <li>Gabriel Synthesis: phthalimide derivative</li>
                        </ul>

                        <h4>Basicity:</h4>
                        <p>In solution: 2° > 1° > 3° (steric and solvation effects)</p>

                        <h4>Reactions:</h4>
                        <ul>
                            <li>Quaternary salt formation with alkyl halides</li>
                            <li>Acylation to form amides</li>
                            <li>Diazotization: RNH₂ + HNO₂ → RN₂⁺ (diazonium salt)</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>7. Amides</h3>
                        <p>R-CO-NH₂ (primary), R-CO-NHR' (secondary), R-CO-NR'₂ (tertiary).</p>
                        
                        <h4>Preparation:</h4>
                        <ul>
                            <li>From carboxylic acids: RCOOH + NH₃ → RCONH₂</li>
                            <li>From acyl chlorides: RCOCl + NH₃ → RCONH₂</li>
                        </ul>

                        <h4>Properties:</h4>
                        <p>Resonance reduces basicity. C-N has partial double bond character. Amide group planar.</p>

                        <h4>Reactions:</h4>
                        <ul>
                            <li>Hydrolysis to carboxylic acid and amine</li>
                            <li>Hofmann Degradation: RCONH₂ + Br₂ + NaOH → RNH₂</li>
                        </ul>
                    </div>
                `
            },
            12: {
                title: "Chapter 12: Polymers & Biomolecules",
                content: `
                    <div class="content-section">
                        <h3>1. Polymers</h3>
                        <p>Large molecules made of repeating units (monomers) linked by covalent bonds.</p>
                        
                        <h4>Classification by Polymerization:</h4>
                        
                        <h4>Addition Polymerization:</h4>
                        <ul>
                            <li>Alkene monomers add directly</li>
                            <li>No small molecule byproduct</li>
                            <li>Examples: Polythene, PVC, Teflon, Polystyrene, Polybutadiene</li>
                        </ul>

                        <h4>Condensation Polymerization:</h4>
                        <ul>
                            <li>Monomers combine with loss of small molecule (H₂O, HCl)</li>
                            <li>Examples: Polyester (RCOOCOOH), Nylon (CONH), Bakelite, Melamine</li>
                        </ul>

                        <h4>Natural Polymers:</h4>
                        <ul>
                            <li><strong>Rubber:</strong> Natural rubber is cis-polyisoprene</li>
                            <li><strong>Cellulose:</strong> Polysaccharide in plants</li>
                            <li><strong>Proteins:</strong> Polypeptides (amino acids linked by peptide bonds)</li>
                            <li><strong>DNA/RNA:</strong> Polynucleotides</li>
                        </ul>

                        <h4>Biodegradable Polymers:</h4>
                        <p>PHBV (polyhydroxybutyrate-co-hydroxyvalerate) decomposes naturally.</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Carbohydrates</h3>
                        <p>Polyhydroxy aldehydes or ketones. General formula: Cn(H₂O)m</p>
                        
                        <h4>Classification:</h4>
                        
                        <h4>Monosaccharides:</h4>
                        <ul>
                            <li>Single sugar unit: glucose, fructose, galactose (C₆H₁₂O₆)</li>
                            <li>Glucose: aldohexose, 6 carbons, aldehyde group</li>
                            <li>Fructose: ketohexose, 6 carbons, ketone group</li>
                        </ul>

                        <h4>Disaccharides:</h4>
                        <ul>
                            <li>Two monosaccharide units: sucrose, lactose, maltose (C₁₂H₂₂O₁₁)</li>
                            <li>Sucrose: glucose + fructose (table sugar)</li>
                            <li>Lactose: glucose + galactose (milk sugar)</li>
                            <li>Maltose: glucose + glucose (malt sugar)</li>
                        </ul>

                        <h4>Polysaccharides:</h4>
                        <ul>
                            <li><strong>Starch:</strong> Plant energy storage, glucose polymer</li>
                            <li><strong>Cellulose:</strong> Plant structural material, glucose polymer</li>
                            <li><strong>Glycogen:</strong> Animal energy storage, glucose polymer</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>3. Proteins</h3>
                        <p>Polypeptides made of ~20 amino acids linked by peptide bonds.</p>
                        
                        <h4>Amino Acid Structure:</h4>
                        <div class="formula-box">
                            General Structure: H₂N-CH(R)-COOH
                            <br>R = side chain (varies for 20 amino acids)
                            <br>Linked by peptide bond: -CO-NH-
                        </div>

                        <h4>Levels of Protein Structure:</h4>
                        <ul>
                            <li><strong>Primary:</strong> Amino acid sequence (order of amino acids)</li>
                            <li><strong>Secondary:</strong> α-helix or β-sheet formed by H-bonds between backbone</li>
                            <li><strong>Tertiary:</strong> 3D folding from disulfide bonds, H-bonds, hydrophobic interactions</li>
                            <li><strong>Quaternary:</strong> Multiple subunits (e.g., hemoglobin has 4 subunits)</li>
                        </ul>

                        <h4>Denaturation:</h4>
                        <p>Loss of secondary/tertiary structure by heat, pH, chemicals. Can be reversible or irreversible.</p>
                    </div>

                    <div class="content-section">
                        <h3>4. Nucleic Acids (DNA & RNA)</h3>
                        <p>Polynucleotides storing genetic information.</p>
                        
                        <h4>Nucleotide Structure:</h4>
                        <ul>
                            <li>Phosphate group</li>
                            <li>Pentose sugar (ribose in RNA, deoxyribose in DNA)</li>
                            <li>Nitrogenous base</li>
                        </ul>

                        <h4>DNA Structure:</h4>
                        <ul>
                            <li>Double helix held by H-bonds between bases</li>
                            <li>Bases: Adenine (A), Thymine (T), Guanine (G), Cytosine (C)</li>
                            <li>Base pairing: A-T (2 H-bonds), G-C (3 H-bonds)</li>
                            <li>Complementary strands run antiparallel</li>
                        </ul>

                        <h4>RNA Structure:</h4>
                        <ul>
                            <li>Single strand</li>
                            <li>Contains Uracil (U) instead of Thymine</li>
                            <li>Ribose sugar (with 2'-OH group)</li>
                            <li>mRNA carries genetic code, tRNA transfers amino acids, rRNA in ribosomes</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Enzymes</h3>
                        <p>Protein catalysts (biocatalysts) with high specificity.</p>
                        <ul>
                            <li>Lower activation energy for biochemical reactions</li>
                            <li>Enzyme-substrate complex forms (E-S → E-P → E + P)</li>
                            <li>Can be inhibited: competitive, non-competitive, irreversible</li>
                        </ul>
                    </div>
                `
            },
            13: {
                title: "Chapter 13: Chemistry in Everyday Life",
                content: `
                    <div class="content-section">
                        <h3>1. Medicines & Drugs</h3>
                        
                        <h4>Analgesics (Pain relievers):</h4>
                        <ul>
                            <li><strong>Aspirin:</strong> Acetylsalicylic acid, anti-inflammatory</li>
                            <li><strong>Ibuprofen:</strong> NSAID</li>
                            <li><strong>Paracetamol:</strong> Acetaminophen, fever reducer</li>
                        </ul>

                        <h4>Antibiotics:</h4>
                        <ul>
                            <li><strong>Penicillin:</strong> β-lactam antibiotic, inhibits cell wall synthesis</li>
                            <li><strong>Streptomycin:</strong> Inhibits protein synthesis</li>
                            <li><strong>Tetracycline:</strong> Broad-spectrum antibiotic</li>
                        </ul>

                        <h4>Antihistamines:</h4>
                        <p>For allergies and fever. Block histamine receptors.</p>

                        <h4>Antacids:</h4>
                        <ul>
                            <li>NaHCO₃ (baking soda)</li>
                            <li>Ca(OH)₂, Al(OH)₃ (bases neutralize HCl)</li>
                        </ul>

                        <h4>Antiinflammatories:</h4>
                        <p>Corticosteroids reduce inflammation.</p>
                    </div>

                    <div class="content-section">
                        <h3>2. Vitamins</h3>
                        <p>Organic compounds needed for normal metabolism.</p>
                        
                        <h4>Fat-soluble Vitamins (A, D, E, K):</h4>
                        <ul>
                            <li>Stored in body fat</li>
                            <li>Excess can be toxic</li>
                        </ul>

                        <h4>Water-soluble Vitamins (B-complex, C):</h4>
                        <ul>
                            <li>Not stored, needed regularly</li>
                            <li>B₁ (thiamine): carbohydrate metabolism</li>
                            <li>B₂ (riboflavin): energy production</li>
                            <li>Vitamin C: collagen synthesis, antioxidant</li>
                        </ul>

                        <h4>Deficiency Diseases:</h4>
                        <ul>
                            <li>Scurvy: Vitamin C deficiency</li>
                            <li>Beriberi: Vitamin B₁ deficiency</li>
                            <li>Rickets: Vitamin D deficiency</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>3. Detergents & Soaps</h3>
                        <p>Amphipathic molecules with hydrophobic tail and hydrophilic head.</p>
                        
                        <h4>Soaps:</h4>
                        <ul>
                            <li>From saponification: alkali + long-chain fatty acids</li>
                            <li>Cleaning action: form micelles around grease</li>
                        </ul>

                        <h4>Detergents:</h4>
                        <ul>
                            <li>Synthetic, more stable in hard water and low pH</li>
                            <li>Better in cold water than soaps</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>4. Food Additives</h3>
                        
                        <h4>Sweeteners:</h4>
                        <ul>
                            <li><strong>Sucrose:</strong> Natural, 1 g = 4 Cal</li>
                            <li><strong>Saccharin:</strong> Artificial, 300× sweeter than sugar, non-caloric</li>
                        </ul>

                        <h4>Preservatives:</h4>
                        <ul>
                            <li>Salt, Sugar: osmotic effect prevents microbial growth</li>
                            <li>Benzoate, SO₂: antimicrobial</li>
                        </ul>

                        <h4>Antioxidants:</h4>
                        <ul>
                            <li>BHT, BHA: prevent rancidity</li>
                            <li>Vitamin E: natural antioxidant</li>
                        </ul>
                    </div>

                    <div class="content-section">
                        <h3>5. Polymeric Materials</h3>
                        
                        <h4>Natural Polymers:</h4>
                        <ul>
                            <li><strong>Rubber:</strong> Cis-polyisoprene, elastic</li>
                            <li><strong>Cellulose:</strong> Plant cell walls</li>
                        </ul>

                        <h4>Synthetic Polymers:</h4>
                        <ul>
                            <li><strong>PVC:</strong> Pipes, flexible plastics</li>
                            <li><strong>Polystyrene:</strong> Foam, rigid plastics</li>
                            <li><strong>Nylon:</strong> Fibers, textiles</li>
                            <li><strong>Polyester:</strong> Clothing, bottles</li>
                        </ul>

                        <h4>Thermosetting Polymers:</h4>
                        <ul>
                            <li><strong>Bakelite:</strong> Heat-resistant, hard</li>
                            <li><strong>Melamine:</strong> Dishware, heat-stable</li>
                        </ul>

                        <h4>Biodegradable Polymers:</h4>
                        <p>PHBV: polyhydroxybutyrate-co-hydroxyvalerate. Decomposes naturally, environmentally friendly.</p>
                    </div>

                    <div class="content-section">
                        <h3>6. Environmental Chemistry</h3>
                        
                        <h4>Air Pollution:</h4>
                        <ul>
                            <li><strong>CO:</strong> Incomplete combustion, reduces oxygen carrying in blood</li>
                            <li><strong>NO₂, SO₂:</strong> Nitrogen and sulfur oxides from burning fuels</li>
                            <li><strong>O₃ (ozone):</strong> Ground-level pollutant causing respiratory issues</li>
                            <li><strong>Smog:</strong> Mixture of smoke and fog</li>
                        </ul>

                        <h4>Water Pollution:</h4>
                        <ul>
                            <li>Heavy metals (Pb, Hg, Cd)</li>
                            <li>Pesticides and herbicides</li>
                            <li>Organic waste causing eutrophication</li>
                        </ul>

                        <h4>Greenhouse Effect:</h4>
                        <ul>
                            <li>CO₂, CH₄, N₂O trap heat radiation</li>
                            <li>Causes global warming and climate change</li>
                        </ul>

                        <h4>Acid Rain:</h4>
                        <div class="formula-box">
                            SO₂ + H₂O → H₂SO₃ → H₂SO₄
                            <br>NOₓ + H₂O → HNO₃
                        </div>
                        <p>Damages ecosystems, corrodes buildings.</p>

                        <h4>Ozone Depletion:</h4>
                        <ul>
                            <li>CFCs release Cl radicals in stratosphere</li>
                            <li>Cl destroys O₃: Cl + O₃ → ClO + O₂</li>
                            <li>Increased UV radiation reaches Earth</li>
                        </ul>
                    </div>
                `
            }
        };

        function renderChapters() {
            const container = document.getElementById('chapters-container');
            container.innerHTML = chapters.map(ch => `
                <div class="chapter-card" onclick="openModal(${ch.id})">
                    <div style="font-size: 2em; margin-bottom: 10px;">${ch.icon}</div>
                    <h3>${ch.id}. ${ch.name}</h3>
                    <div class="chapter-meta">
                        <span class="badge badge-content">Full Content</span>
                    </div>
                </div>
            `).join('');
        }

        function showHome() {
            document.getElementById('home-section').style.display = 'block';
            document.getElementById('chapters-section').style.display = 'none';
        }

        function showAllChapters() {
            document.getElementById('home-section').style.display = 'none';
            document.getElementById('chapters-section').style.display = 'block';

            const container = document.getElementById('chapters-list');
            container.innerHTML = chapters.map(ch => `
                <div class="chapter-card" onclick="openModal(${ch.id})">
                    <div style="font-size: 2em; margin-bottom: 10px;">${ch.icon}</div>
                    <h3>${ch.id}. ${ch.name}</h3>
                    <div class="chapter-meta">
                        <span class="badge badge-content">Open Content</span>
                    </div>
                </div>
            `).join('');
        }

        function openModal(chapterId) {
            const chapter = chapters.find(c => c.id === chapterId);
            const content = detailedContent[chapterId];
            
            const modalTitle = document.getElementById('modal-title');
            const modalBody = document.getElementById('modal-body');
            
            modalTitle.innerHTML = content.title;
            modalBody.innerHTML = `
                <button class="print-btn" onclick="window.print()">🖨️ Print Chapter</button>
                ${content.content}
            `;
            
            document.getElementById('modal').classList.add('active');
        }

        function closeModal() {
            document.getElementById('modal').classList.remove('active');
        }

        // Initialize
        renderChapters();
    </script>
</body>
</html>
