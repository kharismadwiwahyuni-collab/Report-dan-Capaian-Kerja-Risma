<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Operational Dashboard | Digital Product & CS</title>
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* CSS VARIABLE UNTUK TEMA BIRU-PUTIH PROFESIONAL */
        :root {
            --bg-color: #f4f7fa; /* Abu-abu sangat muda kebiruan */
            --card-bg: #ffffff;
            --card-hover: #ffffff;
            --accent-color: #0056b3; /* Biru Profesional */
            --accent-hover: #004494;
            --text-main: #1e293b; /* Biru Gelap/Navy untuk teks */
            --text-muted: #64748b;
            --border-color: #e2e8f0;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            --shadow-hover: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* ANIMASI FADE IN */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(15px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 60px 20px;
            width: 100%;
            animation: fadeIn 0.7s ease-out;
        }

        /* HEADER SECTION */
        header {
            text-align: center;
            margin-bottom: 50px;
        }

        h1 {
            font-size: 2.2rem;
            font-weight: 800;
            letter-spacing: -0.025em;
            margin-bottom: 8px;
            color: #0f172a;
        }

        .subtitle {
            color: var(--accent-color);
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            font-size: 0.9rem;
            margin-bottom: 10px;
            display: block;
        }

        /* GRID SYSTEM */
        .dashboard-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }

        /* CARD STYLE */
        .card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 30px;
            border: 1px solid var(--border-color);
            transition: var(--transition);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            box-shadow: var(--shadow);
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
            border-color: var(--accent-color);
        }

        .card-icon {
            width: 50px;
            height: 50px;
            background: rgba(0, 86, 179, 0.08);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
            color: var(--accent-color);
        }

        .card h3 {
            font-size: 1.15rem;
            font-weight: 700;
            margin-bottom: 12px;
            color: #1e293b;
        }

        .card p {
            font-size: 0.9rem;
            color: var(--text-muted);
            margin-bottom: 30px;
            flex-grow: 1;
        }

        /* BUTTON STYLE */
        .btn-open {
            background-color: var(--accent-color);
            color: #ffffff;
            text-decoration: none;
            text-align: center;
            padding: 14px;
            border-radius: 8px;
            font-size: 0.9rem;
            font-weight: 600;
            transition: var(--transition);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-open:hover {
            background-color: var(--accent-hover);
            box-shadow: 0 4px 12px rgba(0, 86, 179, 0.2);
        }

        /* FOOTER */
        footer {
            margin-top: auto;
            text-align: center;
            padding: 50px 20px;
            color: var(--text-muted);
            font-size: 0.85rem;
            font-weight: 500;
        }

        /* RESPONSIVE */
        @media (max-width: 640px) {
            h1 { font-size: 1.75rem; }
            .container { padding: 40px 15px; }
            .dashboard-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <span class="subtitle">Monitoring & Workspace</span>
            <h1>Operational Dashboard Digital Product & Customer Service</h1>
        </header>

        <div class="dashboard-grid" id="dashboardMenu">
            <!-- Data akan di-render secara dinamis oleh JavaScript -->
        </div>

        <footer>
            Workspace Dashboard &copy; 2026 • Professional Operations Management
        </footer>
    </div>

    <script>
        // DATA CONFIGURATION
        const spreadsheetData = [
            {
                title: "DATA CUSTOMER PRODUK DIGITAL",
                desc: "Database customer & pembelian seluruh digital product secara terpusat.",
                link: "https://docs.google.com/spreadsheets/d/1LkXWVWVJKBXbcHkES5H-QzIu9ZZLUIvF78PkVAVlads/edit?usp=sharing",
                icon: `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>`
            },
            {
                title: "FOLLOW UP PEMBAYARAN BULANAN",
                desc: "Monitoring Follow up pembayaran customer agar tertagih tepat waktu.",
                link: "https://docs.google.com/spreadsheets/d/1Qe812JBGbJcDQhBP2kBse5N-XwUVDZjQHWrBsJ2NnIo/edit?usp=sharing",
                icon: `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="1" y="4" width="22" height="16" rx="2" ry="2"></rect><line x1="1" y1="10" x2="23" y2="10"></line></svg>`
            },
            {
                title: "FOLLOW UP CRM",
                desc: "Tracking upselling, cross selling & follow up customer lama.",
                link: "https://docs.google.com/spreadsheets/d/1DPWbZA9loSiqLdTXXiPNISnf8xF82lwS3X9s1Rq5Oic/edit?usp=sharing",
                icon: `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline></svg>`
            },
            {
                title: "DATA LOST DEAL",
                desc: "Monitoring Follow up calon customer yang belum closing untuk optimasi sales.",
                link: "https://docs.google.com/spreadsheets/d/1DPWbZA9loSiqLdTXXiPNISnf8xF82lwS3X9s1Rq5Oic/edit?usp=sharing",
                icon: `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="4.93" y1="4.93" x2="19.07" y2="19.07"></line></svg>`
            },
            {
                title: "PROGRES DIGITAL PRODUCT",
                desc: "Monitoring progress pembuatan ecourse, aset digital, dan pembaruan produk.",
                link: "https://docs.google.com/spreadsheets/d/1cQ8j1AlhfjayPWJDxsNwW9o5G_WFfGg-UYVQZwFmc7g/edit?usp=sharing",
                icon: `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"></path></svg>`
            },
            {
                title: "REKAPITULASI CAPAIAN KERJA",
                desc: "Dokumen rekapitulasi capaian kerja.",
                link: "https://docs.google.com/document/d/1t0ZP4q64Qc7JBRE-EWRbO7xeGNVzmXeyxDVGl4jOvXs/edit?usp=sharing",
                icon: `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><polyline points="14 2 14 8 20 8"></polyline><line x1="8" y1="13" x2="16" y2="13"></line><line x1="8" y1="17" x2="16" y2="17"></line></svg>`
            }
        ];

        // RENDER MENU KE HTML
        function renderDashboard() {
            const container = document.getElementById('dashboardMenu');
            
            spreadsheetData.forEach(item => {
                const cardHTML = `
                    <div class="card">
                        <div>
                            <div class="card-icon">
                                ${item.icon}
                            </div>
                            <h3>${item.title}</h3>
                            <p>${item.desc}</p>
                        </div>
                        <a href="${item.link}" target="_blank" class="btn-open">
                            Buka
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg>
                        </a>
                    </div>
                `;
                container.innerHTML += cardHTML;
            });
        }

        // Jalankan render saat halaman siap
        window.onload = renderDashboard;
    </script>
</body>
</html>
