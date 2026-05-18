<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="theme-color" content="#1a1a2e">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="TokoKu">
<meta name="application-name" content="TokoKu">
<meta name="msapplication-TileColor" content="#1a1a2e">
<link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAIAAADdvvtQAAAFFklEQVR4nO3dMYsdZRTG8bmbgAiaFBGFBRtbIRBJq7Ufw3SKXZqkUb+AnaWFxVZBC9MFP0Ss0toIFoLbmBUJ0bUYGAZvArn3ec97nvPO/1cm2ezc8/5zZi67SXanpzcn4Fgn2ReA2ggIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICJKr2Rfg4uf3Pzjo19968jjoSmrZbfDvhR3ayqvbYFVbCSgumpfZSEyDB9S/m31jlzRmQA7d7BuypKEC8uxm30glDRJQlXTWxsiofEAV01mrnlHhgKqns1Y3o5IBjZTOWsWMigU0ajprtTKq9LWwLdQzVXuZNTZQrZm2UmIVFdhA26xnKvLC3QMqMcQ4/i/f9xbmP7uebG9nphuIev7HdiCOAdkOK5fnWOwC8hyTCcPheAVkOCA3biNyeYh2m4s/k8dqiw1EPUcwGVp+QCaDqMhhdPkBobTkgBz+DJWWPsDMgNJf/Bhyx5gWEPU0lDjMnICop7mskSYERD1BUgbLuzBIegfE+gnVf7xdA6KeDjoPuV9A1NNNz1HzDARJp4BYP511G3iPgKgnRZ+xcwuDJDwg1k+iDsMv/K+0vvXDNyfX3si+imaefvvgr+8fZV/FwWI3EOsnXfQR8AwESWBArB8ToQfBBoIkKiDWj5W44yj8LmzfxdnDi7Mfj/jA1z68ff2Lzw/9qOe//Hr+6ZdHfLppmm6cfX3lnRvHfayVkA3E+jEUdCg8A0FCQJC0D4j7l62Io2EDQUJAkDQOiPuXueYHxAaChIAgaRkQ968S2h5T4S9lnN+5P53s1j9y+fezrIs51PlnX+2uVL34tcIB/fvnRfYlHO/y6cVl9jU0wTMQJM0C4gGokIaHxQaChIAgISBICAgSAoKEgCBpExDv4ctpdWRsIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgqRNQLeePG7y+6CbVkfGBoKEgCAhIEgICBICgoSAIGkWEO/kC2l4WGwgSAgIEgKCpGVAPAaV0PaY2ECQEBAkjQPiLmau+QGxgSAhIEjaB8RdzFbE0bCBICEgSEIC4i5mKOhQCv9vPYd68+6d1z/+qOFvePW9d9/+6buX/ewfn9z757ffG346T1G3MJaQlbjj4BkIksCAWEImQg+CDQRJbEAsoXTRR7A7Pb0Z+gn4XxByRQcUfgtjCSXqMHyegSDpERBLKEWfsXfaQDTUWbeBcwuDpF9ALKFueo666waioQ46D7n3LYyGQvUfL89AkCQExBIKkjLYnA1EQ81ljTTtFkZDDSUOM/MZiIaayB1j8kM0DYnSB8i7MEjyA0r/M1SXw+jyA5o8BlGOydDCvyPxIHz74qswSWdmsYEWVqPx5DYir4AmvwFZMRyOXUCT5ZgceI7FMaDJdViJbAfi9RC9j8dq23RmphtoYT6+aP4v3z2gqcIQg5R44e63sLXt3M5KpDMrsIEWhcaqqPUyK22gxairqFY6s5IBzUbKqGI6s8IBzapnVDedWfmAZhUzqp7ObJCAZlUyGiOd2VABLTxLGqmbxZgBLRxKGrKbxeABLfqXNHY3i60EtBYX00aiWdtiQC90aFUbbOWFCAiSSl8LgyECgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoLkP2tYOJ/Fg3LUAAAAAElFTkSuQmCC">
<link rel="manifest" id="pwaManifest">
<title>TokoKu — Belanja Online</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
:root {
  --primary: #1a1a2e;
  --accent: #e94560;
  --accent2: #f5a623;
  --bg: #f8f6f1;
  --surface: #ffffff;
  --surface2: #f0ede6;
  --text: #1a1a2e;
  --text2: #6b6880;
  --border: #e2ddd4;
  --success: #2d9e68;
  --danger: #e94560;
  --radius: 12px;
  --shadow: 0 2px 16px rgba(26,26,46,0.08);
}
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: 'DM Sans', sans-serif; background: var(--bg); color: var(--text); min-height: 100vh; }
h1,h2,h3 { font-family: 'DM Serif Display', serif; }

/* NAV */
nav {
  background: var(--primary);
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 2rem;
  height: 60px;
  position: sticky;
  top: 0;
  z-index: 100;
  box-shadow: 0 2px 20px rgba(0,0,0,0.2);
}
.nav-logo { font-family: 'DM Serif Display', serif; font-size: 1.5rem; color: var(--accent2); }
.nav-logo span { color: white; }
.nav-links { display: flex; gap: 0.25rem; align-items: center; }
.nav-btn {
  background: none;
  border: none;
  color: rgba(255,255,255,0.75);
  padding: 0.5rem 0.875rem;
  border-radius: 8px;
  cursor: pointer;
  font-family: 'DM Sans', sans-serif;
  font-size: 0.875rem;
  font-weight: 500;
  transition: all 0.2s;
  display: flex;
  align-items: center;
  gap: 6px;
}
.nav-btn:hover, .nav-btn.active { background: rgba(255,255,255,0.12); color: white; }
.nav-btn.accent { background: var(--accent); color: white; }
.nav-btn.accent:hover { background: #c73450; }
.cart-badge {
  background: var(--accent2);
  color: var(--primary);
  border-radius: 999px;
  font-size: 0.65rem;
  font-weight: 700;
  min-width: 18px;
  height: 18px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0 4px;
}

/* PAGES */
.page { display: none; padding: 2rem; max-width: 1100px; margin: 0 auto; }
.page.active { display: block; }

/* AUTH */
.auth-wrap {
  min-height: calc(100vh - 60px);
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, var(--primary) 0%, #16213e 60%, #0f3460 100%);
  padding: 2rem;
  margin: 0;
  max-width: 100%;
}
.auth-card {
  background: white;
  border-radius: 20px;
  padding: 2.5rem;
  width: 100%;
  max-width: 420px;
  box-shadow: 0 24px 64px rgba(0,0,0,0.3);
}
.auth-card h2 { font-size: 1.75rem; margin-bottom: 0.25rem; }
.auth-card p { color: var(--text2); margin-bottom: 2rem; font-size: 0.9rem; }
.auth-tabs { display: flex; background: var(--bg); border-radius: 10px; padding: 4px; margin-bottom: 1.5rem; }
.auth-tab {
  flex: 1;
  padding: 0.5rem;
  border: none;
  background: none;
  border-radius: 8px;
  cursor: pointer;
  font-family: 'DM Sans', sans-serif;
  font-size: 0.875rem;
  font-weight: 500;
  color: var(--text2);
  transition: all 0.2s;
}
.auth-tab.active { background: white; color: var(--primary); box-shadow: 0 1px 8px rgba(0,0,0,0.1); }
.form-group { margin-bottom: 1rem; }
.form-group label { display: block; font-size: 0.8rem; font-weight: 600; color: var(--text2); margin-bottom: 0.4rem; text-transform: uppercase; letter-spacing: 0.05em; }
.form-group input, .form-group select, .form-group textarea {
  width: 100%;
  padding: 0.75rem 1rem;
  border: 1.5px solid var(--border);
  border-radius: 10px;
  font-family: 'DM Sans', sans-serif;
  font-size: 0.95rem;
  transition: border-color 0.2s;
  background: white;
  color: var(--text);
}
.form-group input:focus, .form-group select:focus, .form-group textarea:focus {
  outline: none;
  border-color: var(--accent);
}
.btn {
  padding: 0.75rem 1.5rem;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  font-family: 'DM Sans', sans-serif;
  font-size: 0.95rem;
  font-weight: 600;
  transition: all 0.2s;
  display: inline-flex;
  align-items: center;
  gap: 8px;
}
.btn-primary { background: var(--accent); color: white; }
.btn-primary:hover { background: #c73450; transform: translateY(-1px); }
.btn-secondary { background: var(--surface2); color: var(--text); }
.btn-secondary:hover { background: var(--border); }
.btn-outline { background: none; border: 1.5px solid var(--border); color: var(--text); }
.btn-outline:hover { border-color: var(--accent); color: var(--accent); }
.btn-success { background: var(--success); color: white; }
.btn-danger { background: var(--danger); color: white; }
.btn-full { width: 100%; justify-content: center; }
.btn-sm { padding: 0.4rem 0.875rem; font-size: 0.8rem; }

/* ALERT */
.alert {
  padding: 0.75rem 1rem;
  border-radius: 8px;
  margin-bottom: 1rem;
  font-size: 0.875rem;
  font-weight: 500;
}
.alert-error { background: #fef2f2; color: #991b1b; border: 1px solid #fecaca; }
.alert-success { background: #f0fdf4; color: #166534; border: 1px solid #bbf7d0; }

/* HERO */
.hero {
  background: linear-gradient(135deg, var(--primary) 0%, #16213e 100%);
  color: white;
  border-radius: 20px;
  padding: 3rem;
  margin-bottom: 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  overflow: hidden;
  position: relative;
}
.hero::before {
  content: '';
  position: absolute;
  right: -60px;
  top: -60px;
  width: 300px;
  height: 300px;
  background: var(--accent);
  border-radius: 50%;
  opacity: 0.08;
}
.hero-text h1 { font-size: 2.5rem; margin-bottom: 0.5rem; line-height: 1.2; }
.hero-text p { color: rgba(255,255,255,0.7); font-size: 1rem; margin-bottom: 1.5rem; }
.hero-badge {
  background: var(--accent2);
  color: var(--primary);
  padding: 0.3rem 0.875rem;
  border-radius: 999px;
  font-size: 0.8rem;
  font-weight: 700;
  display: inline-block;
  margin-bottom: 1rem;
}
.hero-emoji { font-size: 5rem; opacity: 0.9; position: relative; z-index: 1; }

/* SEARCH & FILTER */
.search-bar {
  display: flex;
  gap: 0.75rem;
  margin-bottom: 1.5rem;
  flex-wrap: wrap;
}
.search-bar input {
  flex: 1;
  min-width: 200px;
  padding: 0.75rem 1rem;
  border: 1.5px solid var(--border);
  border-radius: 10px;
  font-family: 'DM Sans', sans-serif;
  font-size: 0.95rem;
  background: white;
}
.search-bar input:focus { outline: none; border-color: var(--accent); }
.search-bar select {
  padding: 0.75rem 1rem;
  border: 1.5px solid var(--border);
  border-radius: 10px;
  font-family: 'DM Sans', sans-serif;
  font-size: 0.875rem;
  background: white;
  cursor: pointer;
}

/* PRODUCT GRID */
.products-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));
  gap: 1.25rem;
}
.product-card {
  background: white;
  border-radius: 16px;
  overflow: hidden;
  box-shadow: var(--shadow);
  transition: transform 0.2s, box-shadow 0.2s;
  border: 1px solid var(--border);
}
.product-card:hover { transform: translateY(-3px); box-shadow: 0 8px 32px rgba(26,26,46,0.12); }
.product-img {
  height: 160px;
  background: var(--surface2);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 4rem;
  position: relative;
}
.product-badge {
  position: absolute;
  top: 10px;
  left: 10px;
  background: var(--accent);
  color: white;
  font-size: 0.7rem;
  font-weight: 700;
  padding: 0.2rem 0.6rem;
  border-radius: 999px;
}
.product-info { padding: 1rem; }
.product-category {
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: var(--text2);
  font-weight: 600;
  margin-bottom: 0.3rem;
}
.product-name { font-size: 0.95rem; font-weight: 600; margin-bottom: 0.25rem; line-height: 1.3; }
.product-price { color: var(--accent); font-weight: 700; font-size: 1.1rem; margin-bottom: 0.75rem; }
.product-stock { font-size: 0.75rem; color: var(--text2); margin-bottom: 0.75rem; }
.product-stock.low { color: #d97706; }
.product-stock.out { color: var(--danger); }
.product-actions { display: flex; gap: 0.5rem; }

/* SECTION TITLE */
.section-title {
  font-size: 1.5rem;
  margin-bottom: 1.25rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}
.section-title .count {
  font-family: 'DM Sans', sans-serif;
  font-size: 0.8rem;
  background: var(--surface2);
  padding: 0.2rem 0.75rem;
  border-radius: 999px;
  color: var(--text2);
  font-weight: 600;
}

/* CART */
.cart-empty {
  text-align: center;
  padding: 4rem 2rem;
  color: var(--text2);
}
.cart-empty .icon { font-size: 4rem; margin-bottom: 1rem; }
.cart-item {
  background: white;
  border-radius: 12px;
  padding: 1rem 1.25rem;
  margin-bottom: 0.75rem;
  display: flex;
  align-items: center;
  gap: 1rem;
  border: 1px solid var(--border);
}
.cart-item-emoji { font-size: 2.5rem; min-width: 50px; text-align: center; }
.cart-item-info { flex: 1; }
.cart-item-name { font-weight: 600; font-size: 0.95rem; }
.cart-item-price { color: var(--text2); font-size: 0.85rem; }
.qty-control { display: flex; align-items: center; gap: 0.5rem; }
.qty-btn {
  width: 32px;
  height: 32px;
  border: 1.5px solid var(--border);
  background: white;
  border-radius: 8px;
  cursor: pointer;
  font-size: 1rem;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: all 0.2s;
}
.qty-btn:hover { border-color: var(--accent); color: var(--accent); }
.qty-val { font-weight: 600; min-width: 28px; text-align: center; }
.cart-item-total { font-weight: 700; color: var(--accent); min-width: 80px; text-align: right; }
.cart-summary {
  background: white;
  border-radius: 16px;
  padding: 1.5rem;
  border: 1px solid var(--border);
  margin-top: 1.5rem;
  max-width: 400px;
  margin-left: auto;
}
.summary-row {
  display: flex;
  justify-content: space-between;
  margin-bottom: 0.75rem;
  font-size: 0.9rem;
  color: var(--text2);
}
.summary-row.total {
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--text);
  border-top: 1.5px solid var(--border);
  padding-top: 0.75rem;
  margin-top: 0.75rem;
}
.summary-row.total span:last-child { color: var(--accent); }

/* ADMIN */
.admin-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin-bottom: 2rem;
}
.stat-card {
  background: white;
  border-radius: 14px;
  padding: 1.25rem;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}
.stat-label { font-size: 0.75rem; text-transform: uppercase; letter-spacing: 0.06em; color: var(--text2); font-weight: 600; margin-bottom: 0.5rem; }
.stat-value { font-size: 2rem; font-family: 'DM Serif Display', serif; }
.stat-icon { font-size: 1.75rem; margin-bottom: 0.5rem; }

/* TABLE */
.table-wrap { overflow-x: auto; }
table { width: 100%; border-collapse: collapse; background: white; border-radius: 14px; overflow: hidden; box-shadow: var(--shadow); }
thead { background: var(--primary); color: white; }
th { padding: 0.875rem 1rem; text-align: left; font-size: 0.8rem; text-transform: uppercase; letter-spacing: 0.05em; font-weight: 600; }
td { padding: 0.875rem 1rem; border-bottom: 1px solid var(--border); font-size: 0.9rem; vertical-align: middle; }
tr:last-child td { border-bottom: none; }
tr:hover td { background: var(--bg); }

/* MODAL */
.modal-overlay {
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.5);
  z-index: 200;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1rem;
  backdrop-filter: blur(4px);
}
.modal-overlay.hidden { display: none; }
.modal {
  background: white;
  border-radius: 20px;
  padding: 2rem;
  width: 100%;
  max-width: 500px;
  max-height: 90vh;
  overflow-y: auto;
  box-shadow: 0 32px 80px rgba(0,0,0,0.3);
}
.modal-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1.5rem;
}
.modal-close {
  background: var(--surface2);
  border: none;
  width: 32px;
  height: 32px;
  border-radius: 8px;
  cursor: pointer;
  font-size: 1.2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: background 0.2s;
}
.modal-close:hover { background: var(--border); }

/* ORDERS */
.order-card {
  background: white;
  border-radius: 14px;
  padding: 1.25rem;
  margin-bottom: 0.75rem;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}
.order-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.75rem; flex-wrap: wrap; gap: 0.5rem; }
.order-id { font-size: 0.8rem; color: var(--text2); font-family: monospace; }
.status-badge {
  padding: 0.25rem 0.75rem;
  border-radius: 999px;
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.04em;
}
.status-pending { background: #fef3c7; color: #92400e; }
.status-processing { background: #dbeafe; color: #1e40af; }
.status-shipped { background: #e0e7ff; color: #3730a3; }
.status-delivered { background: #d1fae5; color: #065f46; }
.status-cancelled { background: #fee2e2; color: #991b1b; }

/* PROFILE */
.profile-card {
  background: white;
  border-radius: 20px;
  padding: 2rem;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
  max-width: 600px;
}
.profile-avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  background: var(--primary);
  color: var(--accent2);
  font-size: 2rem;
  font-family: 'DM Serif Display', serif;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
}
.profile-name { font-size: 1.5rem; margin-bottom: 0.25rem; }
.profile-role {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--surface2);
  padding: 0.3rem 0.875rem;
  border-radius: 999px;
  font-size: 0.8rem;
  font-weight: 600;
  color: var(--text2);
  margin-bottom: 1.5rem;
}
.profile-role.admin { background: #fef3c7; color: #92400e; }

/* TOAST */
.toast {
  position: fixed;
  bottom: 2rem;
  right: 2rem;
  background: var(--primary);
  color: white;
  padding: 0.875rem 1.5rem;
  border-radius: 12px;
  box-shadow: 0 8px 32px rgba(0,0,0,0.2);
  z-index: 300;
  transform: translateY(100px);
  opacity: 0;
  transition: all 0.3s ease;
  font-size: 0.9rem;
  font-weight: 500;
  display: flex;
  align-items: center;
  gap: 8px;
}
.toast.show { transform: translateY(0); opacity: 1; }
.toast.success { background: var(--success); }
.toast.error { background: var(--danger); }

/* NO RESULTS */
.no-results {
  text-align: center;
  padding: 3rem;
  color: var(--text2);
  grid-column: 1/-1;
}
.no-results .icon { font-size: 3rem; margin-bottom: 0.75rem; }

/* TABS */
.tabs { display: flex; gap: 0.25rem; margin-bottom: 1.5rem; border-bottom: 2px solid var(--border); padding-bottom: 0; }
.tab-btn {
  padding: 0.75rem 1.25rem;
  border: none;
  background: none;
  cursor: pointer;
  font-family: 'DM Sans', sans-serif;
  font-size: 0.9rem;
  font-weight: 500;
  color: var(--text2);
  border-bottom: 2px solid transparent;
  margin-bottom: -2px;
  transition: all 0.2s;
}
.tab-btn.active { color: var(--accent); border-bottom-color: var(--accent); font-weight: 600; }
.tab-btn:hover { color: var(--text); }

/* CHECKOUT FORM */
.checkout-grid { display: grid; grid-template-columns: 1fr 360px; gap: 1.5rem; align-items: start; }
@media (max-width: 768px) { .checkout-grid { grid-template-columns: 1fr; } }

/* PRODUCT DETAIL */
.product-detail-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; align-items: start; }
@media (max-width: 640px) { .product-detail-grid { grid-template-columns: 1fr; } }
.product-detail-img {
  border-radius: 20px;
  background: var(--surface2);
  height: 320px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 8rem;
}

/* EMPTY STATE */
.empty-state { text-align: center; padding: 4rem 2rem; }
.empty-state .icon { font-size: 5rem; margin-bottom: 1rem; }
.empty-state h3 { font-size: 1.5rem; margin-bottom: 0.5rem; }
.empty-state p { color: var(--text2); margin-bottom: 1.5rem; }

/* REGISTER FORM in AUTH */
.register-fields { display: none; }
.register-fields.active { display: block; }

input[type="number"] { -moz-appearance: textfield; }
input[type="number"]::-webkit-outer-spin-button,
input[type="number"]::-webkit-inner-spin-button { -webkit-appearance: none; }

/* Scrollbar */
::-webkit-scrollbar { width: 6px; height: 6px; }
::-webkit-scrollbar-track { background: transparent; }
::-webkit-scrollbar-thumb { background: var(--border); border-radius: 999px; }
</style>
</head>
<body>

<!-- NAVBAR -->
<nav>
  <div class="nav-logo">Toko<span>Ku</span></div>
  <div class="nav-links" id="navLinks">
    <!-- Will be rendered by JS -->
  </div>
</nav>

<!-- TOAST -->
<div class="toast" id="toast"></div>

<!-- MODAL: Add/Edit Product -->
<div class="modal-overlay hidden" id="productModal">
  <div class="modal">
    <div class="modal-header">
      <h3 id="modalTitle">Tambah Produk</h3>
      <button class="modal-close" onclick="closeModal()">✕</button>
    </div>
    <div id="modalAlert"></div>
    <div class="form-group">
      <label>Foto Produk</label>
      <div id="imgUploadArea" onclick="document.getElementById('pImgInput').click()" style="border:2px dashed var(--border);border-radius:12px;padding:1.25rem;text-align:center;cursor:pointer;transition:border-color 0.2s;position:relative;background:var(--bg);">
        <div id="imgPreviewWrap" style="display:none;position:relative;">
          <img id="imgPreview" style="max-height:160px;max-width:100%;border-radius:8px;object-fit:cover;" src="">
          <button onclick="clearImage(event)" style="position:absolute;top:6px;right:6px;background:rgba(0,0,0,0.6);color:white;border:none;border-radius:999px;width:26px;height:26px;cursor:pointer;font-size:0.8rem;display:flex;align-items:center;justify-content:center;">✕</button>
        </div>
        <div id="imgPlaceholder">
          <div style="font-size:2.5rem;margin-bottom:0.5rem;">🖼️</div>
          <div style="font-size:0.875rem;color:var(--text2);">Klik untuk upload foto produk</div>
          <div style="font-size:0.75rem;color:var(--text2);margin-top:0.25rem;">JPG, PNG, WEBP — maks. 2MB</div>
        </div>
      </div>
      <input type="file" id="pImgInput" accept="image/*" style="display:none" onchange="handleImageUpload(event)">
      <input type="hidden" id="pImgData">
    </div>
    <div class="form-group">
      <label>Emoji Cadangan (jika tidak upload foto)</label>
      <input type="text" id="pEmoji" placeholder="Contoh: 👟 📱 👜" maxlength="4">
    </div>
    <div class="form-group">
      <label>Nama Produk *</label>
      <input type="text" id="pName" placeholder="Nama produk...">
    </div>
    <div class="form-group">
      <label>Kategori *</label>
      <select id="pCategory">
        <option value="">Pilih kategori</option>
        <option>Elektronik</option>
        <option>Fashion</option>
        <option>Makanan & Minuman</option>
        <option>Kesehatan</option>
        <option>Olahraga</option>
        <option>Rumah & Dapur</option>
        <option>Buku</option>
        <option>Lainnya</option>
      </select>
    </div>
    <div class="form-group">
      <label>Harga (Rp) *</label>
      <input type="number" id="pPrice" placeholder="0" min="0">
    </div>
    <div class="form-group">
      <label>Stok *</label>
      <input type="number" id="pStock" placeholder="0" min="0">
    </div>
    <div class="form-group">
      <label>Deskripsi</label>
      <textarea id="pDesc" rows="3" placeholder="Deskripsi produk..."></textarea>
    </div>
    <div style="display:flex;gap:0.75rem;justify-content:flex-end;margin-top:1rem;">
      <button class="btn btn-secondary" onclick="closeModal()">Batal</button>
      <button class="btn btn-primary" onclick="saveProduct()">Simpan Produk</button>
    </div>
  </div>
</div>

<!-- MODAL: Checkout -->
<div class="modal-overlay hidden" id="checkoutModal">
  <div class="modal">
    <div class="modal-header">
      <h3>Checkout</h3>
      <button class="modal-close" onclick="closeCheckout()">✕</button>
    </div>
    <div class="form-group">
      <label>Nama Lengkap</label>
      <input type="text" id="coName" placeholder="Nama penerima">
    </div>
    <div class="form-group">
      <label>Alamat Pengiriman</label>
      <textarea id="coAddr" rows="2" placeholder="Jl. ..."></textarea>
    </div>
    <div class="form-group">
      <label>No. Telepon</label>
      <input type="text" id="coPhone" placeholder="08xx...">
    </div>
    <div class="form-group">
      <label>Metode Pembayaran</label>
      <select id="coPayment">
        <option>Transfer Bank (BCA)</option>
        <option>Transfer Bank (Mandiri)</option>
        <option>GoPay</option>
        <option>OVO</option>
        <option>Dana</option>
        <option>COD (Bayar di Tempat)</option>
      </select>
    </div>
    <div class="form-group">
      <label>Metode Pengiriman</label>
      <select id="coShipping" onchange="updateShippingCost()">
        <option value="15000">JNE Regular (Rp 15.000)</option>
        <option value="25000">JNE YES (Rp 25.000)</option>
        <option value="12000">J&T Express (Rp 12.000)</option>
        <option value="0">GoSend Same Day (Rp 0 - Gratis)</option>
      </select>
    </div>
    <div style="background:var(--bg);border-radius:10px;padding:1rem;margin-bottom:1rem;">
      <div class="summary-row"><span>Subtotal</span><span id="coSubtotal">-</span></div>
      <div class="summary-row"><span>Ongkos Kirim</span><span id="coShippingCost">-</span></div>
      <div class="summary-row total"><span>Total</span><span id="coTotal">-</span></div>
    </div>
    <div id="coAlert"></div>
    <button class="btn btn-primary btn-full" onclick="placeOrder()">Bayar Sekarang 🎉</button>
  </div>
</div>

<!-- MODAL: Order Success -->
<div class="modal-overlay hidden" id="successModal">
  <div class="modal" style="text-align:center;">
    <div style="font-size:4rem;margin-bottom:1rem;">🎉</div>
    <h2 style="margin-bottom:0.5rem;">Pesanan Berhasil!</h2>
    <p style="color:var(--text2);margin-bottom:0.5rem;">Terima kasih sudah berbelanja di TokoKu</p>
    <p id="successOrderId" style="font-family:monospace;color:var(--accent);font-weight:700;margin-bottom:1.5rem;"></p>
    <div id="successDetail" style="text-align:left;background:var(--bg);border-radius:10px;padding:1rem;margin-bottom:1.5rem;font-size:0.875rem;"></div>
    <div style="display:flex;gap:0.75rem;justify-content:center;flex-wrap:wrap;">
      <button class="btn btn-secondary" onclick="closeSuccess();showPage('orders')">Lihat Pesanan</button>
      <button class="btn btn-primary" onclick="closeSuccess();showPage('shop')">Lanjut Belanja</button>
    </div>
  </div>
</div>

<!-- ======================== PAGES ======================== -->

<!-- LOGIN PAGE -->
<div class="page active" id="page-login" style="padding:0;max-width:100%;">
  <div class="auth-wrap">
    <div class="auth-card">
      <h2>Selamat Datang 👋</h2>
      <p>Login atau daftar untuk mulai berbelanja</p>
      <div class="auth-tabs">
        <button class="auth-tab active" onclick="switchAuthTab('login')">Login</button>
        <button class="auth-tab" onclick="switchAuthTab('register')">Daftar</button>
      </div>
      <div id="authAlert"></div>
      <!-- LOGIN FORM -->
      <div id="loginForm">
        <div class="form-group">
          <label>Email</label>
          <input type="email" id="loginEmail" placeholder="email@contoh.com" onkeydown="if(event.key==='Enter')doLogin()">
        </div>
        <div class="form-group">
          <label>Password</label>
          <input type="password" id="loginPass" placeholder="••••••••" onkeydown="if(event.key==='Enter')doLogin()">
        </div>
        <button class="btn btn-primary btn-full" onclick="doLogin()">Login →</button>
        <div style="margin-top:1.25rem;padding:0.875rem;background:var(--bg);border-radius:10px;font-size:0.8rem;color:var(--text2);">
          <strong>Demo akun:</strong><br>
          👑 Admin: admin@tokoku.com / admin123<br>
          🛍️ User: user@tokoku.com / user123
        </div>
      </div>
      <!-- REGISTER FORM -->
      <div id="registerForm" style="display:none;">
        <div class="form-group">
          <label>Nama Lengkap</label>
          <input type="text" id="regName" placeholder="Nama kamu">
        </div>
        <div class="form-group">
          <label>Email</label>
          <input type="email" id="regEmail" placeholder="email@contoh.com">
        </div>
        <div class="form-group">
          <label>Password</label>
          <input type="password" id="regPass" placeholder="Min. 6 karakter">
        </div>
        <div class="form-group">
          <label>Konfirmasi Password</label>
          <input type="password" id="regPass2" placeholder="Ulangi password">
        </div>
        <button class="btn btn-primary btn-full" onclick="doRegister()">Daftar Sekarang →</button>
      </div>
    </div>
  </div>
</div>

<!-- SHOP PAGE -->
<div class="page" id="page-shop">
  <div class="hero">
    <div class="hero-text">
      <div class="hero-badge">✨ Promo Hari Ini</div>
      <h1>Belanja<br>Lebih Hemat</h1>
      <p>Ribuan produk pilihan dengan harga terbaik</p>
      <button class="btn btn-primary" onclick="document.getElementById('searchInput').focus()">🔍 Cari Produk</button>
    </div>
    <div class="hero-emoji">🛍️</div>
  </div>

  <div class="search-bar">
    <input type="text" id="searchInput" placeholder="🔍 Cari produk..." oninput="renderShop()">
    <select id="filterCategory" onchange="renderShop()">
      <option value="">Semua Kategori</option>
    </select>
    <select id="sortBy" onchange="renderShop()">
      <option value="newest">Terbaru</option>
      <option value="price-asc">Harga ↑</option>
      <option value="price-desc">Harga ↓</option>
      <option value="name">Nama A-Z</option>
    </select>
  </div>

  <div class="section-title">
    <h2>Produk</h2>
    <span class="count" id="productCount">0 produk</span>
  </div>
  <div class="products-grid" id="shopGrid"></div>
</div>

<!-- CART PAGE -->
<div class="page" id="page-cart">
  <div class="section-title"><h2>🛒 Keranjang Belanja</h2></div>
  <div id="cartContent"></div>
</div>

<!-- ORDERS PAGE -->
<div class="page" id="page-orders">
  <div class="section-title"><h2>📦 Pesanan Saya</h2></div>
  <div id="ordersContent"></div>
</div>

<!-- PROFILE PAGE -->
<div class="page" id="page-profile">
  <div class="section-title"><h2>👤 Profil Saya</h2></div>
  <div id="profileContent"></div>
</div>

<!-- ADMIN PAGE -->
<div class="page" id="page-admin">
  <div class="section-title"><h2>⚙️ Panel Admin</h2></div>
  <div class="tabs">
    <button class="tab-btn active" onclick="switchAdminTab('dashboard')">Dashboard</button>
    <button class="tab-btn" onclick="switchAdminTab('products')">Produk</button>
    <button class="tab-btn" onclick="switchAdminTab('orders')">Pesanan</button>
    <button class="tab-btn" onclick="switchAdminTab('users')">Pengguna</button>
  </div>
  <div id="adminContent"></div>
</div>

<script>
// ===== DATA STORE =====
const STORAGE_KEYS = { products:'tk_products', users:'tk_users', orders:'tk_orders', cart:'tk_cart', session:'tk_session' };

function save(key, data) { try { localStorage.setItem(key, JSON.stringify(data)); } catch(e) {} }
function load(key, def) { try { const d=localStorage.getItem(key); return d?JSON.parse(d):def; } catch(e){ return def; } }

// Initialize default data
function initData() {
  if (!localStorage.getItem(STORAGE_KEYS.users)) {
    save(STORAGE_KEYS.users, [
      { id:'u1', name:'Admin TokoKu', email:'admin@tokoku.com', password:'admin123', role:'admin', createdAt: new Date().toISOString() },
      { id:'u2', name:'Budi Santoso', email:'user@tokoku.com', password:'user123', role:'user', createdAt: new Date().toISOString() }
    ]);
  }
  if (!localStorage.getItem(STORAGE_KEYS.products)) {
    save(STORAGE_KEYS.products, [
      { id:'p1', name:'iPhone 15 Pro', emoji:'📱', category:'Elektronik', price:18999000, stock:15, desc:'Smartphone terbaru Apple dengan chip A17 Pro, kamera 48MP, dan Dynamic Island.', createdAt: new Date().toISOString() },
      { id:'p2', name:'Nike Air Max 270', emoji:'👟', category:'Fashion', price:1350000, stock:30, desc:'Sepatu sneaker ikonik dengan cushioning Air Max untuk kenyamanan maksimal.', createdAt: new Date().toISOString() },
      { id:'p3', name:'Kopi Arabika Premium', emoji:'☕', category:'Makanan & Minuman', price:85000, stock:100, desc:'Biji kopi Arabika pilihan dari Gayo, Aceh. Rasa fruity dan aroma harum.', createdAt: new Date().toISOString() },
      { id:'p4', name:'Headphone Sony WH-1000XM5', emoji:'🎧', category:'Elektronik', price:4500000, stock:20, desc:'Headphone noise-cancelling terbaik dengan 30 jam battery dan audio hi-res.', createdAt: new Date().toISOString() },
      { id:'p5', name:'Yoga Mat Premium', emoji:'🧘', category:'Olahraga', price:325000, stock:50, desc:'Matras yoga anti-slip tebal 6mm, material eco-friendly TPE.', createdAt: new Date().toISOString() },
      { id:'p6', name:'Novel "Laut Bercerita"', emoji:'📚', category:'Buku', price:89000, stock:75, desc:'Novel best seller karya Leila S. Chudori tentang aktivis 1998.', createdAt: new Date().toISOString() },
    ]);
  }
  if (!localStorage.getItem(STORAGE_KEYS.orders)) save(STORAGE_KEYS.orders, []);
  if (!localStorage.getItem(STORAGE_KEYS.cart)) save(STORAGE_KEYS.cart, []);
}

// ===== AUTH =====
let currentUser = null;

function getUsers() { return load(STORAGE_KEYS.users, []); }
function getProducts() { return load(STORAGE_KEYS.products, []); }
function getOrders() { return load(STORAGE_KEYS.orders, []); }
function getCart() { return load(STORAGE_KEYS.cart, []); }

function saveSession(user) {
  currentUser = user;
  save(STORAGE_KEYS.session, user);
}
function clearSession() { currentUser = null; localStorage.removeItem(STORAGE_KEYS.session); }

function checkSession() {
  const s = load(STORAGE_KEYS.session, null);
  if (s) {
    const users = getUsers();
    const found = users.find(u => u.id === s.id);
    if (found) { currentUser = found; return true; }
  }
  return false;
}

function switchAuthTab(tab) {
  document.querySelectorAll('.auth-tab').forEach((t,i)=>t.classList.toggle('active', (i===0&&tab==='login')||(i===1&&tab==='register')));
  document.getElementById('loginForm').style.display = tab==='login'?'block':'none';
  document.getElementById('registerForm').style.display = tab==='register'?'block':'none';
  document.getElementById('authAlert').innerHTML = '';
}

function doLogin() {
  const email = document.getElementById('loginEmail').value.trim();
  const pass = document.getElementById('loginPass').value;
  const users = getUsers();
  const user = users.find(u => u.email===email && u.password===pass);
  if (!user) {
    document.getElementById('authAlert').innerHTML = '<div class="alert alert-error">❌ Email atau password salah</div>';
    return;
  }
  saveSession(user);
  renderApp();
  showPage(user.role==='admin'?'admin':'shop');
  showToast('Halo, '+user.name+'! Selamat berbelanja 👋', 'success');
}

function doRegister() {
  const name = document.getElementById('regName').value.trim();
  const email = document.getElementById('regEmail').value.trim();
  const pass = document.getElementById('regPass').value;
  const pass2 = document.getElementById('regPass2').value;
  const alertEl = document.getElementById('authAlert');
  if (!name||!email||!pass) { alertEl.innerHTML='<div class="alert alert-error">Semua field wajib diisi</div>'; return; }
  if (pass.length < 6) { alertEl.innerHTML='<div class="alert alert-error">Password minimal 6 karakter</div>'; return; }
  if (pass !== pass2) { alertEl.innerHTML='<div class="alert alert-error">Password tidak cocok</div>'; return; }
  const users = getUsers();
  if (users.find(u=>u.email===email)) { alertEl.innerHTML='<div class="alert alert-error">Email sudah terdaftar</div>'; return; }
  const newUser = { id:'u'+Date.now(), name, email, password:pass, role:'user', createdAt:new Date().toISOString() };
  users.push(newUser);
  save(STORAGE_KEYS.users, users);
  saveSession(newUser);
  renderApp();
  showPage('shop');
  showToast('Registrasi berhasil! Selamat berbelanja 🎉', 'success');
}

function doLogout() {
  clearSession();
  save(STORAGE_KEYS.cart, []);
  renderApp();
  showPage('login');
  showToast('Berhasil logout. Sampai jumpa!');
}

// ===== NAVIGATION =====
let currentPage = 'login';
let editingProductId = null;
let currentAdminTab = 'dashboard';

function showPage(page) {
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-'+page).classList.add('active');
  currentPage = page;
  updateNavActive();
  if (page==='shop') renderShop();
  if (page==='cart') renderCart();
  if (page==='orders') renderOrders();
  if (page==='profile') renderProfile();
  if (page==='admin') renderAdmin();
  window.scrollTo(0,0);
}

function updateNavActive() {
  document.querySelectorAll('.nav-btn[data-page]').forEach(b=>{
    b.classList.toggle('active', b.dataset.page===currentPage);
  });
}

function renderApp() {
  const nav = document.getElementById('navLinks');
  if (!currentUser) {
    nav.innerHTML = '';
    return;
  }
  const cartCount = getCart().reduce((s,i)=>s+i.qty,0);
  const badge = cartCount>0?`<span class="cart-badge">${cartCount}</span>`:'';
  let links = `
    <button class="nav-btn" data-page="shop" onclick="showPage('shop')">🏪 Toko</button>
    <button class="nav-btn" data-page="cart" onclick="showPage('cart')">🛒 Keranjang ${badge}</button>
    <button class="nav-btn" data-page="orders" onclick="showPage('orders')">📦 Pesanan</button>
  `;
  if (currentUser.role==='admin') {
    links += `<button class="nav-btn" data-page="admin" onclick="showPage('admin')">⚙️ Admin</button>`;
  }
  links += `
    <button class="nav-btn" data-page="profile" onclick="showPage('profile')">👤 ${currentUser.name.split(' ')[0]}</button>
    <button class="nav-btn accent" onclick="doLogout()">Logout</button>
  `;
  nav.innerHTML = links;
  updateNavActive();
}

// ===== SHOP =====
function renderShop() {
  const search = (document.getElementById('searchInput')||{value:''}).value.toLowerCase();
  const catFilter = (document.getElementById('filterCategory')||{value:''}).value;
  const sortBy = (document.getElementById('sortBy')||{value:'newest'}).value;
  let products = getProducts().filter(p=>p.stock>0);

  // Update category dropdown
  const catSel = document.getElementById('filterCategory');
  if (catSel) {
    const cats = [...new Set(getProducts().map(p=>p.category))];
    const cur = catSel.value;
    catSel.innerHTML = '<option value="">Semua Kategori</option>'+cats.map(c=>`<option ${c===cur?'selected':''}>${c}</option>`).join('');
  }

  if (search) products = products.filter(p=>p.name.toLowerCase().includes(search)||p.category.toLowerCase().includes(search)||p.desc.toLowerCase().includes(search));
  if (catFilter) products = products.filter(p=>p.category===catFilter);

  if (sortBy==='price-asc') products.sort((a,b)=>a.price-b.price);
  else if (sortBy==='price-desc') products.sort((a,b)=>b.price-a.price);
  else if (sortBy==='name') products.sort((a,b)=>a.name.localeCompare(b.name));
  else products.sort((a,b)=>new Date(b.createdAt)-new Date(a.createdAt));

  const grid = document.getElementById('shopGrid');
  const count = document.getElementById('productCount');
  if (count) count.textContent = products.length+' produk';

  if (products.length===0) {
    grid.innerHTML = '<div class="no-results"><div class="icon">🔍</div><p>Produk tidak ditemukan</p></div>';
    return;
  }

  grid.innerHTML = products.map(p=>{
    const isNew = (Date.now()-new Date(p.createdAt).getTime())<7*24*3600*1000;
    const imgContent = p.image
      ? `<img src="${p.image}" alt="${p.name}" style="width:100%;height:100%;object-fit:cover;">`
      : `<span style="font-size:4rem;">${p.emoji||'📦'}</span>`;
    return `
    <div class="product-card">
      <div class="product-img" style="${p.image?'padding:0;overflow:hidden;':''}">
        ${imgContent}
        ${isNew?'<span class="product-badge">Baru</span>':''}
      </div>
      <div class="product-info">
        <div class="product-category">${p.category}</div>
        <div class="product-name">${p.name}</div>
        <div class="product-price">${formatRp(p.price)}</div>
        <div class="product-stock ${p.stock<=5?'low':''}">${p.stock<=5?'⚠️ Sisa '+p.stock:p.stock+' tersedia'}</div>
        <div class="product-actions">
          <button class="btn btn-primary btn-sm" style="flex:1" onclick="addToCart('${p.id}')">🛒 Tambah</button>
          <button class="btn btn-outline btn-sm" onclick="viewProduct('${p.id}')">👁</button>
        </div>
      </div>
    </div>`;
  }).join('');
}

function viewProduct(id) {
  const p = getProducts().find(x=>x.id===id);
  if (!p) return;
  // Simple product view as modal content override
  document.getElementById('modalTitle').textContent = p.name;
  document.getElementById('modalAlert').innerHTML = `
    <div style="background:var(--surface2);border-radius:12px;margin-bottom:1rem;overflow:hidden;height:200px;display:flex;align-items:center;justify-content:center;">
      ${p.image?`<img src="${p.image}" alt="${p.name}" style="width:100%;height:100%;object-fit:cover;">`:`<span style="font-size:5rem;">${p.emoji||'📦'}</span>`}
    </div>
    <div style="margin-bottom:0.75rem;"><span style="font-size:0.75rem;color:var(--text2);text-transform:uppercase;letter-spacing:0.06em;">${p.category}</span></div>
    <p style="color:var(--text2);font-size:0.9rem;margin-bottom:1rem;">${p.desc||'Tidak ada deskripsi'}</p>
    <div style="display:flex;justify-content:space-between;align-items:center;background:var(--bg);border-radius:10px;padding:1rem;margin-bottom:1rem;">
      <div><div style="font-size:0.75rem;color:var(--text2);">Harga</div><div style="font-size:1.4rem;font-weight:700;color:var(--accent);">${formatRp(p.price)}</div></div>
      <div><div style="font-size:0.75rem;color:var(--text2);">Stok</div><div style="font-size:1.2rem;font-weight:600;">${p.stock} pcs</div></div>
    </div>
    <button class="btn btn-primary btn-full" onclick="addToCart('${p.id}');closeModal()">🛒 Tambah ke Keranjang</button>
    <div style="height:1rem;"></div>
  `;
  // Hide save button for view mode
  document.querySelector('#productModal .btn-primary[onclick="saveProduct()"]').style.display='none';
  document.querySelector('#productModal .btn-secondary').textContent='Tutup';
  document.getElementById('productModal').classList.remove('hidden');
}

// ===== CART =====
function addToCart(productId) {
  if (!currentUser) { showPage('login'); return; }
  const p = getProducts().find(x=>x.id===productId);
  if (!p||p.stock<=0) { showToast('Stok habis!','error'); return; }
  let cart = getCart();
  const idx = cart.findIndex(x=>x.productId===productId);
  if (idx>=0) {
    if (cart[idx].qty >= p.stock) { showToast('Stok tidak mencukupi!','error'); return; }
    cart[idx].qty++;
  } else {
    cart.push({ productId, qty:1 });
  }
  save(STORAGE_KEYS.cart, cart);
  showToast('✅ '+p.name+' ditambahkan ke keranjang!','success');
  renderApp();
}

function updateQty(productId, delta) {
  let cart = getCart();
  const idx = cart.findIndex(x=>x.productId===productId);
  if (idx<0) return;
  const p = getProducts().find(x=>x.id===productId);
  cart[idx].qty = Math.max(0, Math.min(cart[idx].qty+delta, p?p.stock:999));
  if (cart[idx].qty===0) cart.splice(idx,1);
  save(STORAGE_KEYS.cart, cart);
  renderCart();
  renderApp();
}

function removeFromCart(productId) {
  let cart = getCart().filter(x=>x.productId!==productId);
  save(STORAGE_KEYS.cart, cart);
  renderCart();
  renderApp();
  showToast('Item dihapus dari keranjang');
}

function renderCart() {
  const cart = getCart();
  const products = getProducts();
  const el = document.getElementById('cartContent');
  if (cart.length===0) {
    el.innerHTML = `<div class="empty-state"><div class="icon">🛒</div><h3>Keranjang Kosong</h3><p>Belum ada produk di keranjang</p><button class="btn btn-primary" onclick="showPage('shop')">Mulai Belanja</button></div>`;
    return;
  }
  let subtotal=0;
  const items = cart.map(item=>{
    const p=products.find(x=>x.id===item.productId);
    if(!p) return '';
    const total=p.price*item.qty;
    subtotal+=total;
    return `<div class="cart-item">
      <div class="cart-item-emoji">${p.emoji||'📦'}</div>
      <div class="cart-item-info">
        <div class="cart-item-name">${p.name}</div>
        <div class="cart-item-price">${formatRp(p.price)} × ${item.qty}</div>
      </div>
      <div class="qty-control">
        <button class="qty-btn" onclick="updateQty('${item.productId}',-1)">−</button>
        <span class="qty-val">${item.qty}</span>
        <button class="qty-btn" onclick="updateQty('${item.productId}',1)">+</button>
      </div>
      <div class="cart-item-total">${formatRp(total)}</div>
      <button class="btn btn-danger btn-sm" onclick="removeFromCart('${item.productId}')">🗑</button>
    </div>`;
  }).join('');
  el.innerHTML = items + `
    <div class="cart-summary">
      <div class="summary-row"><span>Subtotal (${cart.reduce((s,i)=>s+i.qty,0)} item)</span><span>${formatRp(subtotal)}</span></div>
      <div class="summary-row total"><span>Estimasi Total</span><span>${formatRp(subtotal)}</span></div>
      <div style="display:flex;gap:0.75rem;margin-top:1rem;flex-wrap:wrap;">
        <button class="btn btn-outline" onclick="save('${STORAGE_KEYS.cart}',[]);renderCart();renderApp();showToast('Keranjang dikosongkan')">Kosongkan</button>
        <button class="btn btn-primary" style="flex:1" onclick="openCheckout()">Checkout →</button>
      </div>
    </div>`;
}

// ===== CHECKOUT =====
function openCheckout() {
  if (!currentUser) { showPage('login'); return; }
  const cart = getCart();
  if (cart.length===0) { showToast('Keranjang kosong!','error'); return; }
  if (currentUser) {
    document.getElementById('coName').value = currentUser.name||'';
  }
  updateCheckoutSummary();
  document.getElementById('checkoutModal').classList.remove('hidden');
}

function updateCheckoutSummary() {
  const cart = getCart();
  const products = getProducts();
  let subtotal = cart.reduce((s,i)=>{
    const p=products.find(x=>x.id===i.productId);
    return s+(p?p.price*i.qty:0);
  },0);
  const shipping = parseInt((document.getElementById('coShipping')||{value:'15000'}).value)||0;
  document.getElementById('coSubtotal').textContent = formatRp(subtotal);
  document.getElementById('coShippingCost').textContent = shipping===0?'Gratis':formatRp(shipping);
  document.getElementById('coTotal').textContent = formatRp(subtotal+shipping);
}

function updateShippingCost() { updateCheckoutSummary(); }
function closeCheckout() { document.getElementById('checkoutModal').classList.add('hidden'); }

function placeOrder() {
  const name = document.getElementById('coName').value.trim();
  const addr = document.getElementById('coAddr').value.trim();
  const phone = document.getElementById('coPhone').value.trim();
  const payment = document.getElementById('coPayment').value;
  const shippingMethod = document.getElementById('coShipping');
  const shippingText = shippingMethod.options[shippingMethod.selectedIndex].text;
  const shippingCost = parseInt(shippingMethod.value)||0;
  const alertEl = document.getElementById('coAlert');
  if (!name||!addr||!phone) { alertEl.innerHTML='<div class="alert alert-error">Lengkapi semua data pengiriman</div>'; return; }
  const cart = getCart();
  const products = getProducts();
  const subtotal = cart.reduce((s,i)=>{const p=products.find(x=>x.id===i.productId);return s+(p?p.price*i.qty:0);},0);
  const total = subtotal+shippingCost;
  const orderId = 'TK'+Date.now().toString().slice(-8);
  const order = {
    id: orderId, userId: currentUser.id, userName: currentUser.name,
    items: cart.map(i=>{const p=products.find(x=>x.id===i.productId);return{productId:i.productId,name:p?p.name:'?',emoji:p?p.emoji:'📦',price:p?p.price:0,qty:i.qty};}),
    shippingName:name, shippingAddr:addr, shippingPhone:phone,
    payment, shipping:shippingText, shippingCost, subtotal, total,
    status:'pending', createdAt:new Date().toISOString()
  };
  // Save order
  const orders = getOrders(); orders.push(order); save(STORAGE_KEYS.orders, orders);
  // Reduce stock
  const prods = getProducts();
  cart.forEach(ci=>{const idx=prods.findIndex(p=>p.id===ci.productId);if(idx>=0)prods[idx].stock-=ci.qty;});
  save(STORAGE_KEYS.products, prods);
  // Clear cart
  save(STORAGE_KEYS.cart, []);
  closeCheckout();
  alertEl.innerHTML='';
  // Show success
  document.getElementById('successOrderId').textContent='#'+orderId;
  document.getElementById('successDetail').innerHTML=`
    <div style="margin-bottom:0.5rem;"><strong>Penerima:</strong> ${name}</div>
    <div style="margin-bottom:0.5rem;"><strong>Alamat:</strong> ${addr}</div>
    <div style="margin-bottom:0.5rem;"><strong>Pembayaran:</strong> ${payment}</div>
    <div style="margin-bottom:0.5rem;"><strong>Pengiriman:</strong> ${shippingText}</div>
    <div><strong>Total:</strong> <span style="color:var(--accent);font-weight:700;">${formatRp(total)}</span></div>
  `;
  document.getElementById('successModal').classList.remove('hidden');
  renderApp();
}

function closeSuccess() { document.getElementById('successModal').classList.add('hidden'); }

// ===== ORDERS =====
function renderOrders() {
  const orders = getOrders().filter(o=>o.userId===currentUser.id).sort((a,b)=>new Date(b.createdAt)-new Date(a.createdAt));
  const el = document.getElementById('ordersContent');
  if (orders.length===0) {
    el.innerHTML=`<div class="empty-state"><div class="icon">📦</div><h3>Belum Ada Pesanan</h3><p>Yuk mulai belanja!</p><button class="btn btn-primary" onclick="showPage('shop')">Belanja Sekarang</button></div>`;
    return;
  }
  el.innerHTML = orders.map(o=>`
    <div class="order-card">
      <div class="order-header">
        <div>
          <div style="font-weight:600;font-size:1rem;">Pesanan #${o.id}</div>
          <div class="order-id">${new Date(o.createdAt).toLocaleString('id-ID')}</div>
        </div>
        <span class="status-badge status-${o.status}">${statusLabel(o.status)}</span>
      </div>
      <div style="display:flex;gap:0.5rem;flex-wrap:wrap;margin-bottom:0.75rem;">
        ${o.items.map(i=>`<div style="display:flex;align-items:center;gap:6px;background:var(--bg);border-radius:8px;padding:0.375rem 0.75rem;font-size:0.85rem;">${i.emoji} ${i.name} ×${i.qty}</div>`).join('')}
      </div>
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:0.5rem;">
        <div style="font-size:0.85rem;color:var(--text2);">${o.shipping} • ${o.payment}</div>
        <div style="font-weight:700;color:var(--accent);">${formatRp(o.total)}</div>
      </div>
    </div>`).join('');
}

// ===== PROFILE =====
function renderProfile() {
  const u = currentUser;
  const orders = getOrders().filter(o=>o.userId===u.id);
  const totalSpent = orders.reduce((s,o)=>s+o.total,0);
  document.getElementById('profileContent').innerHTML = `
    <div class="profile-card">
      <div class="profile-avatar">${u.name.charAt(0).toUpperCase()}</div>
      <div class="profile-name">${u.name}</div>
      <div style="color:var(--text2);font-size:0.875rem;margin-bottom:0.75rem;">📧 ${u.email}</div>
      <span class="profile-role ${u.role==='admin'?'admin':''}">${u.role==='admin'?'👑 Admin':'🛍️ Member'}</span>
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin:1.5rem 0;">
        <div class="stat-card">
          <div class="stat-label">Total Pesanan</div>
          <div class="stat-value">${orders.length}</div>
        </div>
        <div class="stat-card">
          <div class="stat-label">Total Belanja</div>
          <div class="stat-value" style="font-size:1.25rem;">${formatRp(totalSpent)}</div>
        </div>
      </div>
      <div style="border-top:1px solid var(--border);padding-top:1.5rem;">
        <h3 style="margin-bottom:1rem;font-size:1rem;">Ubah Password</h3>
        <div class="form-group">
          <label>Password Lama</label>
          <input type="password" id="oldPass" placeholder="••••••••">
        </div>
        <div class="form-group">
          <label>Password Baru</label>
          <input type="password" id="newPass" placeholder="Min. 6 karakter">
        </div>
        <div id="passAlert"></div>
        <button class="btn btn-primary" onclick="changePassword()">Simpan Password</button>
      </div>
    </div>`;
}

function changePassword() {
  const old = document.getElementById('oldPass').value;
  const nw = document.getElementById('newPass').value;
  const alertEl = document.getElementById('passAlert');
  if (old !== currentUser.password) { alertEl.innerHTML='<div class="alert alert-error">Password lama salah</div>'; return; }
  if (nw.length<6) { alertEl.innerHTML='<div class="alert alert-error">Password baru minimal 6 karakter</div>'; return; }
  const users = getUsers();
  const idx = users.findIndex(u=>u.id===currentUser.id);
  users[idx].password = nw;
  save(STORAGE_KEYS.users, users);
  currentUser.password = nw;
  saveSession(currentUser);
  alertEl.innerHTML='<div class="alert alert-success">✅ Password berhasil diubah</div>';
  document.getElementById('oldPass').value='';
  document.getElementById('newPass').value='';
}

// ===== ADMIN =====
function switchAdminTab(tab) {
  currentAdminTab = tab;
  document.querySelectorAll('.tab-btn').forEach((b,i)=>{
    b.classList.toggle('active', ['dashboard','products','orders','users'][i]===tab);
  });
  renderAdmin();
}

function renderAdmin() {
  const el = document.getElementById('adminContent');
  if (currentAdminTab==='dashboard') renderAdminDashboard(el);
  else if (currentAdminTab==='products') renderAdminProducts(el);
  else if (currentAdminTab==='orders') renderAdminOrders(el);
  else if (currentAdminTab==='users') renderAdminUsers(el);
}

function renderAdminDashboard(el) {
  const products=getProducts(), orders=getOrders(), users=getUsers();
  const totalRevenue=orders.filter(o=>o.status!=='cancelled').reduce((s,o)=>s+o.total,0);
  const pendingOrders=orders.filter(o=>o.status==='pending').length;
  el.innerHTML=`
    <div class="admin-grid">
      <div class="stat-card"><div class="stat-icon">📦</div><div class="stat-label">Total Produk</div><div class="stat-value">${products.length}</div></div>
      <div class="stat-card"><div class="stat-icon">🛍️</div><div class="stat-label">Total Pesanan</div><div class="stat-value">${orders.length}</div></div>
      <div class="stat-card"><div class="stat-icon">👥</div><div class="stat-label">Total User</div><div class="stat-value">${users.length}</div></div>
      <div class="stat-card"><div class="stat-icon">💰</div><div class="stat-label">Total Pendapatan</div><div class="stat-value" style="font-size:1.2rem;">${formatRp(totalRevenue)}</div></div>
    </div>
    <div style="background:white;border-radius:14px;padding:1.25rem;border:1px solid var(--border);margin-bottom:1.5rem;">
      <h3 style="margin-bottom:1rem;font-size:1rem;">Pesanan Pending (${pendingOrders})</h3>
      ${orders.filter(o=>o.status==='pending').slice(0,5).map(o=>`
        <div style="display:flex;justify-content:space-between;align-items:center;padding:0.75rem 0;border-bottom:1px solid var(--border);">
          <div>
            <div style="font-weight:600;font-size:0.9rem;">#${o.id} — ${o.userName}</div>
            <div style="font-size:0.8rem;color:var(--text2);">${new Date(o.createdAt).toLocaleDateString('id-ID')}</div>
          </div>
          <div style="display:flex;align-items:center;gap:0.75rem;">
            <span style="font-weight:700;color:var(--accent);">${formatRp(o.total)}</span>
            <button class="btn btn-success btn-sm" onclick="updateOrderStatus('${o.id}','processing');renderAdmin()">Proses</button>
          </div>
        </div>`).join('')||'<p style="color:var(--text2);text-align:center;padding:1rem;">Tidak ada pesanan pending</p>'}
    </div>
    <div style="background:white;border-radius:14px;padding:1.25rem;border:1px solid var(--border);">
      <h3 style="margin-bottom:1rem;font-size:1rem;">Stok Menipis</h3>
      ${products.filter(p=>p.stock<=10).map(p=>`
        <div style="display:flex;justify-content:space-between;align-items:center;padding:0.75rem 0;border-bottom:1px solid var(--border);">
          <div style="display:flex;align-items:center;gap:0.75rem;">
            <span style="font-size:1.5rem;">${p.emoji||'📦'}</span>
            <div>
              <div style="font-weight:600;font-size:0.9rem;">${p.name}</div>
              <div style="font-size:0.8rem;color:var(--text2);">${p.category}</div>
            </div>
          </div>
          <span style="font-weight:700;color:${p.stock===0?'var(--danger)':'#d97706'};">Stok: ${p.stock}</span>
        </div>`).join('')||'<p style="color:var(--success);text-align:center;padding:1rem;">✅ Semua stok aman</p>'}
    </div>`;
}

function renderAdminProducts(el) {
  const products = getProducts();
  el.innerHTML=`
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1rem;flex-wrap:wrap;gap:0.75rem;">
      <div style="font-size:0.9rem;color:var(--text2);">${products.length} produk terdaftar</div>
      <button class="btn btn-primary" onclick="openAddProduct()">+ Tambah Produk</button>
    </div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>Produk</th><th>Kategori</th><th>Harga</th><th>Stok</th><th>Aksi</th></tr></thead>
        <tbody>${products.map(p=>`
          <tr>
            <td style="display:flex;align-items:center;gap:0.75rem;">
              ${p.image?`<img src="${p.image}" style="width:40px;height:40px;border-radius:8px;object-fit:cover;border:1px solid var(--border);">`:`<span style="font-size:1.5rem;min-width:40px;text-align:center;">${p.emoji||'📦'}</span>`}
              <strong>${p.name}</strong>
            </td>
            <td><span style="background:var(--surface2);padding:0.2rem 0.6rem;border-radius:999px;font-size:0.78rem;font-weight:600;">${p.category}</span></td>
            <td style="font-weight:700;color:var(--accent);">${formatRp(p.price)}</td>
            <td><span style="font-weight:600;color:${p.stock===0?'var(--danger)':p.stock<=10?'#d97706':'var(--success)'};">${p.stock}</span></td>
            <td>
              <div style="display:flex;gap:0.5rem;">
                <button class="btn btn-outline btn-sm" onclick="openEditProduct('${p.id}')">✏️ Edit</button>
                <button class="btn btn-danger btn-sm" onclick="deleteProduct('${p.id}')">🗑</button>
              </div>
            </td>
          </tr>`).join('')}
        </tbody>
      </table>
    </div>`;
}

function renderAdminOrders(el) {
  const orders = getOrders().sort((a,b)=>new Date(b.createdAt)-new Date(a.createdAt));
  el.innerHTML=`
    <div class="table-wrap">
      <table>
        <thead><tr><th>ID</th><th>Pembeli</th><th>Total</th><th>Status</th><th>Tanggal</th><th>Ubah Status</th></tr></thead>
        <tbody>${orders.map(o=>`
          <tr>
            <td style="font-family:monospace;font-size:0.8rem;">#${o.id}</td>
            <td><strong>${o.userName||'-'}</strong><br><span style="font-size:0.78rem;color:var(--text2);">${o.shippingName}</span></td>
            <td style="font-weight:700;color:var(--accent);">${formatRp(o.total)}</td>
            <td><span class="status-badge status-${o.status}">${statusLabel(o.status)}</span></td>
            <td style="font-size:0.8rem;">${new Date(o.createdAt).toLocaleDateString('id-ID')}</td>
            <td>
              <select class="form-group" style="padding:0.3rem 0.5rem;font-size:0.8rem;border:1px solid var(--border);border-radius:6px;" onchange="updateOrderStatus('${o.id}',this.value);renderAdmin()">
                ${['pending','processing','shipped','delivered','cancelled'].map(s=>`<option ${o.status===s?'selected':''} value="${s}">${statusLabel(s)}</option>`).join('')}
              </select>
            </td>
          </tr>`).join('')||'<tr><td colspan="6" style="text-align:center;color:var(--text2);padding:2rem;">Belum ada pesanan</td></tr>'}
        </tbody>
      </table>
    </div>`;
}

function renderAdminUsers(el) {
  const users = getUsers();
  el.innerHTML=`
    <div class="table-wrap">
      <table>
        <thead><tr><th>Nama</th><th>Email</th><th>Role</th><th>Bergabung</th><th>Pesanan</th></tr></thead>
        <tbody>${users.map(u=>{
          const orders = getOrders().filter(o=>o.userId===u.id).length;
          return `<tr>
            <td><strong>${u.name}</strong></td>
            <td>${u.email}</td>
            <td><span class="status-badge ${u.role==='admin'?'status-processing':'status-delivered'}">${u.role==='admin'?'👑 Admin':'🛍️ User'}</span></td>
            <td style="font-size:0.8rem;">${new Date(u.createdAt).toLocaleDateString('id-ID')}</td>
            <td style="text-align:center;">${orders}</td>
          </tr>`;
        }).join('')}
        </tbody>
      </table>
    </div>`;
}

function updateOrderStatus(orderId, status) {
  const orders = getOrders();
  const idx = orders.findIndex(o=>o.id===orderId);
  if (idx>=0) { orders[idx].status=status; save(STORAGE_KEYS.orders, orders); showToast('Status pesanan diperbarui','success'); }
}

// ===== PRODUCT CRUD =====
function openAddProduct() {
  editingProductId = null;
  document.getElementById('modalTitle').textContent = 'Tambah Produk';
  document.getElementById('pEmoji').value='';
  document.getElementById('pName').value='';
  document.getElementById('pCategory').value='';
  document.getElementById('pPrice').value='';
  document.getElementById('pStock').value='';
  document.getElementById('pDesc').value='';
  document.getElementById('modalAlert').innerHTML='';
  clearImagePreview();
  document.querySelector('#productModal .btn-primary[onclick="saveProduct()"]').style.display='inline-flex';
  document.querySelector('#productModal .btn-secondary').textContent='Batal';
  document.getElementById('productModal').classList.remove('hidden');
}

function openEditProduct(id) {
  const p = getProducts().find(x=>x.id===id);
  if (!p) return;
  editingProductId = id;
  document.getElementById('modalTitle').textContent = 'Edit Produk';
  document.getElementById('pEmoji').value=p.emoji||'';
  document.getElementById('pName').value=p.name;
  document.getElementById('pCategory').value=p.category;
  document.getElementById('pPrice').value=p.price;
  document.getElementById('pStock').value=p.stock;
  document.getElementById('pDesc').value=p.desc||'';
  document.getElementById('modalAlert').innerHTML='';
  // Load existing image if any
  if (p.image) {
    document.getElementById('pImgData').value = p.image;
    document.getElementById('imgPreview').src = p.image;
    document.getElementById('imgPreviewWrap').style.display='block';
    document.getElementById('imgPlaceholder').style.display='none';
  } else {
    clearImagePreview();
  }
  document.querySelector('#productModal .btn-primary[onclick="saveProduct()"]').style.display='inline-flex';
  document.querySelector('#productModal .btn-secondary').textContent='Batal';
  document.getElementById('productModal').classList.remove('hidden');
}

function saveProduct() {
  const emoji=document.getElementById('pEmoji').value.trim();
  const name=document.getElementById('pName').value.trim();
  const cat=document.getElementById('pCategory').value;
  const price=parseInt(document.getElementById('pPrice').value)||0;
  const stock=parseInt(document.getElementById('pStock').value)||0;
  const desc=document.getElementById('pDesc').value.trim();
  const image=document.getElementById('pImgData').value||'';
  if (!name||!cat||price<=0) {
    document.getElementById('modalAlert').innerHTML='<div class="alert alert-error">Nama, kategori, dan harga wajib diisi</div>';
    return;
  }
  const products = getProducts();
  if (editingProductId) {
    const idx=products.findIndex(p=>p.id===editingProductId);
    if (idx>=0) { products[idx]={...products[idx],emoji,name,category:cat,price,stock,desc,image}; }
    showToast('✅ Produk berhasil diperbarui','success');
  } else {
    products.push({id:'p'+Date.now(),emoji,name,category:cat,price,stock,desc,image,createdAt:new Date().toISOString()});
    showToast('✅ Produk berhasil ditambahkan','success');
  }
  save(STORAGE_KEYS.products, products);
  closeModal();
  if (currentPage==='admin') renderAdmin();
  if (currentPage==='shop') renderShop();
}

function deleteProduct(id) {
  if (!confirm('Hapus produk ini?')) return;
  const products = getProducts().filter(p=>p.id!==id);
  save(STORAGE_KEYS.products, products);
  showToast('Produk dihapus');
  renderAdmin();
}

function closeModal() {
  document.getElementById('productModal').classList.add('hidden');
  editingProductId=null;
}

// ===== IMAGE UPLOAD =====
function handleImageUpload(event) {
  const file = event.target.files[0];
  if (!file) return;
  if (file.size > 2*1024*1024) { showToast('Ukuran foto maksimal 2MB!','error'); return; }
  if (!file.type.startsWith('image/')) { showToast('File harus berupa gambar!','error'); return; }
  const reader = new FileReader();
  reader.onload = function(e) {
    const dataUrl = e.target.result;
    document.getElementById('pImgData').value = dataUrl;
    document.getElementById('imgPreview').src = dataUrl;
    document.getElementById('imgPreviewWrap').style.display = 'block';
    document.getElementById('imgPlaceholder').style.display = 'none';
    document.getElementById('imgUploadArea').style.borderColor = 'var(--success)';
  };
  reader.readAsDataURL(file);
}
function clearImagePreview() {
  document.getElementById('pImgData').value = '';
  document.getElementById('pImgInput').value = '';
  document.getElementById('imgPreview').src = '';
  document.getElementById('imgPreviewWrap').style.display = 'none';
  document.getElementById('imgPlaceholder').style.display = 'block';
  document.getElementById('imgUploadArea').style.borderColor = '';
}
function clearImage(e) {
  e.stopPropagation();
  clearImagePreview();
}

// ===== HELPERS =====
function formatRp(n) { return 'Rp '+n.toLocaleString('id-ID'); }
function statusLabel(s) { return {pending:'⏳ Pending',processing:'🔄 Diproses',shipped:'🚚 Dikirim',delivered:'✅ Diterima',cancelled:'❌ Dibatal'}[s]||s; }
function showToast(msg, type='') {
  const t=document.getElementById('toast');
  t.textContent=msg;
  t.className='toast'+(type?' '+type:'');
  t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'),3000);
}

// ===== INIT =====
initData();
if (checkSession()) {
  renderApp();
  showPage(currentUser.role==='admin'?'admin':'shop');
} else {
  showPage('login');
}
</script>

<script>
// ===== PWA MANIFEST (inline) =====
(function() {
  const manifest = {
    name: "TokoKu — Belanja Online",
    short_name: "TokoKu",
    description: "Aplikasi belanja online lengkap dengan fitur admin dan pelanggan",
    start_url: "./",
    display: "standalone",
    background_color: "#1a1a2e",
    theme_color: "#1a1a2e",
    orientation: "portrait-primary",
    icons: [{"src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEgAAABICAIAAADajyQQAAAB5UlEQVR4nO2aPUsEMRBAs4egclhqcX/hQPB+gb3YWNpoaSfYa2trI9jZCNaKIAgWljYeFnYiiJUHp4jgcXKKRZrFZbOTzGSTmc0r75bMvJ187GaTdTqLSiKt0An4IolxI4lxI4lxY8pr6/1uz/Dv0sOdv9AZ+QJtlimDXJJSzE0pD6EejRheKQ+JHlaMVikPUg81K/qzwjfuWDGvSv9wK51Lxeq0cg5nLVazlXNQO7EgVm6hLcQCWjkkIPZZESoWvFwaeBogsUisNMBkxHbF6gUacofmtjdmV5ZpMlLq8/BkdHZtvqZy1RZbsYoXTavRNXl6edvaK/6+cHUMvHL+/CibmYbE6nd75qKJrZhJLKrJsIg5PbEVo9nM+Tq9GF3eqPE3sp33nX3Vyn5fh/iUaMR+BkM1IMhm8viMb0RT2hUjH2AaQ5Jix1gS40YS40YS40YS40apmNevclQYkmxexbjTSLHIh1lD9zxo9hWLtNdX25trkCs/dg/Gt/e27Td3XxH0qTa2t2nI4BdbMZBYVNMjMBloxSJxg6fR7K6oCV40qwTsKhbQzTa0dVcM4uYQ1GWM1ezmFg51+s33wo25g6hZ0WvpkI2ng5gABB6dzSPwsHMRUcfTIyE9K3IjiXEjiXFDrNgfgLaVSisNVDUAAAAASUVORK5CYII=", "sizes": "72x72", "type": "image/png", "purpose": "any maskable"}, {"src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgCAIAAABt+uBvAAACt0lEQVR4nO2cvUscQRjG98TErxArm/sXDiJaxNIu5B84rC0sLASRdJZCsLawDtZiCKRIIaROkyNHLI4UKYVL4BDNiSweFgvh8LJ5Zt55Z3ZmeX7t3d4887v3nd29j2k0my8yUs5U1QFih4IAFASgIAAFASgIQEEACgJQEICCANPVDt9prcLnrFx8DZCkjEb4ezETKWWElxVOkIuXSYKZ8i5I18skvk15FORbzTj+NPk6i4W043U4/QoKrOYR6qWkXEHV2vERQFNQ5XYKdGPotFgkah6h0m4KFRSnnUwpmKugaO0UuMdzEhS5nQLHkLybB8gFJVE+BS5RhYISslMgDiwRlJydAllsrkEAa0GJlk+BILzdlbTVAPPt18+2NmwDCRjsvc2//zB/vtUVNlsMYCEo6eYax2oiIb7VyLu9wZvDskef72/Prr/850PXRye3Hz+XHbj0/rixMKeQ77+wxQCmgmrTXwXm02EFASgIYLRIy/or7/0cnn7Ksuz+si84HDL8cN54+iTLstGvgeDwTmvV5ILI41ks7/bybs/f6/95d+bvxf/CFgNQEAALqtkJfhyTqbGCABQEoCAABQEoCEBBAAoCUBCAggAUBKAgABZU7T8BvGIyNVYQgIIAFAQwElTLZchwUqwgAAUBTAXVrMvMp2Px+yCtD6dn1pYXD3YFB/5u74yublQymAtiiwEsBNWmy6wmUsG/nu++fOu/2gw/rgy7FqtBEdlOwXoNStqRIDwXaYBEUKJFJIstrKDkHIkDy1ssIUcuUbkGAZwEJVFEjiFdKyhyR+7xFFosWkcqwTS3pojnt2iK75nmIh1JKenGUD6LVe5IPYCv/YPCt5un98bXdVDgUvI3HLfoAnCTNwC3CQRUIGgcbjSZPLybB1AQgIIAFASgIAAFASgIQEEACgJQEOABGrG+LG/UJ6cAAAAASUVORK5CYII=", "sizes": "96x96", "type": "image/png", "purpose": "any maskable"}, {"src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIAAAACACAIAAABMXPacAAADeklEQVR4nO2dPWsUURSGJ34ELISIoJA2jRJUDPgDbGz0B9goWNiKiGBja2VlbWEttinEJv/AVP4BCyWfEBBTxI0WF9ZlEnZ37pxznzMz71OG3Z1z3mfOvZmdZHdheflmJTjO0AUMHQmAkQAYCYCRABgJgJEAGAmAkQAYCYCRABgJgJEAGAmAOUcX0IDN1bU5H3n721fXSgxZiHw/YP7EpxPZR0QBVrmfJKCJQAL8cj9JHBMhBJSMfpIIGmABVPSTsBowARGin4TSAAiIFv0k5TWUvhCLnH5FlFduAoJHX6PYKBSagG6lXxUsuISAzqWfKFO2u4COpp8oULzjHtDp6Gv4bQleE9Cn9CvPdlwE9Cz9hFNTuiEDYy+gl6d/wqM1YwE9Tj9h3qClgN6nn7Bt00zAQNJPGDarTRjGRsCgTv+EVcsGAgaYfsKkcS1BMG3fC8o+Cxbv3Fh686LNoa34e/Rn5/7T7Ke3fJtIEwDTSsBgV/9JWoagCYDJ/+Nc29N/+96TmY85f33l0rvX0x8z2trbe/Ry5kst3rq29PbVvMXNYnN1LXsn0ATAZArQ6l8jOxBNAIwEwOQI0PpzKnmxaAJgsP8RG33/+ev9R+zoP7b/H310TJVRZQiwWn9GW7u/P302eamco+/sexw944JASxCMBMBIAIwEwDQToCuAmTSNSBMAIwEwEgAjATASACMBMBIAIwEwEgAjATASACMBMBIA00xAhA9ZC45uSXYMCYCRABgJgGksQPvwFDLC0QTASABMjgCtQqeSF4smAEYCYDIFaBWqkR1I3O+QufDg7sVnj5s+6+zVy1e+fKj9cPfh8+P9A6O6jMlfgjQEY9pEoT0AppUADUHVOoS4e8Dh+sbh+gZdhTttl6CBD0H79rUHwBgIGOwQmDRuMwEDdGDVspYgGDMBgxoCw2YtJ2AgDmzbNF6Ceu/AvEH7PaDHDjxa0yYM4yKgl0Pg1JTXBPTMgV877t8l2fVPN/A+k9z3gE6PQoHiS2zCHXVQpuxCvwV1zkGxgkt/o3b8LaHwuVL6OiD4KJQvD/hO+US0UaDODExAIoIGdihhAQlKQ4T1MISAREkNEaJPBBIwxs9EnNzHRBQwxspEwNzHhBZQY34fkROv0SUBvUQ3ZGAkAEYCYCQARgJgJABGAmAkAEYCYCQARgJgJABGAmAkAOYfptXqGpQbJGUAAAAASUVORK5CYII=", "sizes": "128x128", "type": "image/png", "purpose": "any maskable"}, {"src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJAAAACQCAIAAABoJHXvAAADxUlEQVR4nO3dv2pUQRyG4dkQjJWgqEUKG8uAYC7Ju7C0FgRttAgI6bQUCzGFIKQ1lVegRUC0SCJJk2gxcFh2wzI78/v3zXxvpbAsZ+bZmXN21z3OtrcfJYbThvcBsPUiGFgEA4tgYBEMLIKBRTCwCAYWwcAiGFgEA4tgYBEMLIKBRTCwCAbWpvcBCHS0s1v4yMffv6keiUEzuG+cy3lKgiOEAZN1Wg5FLjqYttNyweWCgtk7LRdTLhxYBKr5orEFAotGNV8cthBgkanmi8Dm/8YZRSvFOFTPFRZh/HU5LjW3FYarlVwP3gcMWivnNQTrLbEDqoWMt0fTFdafVjIflB1Yl1o5y6EZgXWslTMboAVY91o5m2Gqgw2ilTMYrC7YUFo57SErgg2olVMduBbYsFo5veH7f/jL1koFbPDllVOaBHkwak1pTIUwGLUWEp8QnsPAkgTj8ro22WkRA6PWigQnh1siWDJfYLa/gjYfPrjz+ln7kWh0+fP495On7c8j8lUnVxhYAmA8exUmMlFcYWC1/qBPaXldHByePN8rfPD9z29LHnb+6evpi6JHppTuvnu5cftW4YPLO9rZbTyTcYWBRTCwmsB4uVFR46RxhYFFMLDqwbgfVtcydVxhYEW5scrVrz+nr/anv17+OHY8mJTS2d772daN/Od/p399D2a+SjDx/fDq5Oz84xfZ52zp4uBQ9fmr30FzSwSLYGARDCyCgUUwsGrA+JZZpLpp5AoDi2BgEQwsgoFFMLAIBhbBwCIYWAQDi2BgEQwsgoFFMLBqwCLcDbyD+G86hohgYBEMLIKBRTCwKsF4odhY9QRyhYFFMLDqwbgrVtcydVxhYBEMrCYw7ooV8cYqY0UwsATul2j524h7H97Mbm4JPuFaN6Bqr/0kwhUGlgAYLz0K4x1JR0zsPy3lr/xWJ7UPcYWBJQbGM9mKBCdHcoXR7Npkp4VbIljCYFxkC4lPiPwKo9mUxlSobIk0S2qTwHMYWFpggy8yveErrrBhzVQHrrslDmimPWT1c9hQZgaDtbjoGMTMZphGV4ndm5kN0O6yvmMzy6GZvg/r0sx4UGJfYK5VH992urz+fD7p6GCpeQ3B7aMpaDPHg/fZEufD2h7dX2f+H/66T0F5EQ7Vf4VNRV5qEahygcBy0djiUOXCgeUisEWjygUFm7KXi+k0FR1sSlsuuNMUDNiUrByK0xQe2HLlhHA8y/UANlT+b5zZWhEMLIKBRTCwCAYWwcAiGFgEA4tgYBEMLIKBRTCwCAYWwcAiGFgEA+s/urr8mwyC0hkAAAAASUVORK5CYII=", "sizes": "144x144", "type": "image/png", "purpose": "any maskable"}, {"src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJgAAACYCAIAAACXoLd2AAAD8ElEQVR4nO3dv04VQRTH8QW1oiISC3orjYk+ha08AYmdha2JrZUNz0BFSeN7aEViYmJJgTFWxIJcsJhkXReEvTtn5pz57fdTGXNzs3O+zNw/uXA3dnefdWjfpvcFwAYhRRBSBCFFEFIEIUUQUgQhRRBSBCFFEFIEIUUQUgQhRRBSBCFFEFLEfe8LsPTlyYu1bv/85HOhK6lvo+mPeqxb7nZNd20vpG28/2kuajMh6/S7rpWiDYT0SjgUP2fckBH6XRe2aMSQMRMOBcwZ7nVk/IpdyIsMtCMDTudOcbZmiJAtJhyKkNP/aG29YhdjCc4hI4zAhPtC3I5W95UX4nXM+uxI1Yqd39IcQgpXTFwWWDukfMWk/jKrhlxIxaTyYuuFXFTFpOaSK4VcYMWk2sJrhFxsxaTO8ouHXHjFpMIQyoakYq/0KAqGpOJI0YH4v2kOE6VCsh1vVG4sRUJS8RaFhmMfkop3KjEiHiNFGIdkO05kPih2pAjLTwiY/JTd23308PBj/v0UdfH1+6+3H/Lvx/DjBGY7kkN1BsOhcbSKsAnJdpzNanTRf2P56vz3j1dvpt9+5+hgc2d7yi3PD4/Pjz5NvNsHTx9vH7yffhn1cbSKMAjJuZrJZIDsSBG5IdmOJvLHyI4UQUgRWSE5Vw1lDjPk68jLy/6fV6uV44X8dfXPVXVBrmogXMjV6dnZy9feVzF2cfIt4FUN8RgpYn5IHiDN5YyUHSmCkCIIKYKQImaG5JlOIbMHy44UQUgRhBRBSBGEFEFIEYQUQUgRhBRBSBGEFEFIEYQUQUgRhBQxM2SEryyRNHuw7EgRhBRBSBGEFDE/JM93zOWMlB0pgpAiCCkiKyQPk4Yyh8mOFEFIEbkhOV1N5I+RHSnCICSbMpPJAMP9VY+J8v/u5tb+3tb+3ug/V6dnP/ff5dytF45WETYhOV1nsxodO1JEuK+LWJSIXxfRccCuyXZcHK0ijEOyKScyHxQ7UoR9SDblnUqMqMiOpOUtCg2n1NFKyxuVGwuPkSIKhmRTjhQdSNkdScte6VEUP1pp2VUZQo3HyIW3rLP8Sk92Ftuy2sLrPWtdYMuaS6768mNRLSsvtvbryIW0rL9MhzcE5Fu6LNDnnR3hll5Ls/yoxwxKnw7x/el0fq9VZmu6L8T/TXP3EeSLsATno3WoxWM2QsIkUMiklZxxEib+R+tItAHdKOBFhtuRvZhbM2DCJG7IXoSiYfv1GgiZeOWMnzBpJmSvTtFW+vXaCzlkG7W5eENthxxZt2vT5UakQi5ZuNeRmIeQIggpgpAiCCmCkCIIKYKQIggpgpAiCCmCkCIIKYKQIggpgpAiCCniD/tHBKaQZZo6AAAAAElFTkSuQmCC", "sizes": "152x152", "type": "image/png", "purpose": "any maskable"}, {"src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAIAAADdvvtQAAAFFklEQVR4nO3dMYsdZRTG8bmbgAiaFBGFBRtbIRBJq7Ufw3SKXZqkUb+AnaWFxVZBC9MFP0Ss0toIFoLbmBUJ0bUYGAZvArn3ec97nvPO/1cm2ezc8/5zZi67SXanpzcn4Fgn2ReA2ggIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICJKr2Rfg4uf3Pzjo19968jjoSmrZbfDvhR3ayqvbYFVbCSgumpfZSEyDB9S/m31jlzRmQA7d7BuypKEC8uxm30glDRJQlXTWxsiofEAV01mrnlHhgKqns1Y3o5IBjZTOWsWMigU0ajprtTKq9LWwLdQzVXuZNTZQrZm2UmIVFdhA26xnKvLC3QMqMcQ4/i/f9xbmP7uebG9nphuIev7HdiCOAdkOK5fnWOwC8hyTCcPheAVkOCA3biNyeYh2m4s/k8dqiw1EPUcwGVp+QCaDqMhhdPkBobTkgBz+DJWWPsDMgNJf/Bhyx5gWEPU0lDjMnICop7mskSYERD1BUgbLuzBIegfE+gnVf7xdA6KeDjoPuV9A1NNNz1HzDARJp4BYP511G3iPgKgnRZ+xcwuDJDwg1k+iDsMv/K+0vvXDNyfX3si+imaefvvgr+8fZV/FwWI3EOsnXfQR8AwESWBArB8ToQfBBoIkKiDWj5W44yj8LmzfxdnDi7Mfj/jA1z68ff2Lzw/9qOe//Hr+6ZdHfLppmm6cfX3lnRvHfayVkA3E+jEUdCg8A0FCQJC0D4j7l62Io2EDQUJAkDQOiPuXueYHxAaChIAgaRkQ968S2h5T4S9lnN+5P53s1j9y+fezrIs51PlnX+2uVL34tcIB/fvnRfYlHO/y6cVl9jU0wTMQJM0C4gGokIaHxQaChIAgISBICAgSAoKEgCBpExDv4ctpdWRsIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgqRNQLeePG7y+6CbVkfGBoKEgCAhIEgICBICgoSAIGkWEO/kC2l4WGwgSAgIEgKCpGVAPAaV0PaY2ECQEBAkjQPiLmau+QGxgSAhIEjaB8RdzFbE0bCBICEgSEIC4i5mKOhQCv9vPYd68+6d1z/+qOFvePW9d9/+6buX/ewfn9z757ffG346T1G3MJaQlbjj4BkIksCAWEImQg+CDQRJbEAsoXTRR7A7Pb0Z+gn4XxByRQcUfgtjCSXqMHyegSDpERBLKEWfsXfaQDTUWbeBcwuDpF9ALKFueo666waioQ46D7n3LYyGQvUfL89AkCQExBIKkjLYnA1EQ81ljTTtFkZDDSUOM/MZiIaayB1j8kM0DYnSB8i7MEjyA0r/M1SXw+jyA5o8BlGOydDCvyPxIHz74qswSWdmsYEWVqPx5DYir4AmvwFZMRyOXUCT5ZgceI7FMaDJdViJbAfi9RC9j8dq23RmphtoYT6+aP4v3z2gqcIQg5R44e63sLXt3M5KpDMrsIEWhcaqqPUyK22gxairqFY6s5IBzUbKqGI6s8IBzapnVDedWfmAZhUzqp7ObJCAZlUyGiOd2VABLTxLGqmbxZgBLRxKGrKbxeABLfqXNHY3i60EtBYX00aiWdtiQC90aFUbbOWFCAiSSl8LgyECgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoLkP2tYOJ/Fg3LUAAAAAElFTkSuQmCC", "sizes": "192x192", "type": "image/png", "purpose": "any maskable"}, {"src": "data:image/png;base64,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", "sizes": "384x384", "type": "image/png", "purpose": "any maskable"}, {"src": "data:image/png;base64,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", "sizes": "512x512", "type": "image/png", "purpose": "any maskable"}]
  };
  const blob = new Blob([JSON.stringify(manifest)], {type: 'application/manifest+json'});
  const url = URL.createObjectURL(blob);
  document.getElementById('pwaManifest').setAttribute('href', url);
})();

// ===== SERVICE WORKER =====
if ('serviceWorker' in navigator) {
  const swCode = `
const CACHE = 'tokoku-v1';
const ASSETS = [location.pathname];
self.addEventListener('install', e => {
  e.waitUntil(caches.open(CACHE).then(c => c.addAll(ASSETS)).then(() => self.skipWaiting()));
});
self.addEventListener('activate', e => {
  e.waitUntil(caches.keys().then(keys => Promise.all(keys.filter(k=>k!==CACHE).map(k=>caches.delete(k)))).then(()=>self.clients.claim()));
});
self.addEventListener('fetch', e => {
  if (e.request.method !== 'GET') return;
  e.respondWith(caches.match(e.request).then(cached => cached || fetch(e.request).then(res => {
    const clone = res.clone();
    caches.open(CACHE).then(c => c.put(e.request, clone));
    return res;
  }).catch(() => cached)));
});
  `;
  const blob = new Blob([swCode], {type:'application/javascript'});
  const swUrl = URL.createObjectURL(blob);
  navigator.serviceWorker.register(swUrl).then(reg => {
    console.log('SW registered:', reg.scope);
  }).catch(err => console.log('SW error:', err));
}

// ===== INSTALL PROMPT =====
let deferredPrompt = null;
window.addEventListener('beforeinstallprompt', (e) => {
  e.preventDefault();
  deferredPrompt = e;
  showInstallBanner();
});

function showInstallBanner() {
  if (document.getElementById('installBanner')) return;
  const banner = document.createElement('div');
  banner.id = 'installBanner';
  banner.style.cssText = 'position:fixed;bottom:0;left:0;right:0;background:#1a1a2e;color:white;padding:1rem 1.5rem;display:flex;align-items:center;justify-content:space-between;z-index:999;box-shadow:0 -4px 20px rgba(0,0,0,0.3);gap:1rem;flex-wrap:wrap;';
  banner.innerHTML = `
    <div style="display:flex;align-items:center;gap:0.75rem;">
      <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAIAAADdvvtQAAAFFklEQVR4nO3dMYsdZRTG8bmbgAiaFBGFBRtbIRBJq7Ufw3SKXZqkUb+AnaWFxVZBC9MFP0Ss0toIFoLbmBUJ0bUYGAZvArn3ec97nvPO/1cm2ezc8/5zZi67SXanpzcn4Fgn2ReA2ggIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICJKr2Rfg4uf3Pzjo19968jjoSmrZbfDvhR3ayqvbYFVbCSgumpfZSEyDB9S/m31jlzRmQA7d7BuypKEC8uxm30glDRJQlXTWxsiofEAV01mrnlHhgKqns1Y3o5IBjZTOWsWMigU0ajprtTKq9LWwLdQzVXuZNTZQrZm2UmIVFdhA26xnKvLC3QMqMcQ4/i/f9xbmP7uebG9nphuIev7HdiCOAdkOK5fnWOwC8hyTCcPheAVkOCA3biNyeYh2m4s/k8dqiw1EPUcwGVp+QCaDqMhhdPkBobTkgBz+DJWWPsDMgNJf/Bhyx5gWEPU0lDjMnICop7mskSYERD1BUgbLuzBIegfE+gnVf7xdA6KeDjoPuV9A1NNNz1HzDARJp4BYP511G3iPgKgnRZ+xcwuDJDwg1k+iDsMv/K+0vvXDNyfX3si+imaefvvgr+8fZV/FwWI3EOsnXfQR8AwESWBArB8ToQfBBoIkKiDWj5W44yj8LmzfxdnDi7Mfj/jA1z68ff2Lzw/9qOe//Hr+6ZdHfLppmm6cfX3lnRvHfayVkA3E+jEUdCg8A0FCQJC0D4j7l62Io2EDQUJAkDQOiPuXueYHxAaChIAgaRkQ968S2h5T4S9lnN+5P53s1j9y+fezrIs51PlnX+2uVL34tcIB/fvnRfYlHO/y6cVl9jU0wTMQJM0C4gGokIaHxQaChIAgISBICAgSAoKEgCBpExDv4ctpdWRsIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgqRNQLeePG7y+6CbVkfGBoKEgCAhIEgICBICgoSAIGkWEO/kC2l4WGwgSAgIEgKCpGVAPAaV0PaY2ECQEBAkjQPiLmau+QGxgSAhIEjaB8RdzFbE0bCBICEgSEIC4i5mKOhQCv9vPYd68+6d1z/+qOFvePW9d9/+6buX/ewfn9z757ffG346T1G3MJaQlbjj4BkIksCAWEImQg+CDQRJbEAsoXTRR7A7Pb0Z+gn4XxByRQcUfgtjCSXqMHyegSDpERBLKEWfsXfaQDTUWbeBcwuDpF9ALKFueo666waioQ46D7n3LYyGQvUfL89AkCQExBIKkjLYnA1EQ81ljTTtFkZDDSUOM/MZiIaayB1j8kM0DYnSB8i7MEjyA0r/M1SXw+jyA5o8BlGOydDCvyPxIHz74qswSWdmsYEWVqPx5DYir4AmvwFZMRyOXUCT5ZgceI7FMaDJdViJbAfi9RC9j8dq23RmphtoYT6+aP4v3z2gqcIQg5R44e63sLXt3M5KpDMrsIEWhcaqqPUyK22gxairqFY6s5IBzUbKqGI6s8IBzapnVDedWfmAZhUzqp7ObJCAZlUyGiOd2VABLTxLGqmbxZgBLRxKGrKbxeABLfqXNHY3i60EtBYX00aiWdtiQC90aFUbbOWFCAiSSl8LgyECgoSAICEgSAgIEgKChIAgISBICAgSAoKEgCAhIEgICBICgoSAICEgSAgIEgKChIAgISBICAgSAoLkP2tYOJ/Fg3LUAAAAAElFTkSuQmCC" style="width:40px;height:40px;border-radius:10px;">
      <div>
        <div style="font-weight:700;font-size:0.95rem;">Install Aplikasi TokoKu</div>
        <div style="font-size:0.78rem;opacity:0.75;">Tambahkan ke layar utama HP Anda</div>
      </div>
    </div>
    <div style="display:flex;gap:0.5rem;">
      <button onclick="dismissInstall()" style="background:rgba(255,255,255,0.15);color:white;border:none;padding:0.5rem 1rem;border-radius:8px;cursor:pointer;font-size:0.85rem;">Nanti</button>
      <button onclick="installApp()" style="background:#e94560;color:white;border:none;padding:0.5rem 1.25rem;border-radius:8px;cursor:pointer;font-weight:700;font-size:0.85rem;">📲 Install</button>
    </div>
  `;
  document.body.appendChild(banner);
}

function installApp() {
  if (!deferredPrompt) return;
  deferredPrompt.prompt();
  deferredPrompt.userChoice.then(choice => {
    if (choice.outcome === 'accepted') {
      showToast('✅ TokoKu berhasil diinstall!', 'success');
    }
    deferredPrompt = null;
    const b = document.getElementById('installBanner');
    if (b) b.remove();
  });
}

function dismissInstall() {
  const b = document.getElementById('installBanner');
  if (b) b.remove();
  localStorage.setItem('installDismissed', Date.now());
}

window.addEventListener('appinstalled', () => {
  showToast('🎉 TokoKu berhasil diinstall!', 'success');
  const b = document.getElementById('installBanner');
  if (b) b.remove();
});
</script>

</body>
</html>
