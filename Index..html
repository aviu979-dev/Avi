<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LuxeStyle | AI-Powered Shopping</title>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #d4af37; /* Gold */
            --bg-color: #f4f4f4;
            --text-color: #333;
            --card-bg: #fff;
            --sidebar-bg: #fff;
            --accent: #ff4757;
            --chat-bg: #e5e5e5;
        }

        body.dark-mode {
            --bg-color: #121212;
            --text-color: #e0e0e0;
            --card-bg: #1e1e1e;
            --sidebar-bg: #1a1a1a;
            --primary-color: #ffd700;
            --chat-bg: #2a2a2a;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; transition: background 0.3s, color 0.3s; }
        body { background-color: var(--bg-color); color: var(--text-color); overflow-x: hidden; }

        /* --- NAVIGATION --- */
        nav {
            background: rgba(255, 255, 255, 0.95);
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky; top: 0; z-index: 1000;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            backdrop-filter: blur(10px);
        }
        body.dark-mode nav { background: rgba(30, 30, 30, 0.95); }

        .logo { font-size: 1.8rem; font-weight: 900; color: var(--primary-color); letter-spacing: 2px; text-transform: uppercase; }
        
        .search-bar { position: relative; width: 40%; }
        .search-bar input { width: 100%; padding: 12px 20px; border-radius: 30px; border: 2px solid #ddd; outline: none; background: var(--bg-color); color: var(--text-color); }
        .search-bar input:focus { border-color: var(--primary-color); }

        .nav-icons { display: flex; gap: 20px; align-items: center; font-size: 1.2rem; }
        .nav-icons i { cursor: pointer; transition: transform 0.2s; }
        .nav-icons i:hover { transform: scale(1.2); color: var(--primary-color); }
        
        .badge { position: absolute; top: -8px; right: -8px; background: var(--accent); color: white; font-size: 0.7rem; padding: 3px 6px; border-radius: 50%; font-weight: bold; }

        /* --- MOOD WIDGET --- */
        .mood-widget {
            position: fixed; bottom: 30px; left: 30px; background: var(--card-bg); padding: 10px 15px; 
            border-radius: 50px; box-shadow: 0 10px 30px rgba(0,0,0,0.2); z-index: 900; 
            display: flex; align-items: center; gap: 15px; border: 2px solid var(--primary-color);
        }
        .mood-btn { width: 35px; height: 35px; border-radius: 50%; border: none; cursor: pointer; font-size: 1.2rem; transition: transform 0.2s; }
        .mood-btn:hover { transform: scale(1.2); }

        /* --- STUDIO BUTTON --- */
        .studio-btn-float {
            position: fixed; bottom: 90px; left: 30px; background: linear-gradient(45deg, #ff9ff3, #feca57); 
            padding: 12px 20px; border-radius: 30px; color: white; font-weight: bold; cursor: pointer;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2); z-index: 900; border: none;
            display: flex; align-items: center; gap: 10px; transition: transform 0.3s;
        }
        .studio-btn-float:hover { transform: translateY(-5px); }

        /* --- CART SIDEBAR --- */
        .cart-sidebar {
            position: fixed; top: 0; right: -400px; width: 380px; height: 100%; background: var(--sidebar-bg);
            box-shadow: -5px 0 30px rgba(0,0,0,0.3); z-index: 1500; padding: 25px; display: flex; flex-direction: column; transition: right 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .cart-sidebar.open { right: 0; }
        
        .cart-item { display: flex; align-items: center; gap: 15px; margin-bottom: 20px; background: var(--bg-color); padding: 10px; border-radius: 12px; }
        .cart-item img { width: 60px; height: 60px; border-radius: 8px; object-fit: cover; }
        .cart-details { flex: 1; }
        .cart-details h4 { font-size: 0.9rem; margin-bottom: 4px; }
        .cart-details .price { color: var(--primary-color); font-weight: bold; }
        .remove-icon { color: #ff4757; cursor: pointer; padding: 5px; font-size: 1.1rem; }
        .remove-icon:hover { background: rgba(255, 71, 87, 0.1); border-radius: 50%; }

        /* --- PRODUCTS --- */
        .container { max-width: 1200px; margin: 40px auto; padding: 0 20px; }
        .section-header { margin-bottom: 30px; display: flex; align-items: center; gap: 15px; }
        .section-header h2 { font-size: 2rem; color: var(--primary-color); }
        
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 30px; }
        
        .product-card { 
            background: var(--card-bg); border-radius: 20px; overflow: hidden; position: relative;
            box-shadow: 0 10px 20px rgba(0,0,0,0.05); transition: transform 0.3s, box-shadow 0.3s;
        }
        .product-card:hover { transform: translateY(-10px); box-shadow: 0 15px 30px rgba(0,0,0,0.1); }
        
        .product-img { width: 100%; height: 260px; object-fit: cover; }
        
        .product-info { padding: 20px; text-align: center; }
        .product-title { font-size: 1.1rem; font-weight: 700; margin-bottom: 5px; }
        .rating { color: #f1c40f; font-size: 0.8rem; margin-bottom: 10px; }
        .price { font-size: 1.2rem; font-weight: bold; color: var(--primary-color); }
        
        .btn-group { display: flex; gap: 10px; margin-top: 15px; }
        .btn { flex: 1; padding: 10px; border: none; border-radius: 8px; cursor: pointer; font-weight: 600; font-size: 0.9rem; }
        .btn-cart { background: transparent; border: 2px solid var(--text-color); color: var(--text-color); }
        .btn-cart:hover { background: var(--text-color); color: var(--bg-color); }
        .btn-buy { background: var(--primary-color); color: #fff; }
        .btn-haggle { background: #2ed573; color: white; display:flex; align-items:center; justify-content:center; gap:5px;}
        .btn-haggle:hover { background: #26af61; }

        .wishlist-icon { position: absolute; top: 15px; right: 15px; background: rgba(255,255,255,0.9); padding: 8px; border-radius: 50%; cursor: pointer; color: #ccc; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        .wishlist-icon.active { color: #ff4757; }

        /* --- FOOTER --- */
        footer { background: #111; color: white; padding: 60px 20px 20px; margin-top: 80px; }
        .footer-content { max-width: 1200px; margin: auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 40px; }
        .footer-col h3 { color: var(--primary-color); margin-bottom: 20px; }
        .footer-col p, .footer-col a { color: #888; margin-bottom: 10px; display: block; text-decoration: none; }
        .teen-credit { text-align: center; margin-top: 50px; padding-top: 20px; border-top: 1px solid #333; font-family: monospace; color: var(--primary-color); }

        /* --- MODALS --- */
        .modal { display: none; position: fixed; z-index: 2000; left: 0; top: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.85); justify-content: center; align-items: center; backdrop-filter: blur(5px); }
        .modal-content { background: var(--card-bg); padding: 30px; border-radius: 20px; width: 90%; max-width: 450px; position: relative; text-align: center; box-shadow: 0 0 50px rgba(212, 175, 55, 0.2); }
        .close-btn { position: absolute; top: 15px; right: 20px; font-size: 24px; cursor: pointer; }

        /* --- NEGOTIATOR CHAT --- */
        .chat-box { background: var(--chat-bg); height: 300px; overflow-y: auto; border-radius: 10px; padding: 15px; margin-bottom: 15px; display: flex; flex-direction: column; gap: 10px; border: 1px solid #ccc; }
        .message { max-width: 80%; padding: 10px 15px; border-radius: 15px; font-size: 0.9rem; line-height: 1.4; }
        .bot-msg { align-self: flex-start; background: var(--card-bg); border-bottom-left-radius: 2px; }
        .user-msg { align-self: flex-end; background: var(--primary-color); color: white; border-bottom-right-radius: 2px; }
        .offer-controls { display: flex; gap: 10px; }
        .offer-input { flex: 1; padding: 10px; border-radius: 5px; border: 1px solid #ccc; outline: none; }

        /* --- VIRTUAL STUDIO (Mix & Match) --- */
        .studio-layout { display: flex; height: 500px; gap: 20px; text-align: left; }
        .studio-sidebar { width: 30%; overflow-y: auto; padding-right: 10px; border-right: 1px solid #ddd; }
        .studio-item-thumb { cursor: grab; padding: 10px; margin-bottom: 10px; background: var(--bg-color); border-radius: 8px; display: flex; align-items: center; gap: 10px; }
        .studio-item-thumb:active { cursor: grabbing; }
        .studio-item-thumb img { width: 40px; height: 40px; object-fit: cover; border-radius: 5px; }
        
        .studio-canvas { 
            flex: 1; background: url('https://www.transparenttextures.com/patterns/graphy.png'), #f0f0f0; 
            border-radius: 10px; position: relative; overflow: hidden; border: 2px dashed #ccc; 
        }
        .canvas-obj { position: absolute; width: 100px; cursor: move; filter: drop-shadow(0 5px 5px rgba(0,0,0,0.2)); transition: transform 0.1s; }
        .canvas-obj:hover { border: 1px solid var(--primary-color); }
        .studio-hint { position: absolute; top: 50%; left: 50%; transform: translate(-50%,-50%); color: #999; pointer-events: none; }

        /* --- LIVE HYPE NOTIFICATION --- */
        .hype-notification {
            position: fixed; bottom: 30px; right: -300px; background: var(--card-bg); width: 280px;
            padding: 15px; border-radius: 10px; box-shadow: 0 5px 20px rgba(0,0,0,0.2);
            display: flex; gap: 15px; align-items: center; transition: right 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            z-index: 1000; border-left: 4px solid var(--primary-color);
        }
        .hype-notification.show { right: 30px; }
        .hype-img { width: 50px; height: 50px; border-radius: 5px; object-fit: cover; }

        /* --- SPIN WHEEL --- */
        .wheel-wrapper { position: relative; width: 300px; height: 300px; margin: 20px auto; }
        .wheel { width: 100%; height: 100%; border-radius: 50%; border: 8px solid #fff; box-shadow: 0 0 20px rgba(0,0,0,0.5); background: conic-gradient(#ff6b6b 0deg 45deg, #feca57 45deg 90deg, #1dd1a1 90deg 135deg, #54a0ff 135deg 180deg, #5f27cd 180deg 225deg, #ff9ff3 225deg 270deg, #48dbfb 270deg 315deg, #ff9f43 315deg 360deg); transition: transform 5s cubic-bezier(0.25, 0.1, 0.25, 1); position: relative; overflow: hidden; }
        .wheel-pointer { position: absolute; top: -20px; left: 50%; transform: translateX(-50%); width: 0; height: 0; border-left: 15px solid transparent; border-right: 15px solid transparent; border-top: 30px solid #333; z-index: 10; }
        .spin-btn-center { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 60px; height: 60px; background: white; border-radius: 50%; display: flex; justify-content: center; align-items: center; font-weight: 900; color: #333; cursor: pointer; z-index: 5; box-shadow: 0 0 15px rgba(0,0,0,0.3); border: 4px solid var(--primary-color); }
        .wheel-label { position: absolute; top: 50%; left: 50%; width: 50%; height: 2px; transform-origin: 0 0; text-align: right; padding-right: 25px; font-weight: bold; font-size: 0.85rem; color: #fff; text-shadow: 1px 1px 2px rgba(0,0,0,0.6); pointer-events: none; }
        .win-popup { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%) scale(0); background: white; padding: 20px; border-radius: 15px; box-shadow: 0 0 30px rgba(0,0,0,0.5); z-index: 20; text-align: center; border: 3px solid gold; width: 80%; transition: 0.3s; }
        .win-popup.show { transform: translate(-50%, -50%) scale(1); }

        /* Payment Radio Styles */
        .pay-option { display: flex; align-items: center; gap: 10px; padding: 10px; border: 1px solid #ddd; border-radius: 8px; margin-bottom: 8px; cursor: pointer; transition: 0.2s; }
        .pay-option:hover { border-color: var(--primary-color); }
        .pay-option input { accent-color: var(--primary-color); transform: scale(1.2); }
        
        @media (max-width: 768px) {
            .search-bar { display: none; }
            .studio-layout { flex-direction: column; height: auto; }
            .studio-sidebar { width: 100%; display: flex; gap: 10px; overflow-x: auto; border-right: none; border-bottom: 1px solid #ddd; padding-bottom: 10px; }
            .studio-canvas { height: 300px; }
            .cart-sidebar { width: 100%; }
        }
    </style>
</head>
<body>

    <!-- Nav -->
    <nav>
        <div class="logo">LuxeStyle</div>
        <div class="search-bar">
            <input type="text" id="searchInput" placeholder="Search..." onkeyup="filterProducts()">
        </div>
        <div class="nav-icons">
            <i class="fas fa-moon" onclick="toggleTheme()" title="Toggle Theme"></i>
            <i class="fas fa-dharmachakra" style="color:var(--primary-color); animation: spin 10s linear infinite;" onclick="openModal('spinModal')" title="Spin & Win"></i>
            <div style="position:relative;" title="Wishlist">
                <i class="fas fa-heart"></i><span class="badge" id="wishlistCount">0</span>
            </div>
            <div style="position:relative;" title="Cart" onclick="toggleCart()">
                <i class="fas fa-shopping-cart"></i><span class="badge" id="cartCount">0</span>
            </div>
            <div style="position:relative; display:inline-block;" class="dropdown">
                <i class="fas fa-ellipsis-v" onclick="toggleDropdown()"></i>
                <div id="dropdownMenu" style="display:none; position:absolute; right:0; top:25px; background:var(--card-bg); width:150px; box-shadow:0 5px 15px rgba(0,0,0,0.2); border-radius:8px; overflow:hidden;">
                    <a href="#footer" style="display:block; padding:10px; text-decoration:none; color:var(--text-color); border-bottom:1px solid #eee;">Contact</a>
                    <a href="#" onclick="alert('Support: 9919900000')" style="display:block; padding:10px; text-decoration:none; color:var(--text-color);">Support</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Mood AI & Studio Buttons -->
    <div class="mood-widget">
        <span style="font-size:0.8rem; font-weight:bold; text-transform:uppercase;">Mood AI</span>
        <button class="mood-btn" style="background:#f1c40f" onclick="setMood('happy')" title="Happy">☀️</button>
        <button class="mood-btn" style="background:#2c3e50; color:white" onclick="setMood('pro')" title="Professional">💼</button>
        <button class="mood-btn" style="background:#ff4757; color:white" onclick="setMood('party')" title="Party">🎉</button>
    </div>

    <!-- Virtual Studio Button -->
    <button class="studio-btn-float" onclick="openStudio()">
        <i class="fas fa-tshirt"></i> Virtual Closet
    </button>

    <!-- Cart Sidebar -->
    <div class="cart-sidebar" id="cartSidebar">
        <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:20px; border-bottom:1px solid #ddd; padding-bottom:15px;">
            <h2 style="font-size:1.5rem;">Shopping Cart</h2>
            <span onclick="toggleCart()" style="cursor:pointer; font-size:1.5rem;">&times;</span>
        </div>
        <div id="cartItemsContainer" style="flex:1; overflow-y:auto;">
            <p style="text-align:center; margin-top:30px; color:#999;">Your cart is empty.</p>
        </div>
        <div style="border-top:1px solid #ddd; padding-top:20px; margin-top:10px;">
            <div style="display:flex; justify-content:space-between; margin-bottom:15px; font-size:1.2rem; font-weight:bold;">
                <span>Total:</span>
                <span id="cartTotal">₹0</span>
            </div>
            <button class="btn btn-buy" style="width:100%; padding:15px; font-size:1rem;" onclick="openCheckout()">Proceed to Checkout</button>
        </div>
    </div>

    <!-- Main Content -->
    <div class="container">
        <div class="section-header">
            <h2 id="collectionTitle">Featured Collection</h2>
            <div style="height:2px; background:var(--primary-color); flex:1; opacity:0.5;"></div>
        </div>
        <div class="product-grid" id="productGrid">
            <!-- Products via JS -->
        </div>
    </div>

    <!-- Live Hype Notification (Hidden by default) -->
    <div id="hypeNotification" class="hype-notification">
        <img id="hypeImg" src="" class="hype-img">
        <div>
            <p id="hypeText" style="font-size:0.85rem; margin-bottom:2px;">Someone in <b>London</b> bought...</p>
            <h5 id="hypeItem" style="font-size:1rem;">Royal Gold Watch</h5>
            <span style="font-size:0.7rem; color:#888;">2 minutes ago</span>
        </div>
    </div>

    <!-- Footer -->
    <footer id="footer">
        <div class="footer-content">
            <div class="footer-col">
                <h3>Contact Us</h3>
                <!-- Address Added Here -->
                <p><i class="fas fa-map-marker-alt"></i> Lar Town, Deoria</p>
                <p><i class="fas fa-phone"></i> +91 9919900000</p>
                <p><i class="fas fa-envelope"></i> help@luxestyle.com</p>
            </div>
            <div class="footer-col">
                <h3>Quick Links</h3>
                <a href="#">Men's Fashion</a>
                <a href="#">Women's Fashion</a>
            </div>
            <div class="footer-col">
                <h3>Social</h3>
                <a href="#">Instagram</a>
                <a href="#">Facebook</a>
            </div>
        </div>
        <div class="teen-credit">Made by Teenagers with the help of AI.</div>
    </footer>

    <!-- MODALS -->

    <!-- Welcome -->
    <div id="welcomePopup" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal('welcomePopup')">&times;</span>
            <h2 style="color:var(--primary-color);">Welcome to LuxeStyle</h2>
            <p>Experience the next gen of shopping with AI Moods, Negotiation & Virtual Studio.</p>
            <br><button class="btn btn-buy" onclick="closeModal('welcomePopup')">Shop Now</button>
        </div>
    </div>

    <!-- MULTI-OPTION PAYMENT MODAL -->
    <div id="paymentModal" class="modal">
        <div class="modal-content" style="text-align:left;">
            <span class="close-btn" onclick="closeModal('paymentModal')">&times;</span>
            <h2 style="text-align:center; margin-bottom:20px;">Secure Checkout</h2>
            <form onsubmit="event.preventDefault(); processPayment();">
                <div style="margin-bottom:20px;">
                    <p style="font-weight:bold; margin-bottom:10px;">Select Payment Method:</p>
                    
                    <label class="pay-option">
                        <input type="radio" name="pay_method" value="UPI" checked onclick="togglePaymentFields()">
                        <i class="fas fa-mobile-alt" style="color:#25D366; font-size:1.2rem;"></i>
                        <span>UPI (GPay, PhonePe, Paytm)</span>
                    </label>

                    <label class="pay-option">
                        <input type="radio" name="pay_method" value="Card" onclick="togglePaymentFields()">
                        <i class="fas fa-credit-card" style="color:#54a0ff; font-size:1.2rem;"></i>
                        <span>Credit / Debit Card</span>
                    </label>

                    <label class="pay-option">
                        <input type="radio" name="pay_method" value="NetBanking" onclick="togglePaymentFields()">
                        <i class="fas fa-university" style="color:#f39c12; font-size:1.2rem;"></i>
                        <span>Net Banking</span>
                    </label>

                    <label class="pay-option">
                        <input type="radio" name="pay_method" value="COD" onclick="togglePaymentFields()">
                        <i class="fas fa-money-bill-wave" style="color:#2ecc71; font-size:1.2rem;"></i>
                        <span>Cash on Delivery</span>
                    </label>
                </div>

                <!-- Input Fields -->
                <div id="paymentInputs" style="margin-bottom:15px;">
                    <input type="text" id="payDetailInput" placeholder="Enter UPI ID (e.g. name@okaxis)" required style="width:100%; padding:12px; border:1px solid #ddd; border-radius:8px;">
                </div>

                <!-- Total -->
                <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:20px; font-weight:bold; font-size:1.2rem; padding-top:10px; border-top:1px solid #eee;">
                    <span>Total Payable:</span>
                    <span id="checkoutTotalDisplay" style="color:var(--primary-color);">₹0</span>
                </div>

                <button class="btn btn-buy" style="width:100%; padding:12px; font-size:1.1rem;">Place Order Now</button>
            </form>
        </div>
    </div>

    <!-- Negotiator -->
    <div id="negotiateModal" class="modal">
        <div class="modal-content" style="width:100%; max-width:400px; text-align:left;">
            <span class="close-btn" onclick="closeModal('negotiateModal')">&times;</span>
            <div style="text-align:center; margin-bottom:15px;">
                <h3 style="color:var(--primary-color);"><i class="fas fa-robot"></i> AI Negotiator</h3>
                <p id="negotiateItemName" style="font-size:0.9rem; color:#888;">Haggle for the best price!</p>
            </div>
            <div class="chat-box" id="negotiateChat"></div>
            <div class="offer-controls" id="offerControls">
                <input type="number" id="offerInput" class="offer-input" placeholder="Your Offer (₹)">
                <button class="btn btn-buy" onclick="submitOffer()" style="width:auto; padding:0 20px;">Offer</button>
            </div>
            <button id="claimDealBtn" class="btn btn-buy" style="width:100%; display:none; background:#2ed573;" onclick="claimNegotiatedDeal()">Add to Cart at Deal Price</button>
        </div>
    </div>

    <!-- Virtual Studio Modal -->
    <div id="studioModal" class="modal">
        <div class="modal-content" style="width:90%; max-width:800px;">
            <span class="close-btn" onclick="closeModal('studioModal')">&times;</span>
            <h2 style="color:var(--primary-color); margin-bottom:10px;">Mix & Match Studio</h2>
            <p style="margin-bottom:20px;">Drag items from left to right to create your look!</p>
            
            <div class="studio-layout">
                <div class="studio-sidebar" id="studioSidebar">
                    <!-- Thumbnails generated by JS -->
                </div>
                <div class="studio-canvas" id="studioCanvas" ondrop="drop(event)" ondragover="allowDrop(event)">
                    <p class="studio-hint">Drop Items Here</p>
                    <!-- Dropped items go here -->
                </div>
            </div>
            <button class="btn btn-buy" style="margin-top:20px;" onclick="alert('Look saved to gallery! (Simulation)')">Save Look 📸</button>
        </div>
    </div>

    <!-- Spin Wheel -->
    <div id="spinModal" class="modal">
        <div class="modal-content" style="background:#222; width:400px; border:1px solid gold;">
            <span class="close-btn" onclick="closeModal('spinModal')" style="color:white; z-index:100;">&times;</span>
            <h2 style="color:gold;">LUCKY SPIN</h2>
            <div class="wheel-wrapper">
                <div class="wheel-pointer"></div>
                <div class="wheel" id="wheel"></div>
                <div class="spin-btn-center" onclick="spinWheel()">SPIN</div>
            </div>
            <div id="winPopup" class="win-popup">
                <h3 style="color:#333;">Congratulations!</h3>
                <p id="winText" style="font-size:1.2rem; font-weight:bold; color:#ff4757;"></p>
                <button class="btn btn-buy" style="margin-top:10px;" onclick="closeWinPopup()">Claim Prize</button>
            </div>
        </div>
    </div>

    <script>
        // --- DATA ---
        const products = [
            { id: 1, name: "Royal Gold Watch", category: "watch", price: 12999, mood: "pro", img: "https://images.unsplash.com/photo-1547996160-81dfa63595aa?auto=format&fit=crop&w=500&q=80" },
            { id: 2, name: "Men's Tuxedo", category: "manwear", price: 8500, mood: "pro", img: "https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=500&q=80" },
            { id: 3, name: "Summer Floral Dress", category: "womenwear", price: 3200, mood: "happy", img: "https://images.unsplash.com/photo-1572804013309-59a88b7e92f1?auto=format&fit=crop&w=500&q=80" },
            { id: 4, name: "Street Sneakers", category: "shoes", price: 4100, mood: "party", img: "https://images.unsplash.com/photo-1552346154-21d32810aba3?auto=format&fit=crop&w=500&q=80" },
            { id: 5, name: "Comfy Socks Set", category: "socks", price: 499, mood: "happy", img: "https://images.unsplash.com/photo-1586350977771-b3b0abd50f82?auto=format&fit=crop&w=500&q=80" },
            { id: 6, name: "Party Stilettos", category: "shoes", price: 3800, mood: "party", img: "https://images.unsplash.com/photo-1543163521-1bf539c55dd2?auto=format&fit=crop&w=500&q=80" },
            { id: 7, name: "Classic Aviators", category: "accessories", price: 1500, mood: "happy", img: "https://images.unsplash.com/photo-1572635196237-14b3f281503f?auto=format&fit=crop&w=500&q=80" },
            { id: 8, name: "Leather Handbag", category: "womenwear", price: 4500, mood: "pro", img: "https://images.unsplash.com/photo-1584917865442-de89df76afd3?auto=format&fit=crop&w=500&q=80" }
        ];

        let cart = [];
        let wishlist = [];

        // Negotiator Vars
        let currentNegotiationProduct = null;
        let minAcceptablePrice = 0;
        let attemptCount = 0;

        window.onload = function() {
            renderProducts(products);
            setTimeout(() => document.getElementById('welcomePopup').style.display = 'flex', 1500);
            startHypeSystem();
        };

        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            grid.innerHTML = list.map(p => `
                <div class="product-card">
                    <i class="fas fa-heart wishlist-icon" onclick="toggleWishlist(this, ${p.id})"></i>
                    <img src="${p.img}" alt="${p.name}" class="product-img">
                    <div class="product-info">
                        <h3 class="product-title">${p.name}</h3>
                        <div class="rating">★★★★☆</div>
                        <p class="price">₹${p.price.toLocaleString()}</p>
                        <div class="btn-group">
                            <button class="btn btn-cart" onclick="addToCart(${p.id})">Add</button>
                            <button class="btn btn-haggle" onclick="startNegotiation(${p.id})"><i class="fas fa-comments-dollar"></i> Haggle</button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // --- CART ---
        function addToCart(id, customPrice = null) {
            const item = products.find(p => p.id === id);
            let cartItem = {...item};
            if(customPrice) { cartItem.price = customPrice; cartItem.name += " (Deal)"; }
            cart.push(cartItem);
            updateCartUI();
            if(!customPrice) toggleCart();
        }

        function removeFromCart(index) { cart.splice(index, 1); updateCartUI(); }
        
        function updateCartUI() {
            document.getElementById('cartCount').innerText = cart.length;
            const container = document.getElementById('cartItemsContainer');
            const totalEl = document.getElementById('cartTotal');
            if (cart.length === 0) { container.innerHTML = '<p style="text-align:center; margin-top:30px; color:#999;">Empty.</p>'; totalEl.innerText = '₹0'; return; }
            let total = 0;
            container.innerHTML = cart.map((item, index) => {
                total += item.price;
                return `<div class="cart-item"><img src="${item.img}"><div class="cart-details"><h4>${item.name}</h4><span class="price">₹${item.price}</span></div><i class="fas fa-trash remove-icon" onclick="removeFromCart(${index})"></i></div>`;
            }).join('');
            totalEl.innerText = '₹' + total.toLocaleString();
        }
        function toggleCart() { document.getElementById('cartSidebar').classList.toggle('open'); }

        // --- NEGOTIATOR ---
        function startNegotiation(id) {
            currentNegotiationProduct = products.find(p => p.id === id);
            minAcceptablePrice = Math.floor(currentNegotiationProduct.price * 0.85);
            attemptCount = 0;
            document.getElementById('negotiateItemName').innerText = `Negotiating: ${currentNegotiationProduct.name} (Listed: ₹${currentNegotiationProduct.price})`;
            document.getElementById('negotiateChat').innerHTML = '';
            document.getElementById('offerControls').style.display = 'flex';
            document.getElementById('claimDealBtn').style.display = 'none';
            document.getElementById('offerInput').value = '';
            addMessage("bot", `Hello! I see you like the ${currentNegotiationProduct.name}. The price is ₹${currentNegotiationProduct.price}. What is your offer?`);
            openModal('negotiateModal');
        }

        function addMessage(sender, text) {
            const div = document.createElement('div'); div.className = `message ${sender}-msg`; div.innerText = text;
            const box = document.getElementById('negotiateChat'); box.appendChild(div); box.scrollTop = box.scrollHeight;
        }

        function submitOffer() {
            const offer = parseInt(document.getElementById('offerInput').value);
            if(!offer) return;
            addMessage("user", `I offer ₹${offer}`);
            document.getElementById('offerInput').value = '';
            setTimeout(() => processOffer(offer), 1000);
        }

        function processOffer(offer) {
            attemptCount++;
            if (offer < currentNegotiationProduct.price * 0.5) { addMessage("bot", "Too low! Be reasonable."); return; }
            if (offer >= minAcceptablePrice) { addMessage("bot", `Deal! ₹${offer} is fair.`); finalizeDeal(offer); return; }
            if (attemptCount >= 3) { addMessage("bot", `Lowest I can go is ₹${minAcceptablePrice}. Take it or leave it.`); finalizeDeal(minAcceptablePrice); } 
            else { 
                const counter = Math.floor((offer + currentNegotiationProduct.price)/2);
                addMessage("bot", `Hmm, how about ₹${counter}?`); 
            }
        }
        function finalizeDeal(price) {
            document.getElementById('offerControls').style.display = 'none';
            const btn = document.getElementById('claimDealBtn'); btn.style.display = 'block'; btn.innerText = `Add @ ₹${price}`;
            btn.onclick = () => { addToCart(currentNegotiationProduct.id, price); closeModal('negotiateModal'); toggleCart(); };
        }

        // --- VIRTUAL STUDIO ---
        function openStudio() {
            openModal('studioModal');
            const sidebar = document.getElementById('studioSidebar');
            sidebar.innerHTML = products.map(p => `
                <div class="studio-item-thumb" draggable="true" ondragstart="drag(event, '${p.img}')">
                    <img src="${p.img}">
                    <span style="font-size:0.8rem;">${p.name}</span>
                </div>
            `).join('');
        }

        function allowDrop(ev) { ev.preventDefault(); }
        function drag(ev, imgSrc) { ev.dataTransfer.setData("text", imgSrc); }
        function drop(ev) {
            ev.preventDefault();
            const data = ev.dataTransfer.getData("text");
            // Basic validation to ensure we are dropping on canvas
            if(ev.target.id !== "studioCanvas" && !ev.target.classList.contains('studio-canvas')) return;
            
            const img = document.createElement("img");
            img.src = data; 
            img.className = "canvas-obj";
            
            // Position where dropped
            const rect = document.getElementById('studioCanvas').getBoundingClientRect();
            let x = ev.clientX - rect.left - 40; 
            let y = ev.clientY - rect.top - 40;
            
            img.style.left = x + 'px';
            img.style.top = y + 'px';
            
            // Make created item draggable within canvas
            img.onmousedown = function(event) {
                let shiftX = event.clientX - img.getBoundingClientRect().left;
                let shiftY = event.clientY - img.getBoundingClientRect().top;
                
                function moveAt(pageX, pageY) {
                    img.style.left = pageX - rect.left - shiftX + 'px';
                    img.style.top = pageY - rect.top - shiftY + 'px';
                }
                
                function onMouseMove(event) { moveAt(event.clientX, event.clientY); }
                document.addEventListener('mousemove', onMouseMove);
                
                img.onmouseup = function() {
                    document.removeEventListener('mousemove', onMouseMove);
                    img.onmouseup = null;
                };
            };
            img.ondragstart = function() { return false; }; 
            
            document.getElementById('studioCanvas').appendChild(img);
            document.querySelector('.studio-hint').style.display = 'none';
        }

        // --- LIVE HYPE ---
        function startHypeSystem() {
            setInterval(() => {
                const cities = ["Mumbai", "London", "New York", "Paris", "Delhi", "Tokyo"];
                const p = products[Math.floor(Math.random() * products.length)];
                const c = cities[Math.floor(Math.random() * cities.length)];
                document.getElementById('hypeImg').src = p.img;
                document.getElementById('hypeText').innerHTML = `Someone in <b>${c}</b> bought...`;
                document.getElementById('hypeItem').innerText = p.name;
                const notif = document.getElementById('hypeNotification');
                notif.classList.add('show');
                setTimeout(() => notif.classList.remove('show'), 5000);
            }, 15000);
        }

        // --- SPIN WHEEL, MOOD ---
        function spinWheel() {
            const wheel = document.getElementById('wheel');
            // Generate segments if empty
            if(!wheel.innerHTML) {
                const labels = ["10% OFF", "BAD LUCK", "FREE SHIP", "₹500 OFF", "JACKPOT", "TRY AGAIN", "20% OFF", "MYSTERY"];
                wheel.innerHTML = labels.map((l, i) => `
                    <div class="wheel-label" style="transform: rotate(${i * 45 + 22.5}deg);">
                        ${l}
                    </div>
                `).join('');
            }
            
            const spins = 5 + Math.floor(Math.random()*5);
            const deg = (spins * 360) + Math.floor(Math.random()*360);
            wheel.style.transform = `rotate(${deg}deg)`;
            
            // Determine win (Simulated)
            setTimeout(() => {
                const finalDeg = deg % 360;
                // Simple win logic for demo
                document.getElementById('winText').innerText = "You won a Mystery Prize!";
                document.getElementById('winPopup').classList.add('show');
            }, 5000);
        }
        function closeWinPopup() { document.getElementById('winPopup').classList.remove('show'); closeModal('spinModal'); }

        function setMood(mood) {
            const root = document.documentElement;
            const t = document.getElementById('collectionTitle');
            if(mood==='pro') { 
                root.style.setProperty('--primary-color','#2c3e50'); 
                t.innerText="Professional Collection"; 
                renderProducts(products.filter(p=>p.mood==='pro')); 
            }
            else if(mood==='party') { 
                root.style.setProperty('--primary-color','#ff4757'); 
                t.innerText="Night Out Collection"; 
                renderProducts(products.filter(p=>p.mood==='party')); 
            }
            else { 
                root.style.setProperty('--primary-color','#d4af37'); 
                t.innerText="Featured Collection"; 
                renderProducts(products); 
            }
        }

        // --- PAYMENT SYSTEM LOGIC ---
        function openCheckout() {
            if(cart.length === 0) { alert("Cart is empty!"); return; }
            const total = cart.reduce((sum, item) => sum + item.price, 0);
            document.getElementById('checkoutTotalDisplay').innerText = '₹' + total.toLocaleString();
            openModal('paymentModal');
        }

        function togglePaymentFields() {
            const method = document.querySelector('input[name="pay_method"]:checked').value;
            const input = document.getElementById('payDetailInput');
            if(method === 'UPI') { input.style.display='block'; input.placeholder="Enter UPI ID (e.g. name@okaxis)"; input.required=true; }
            else if(method === 'Card') { input.style.display='block'; input.placeholder="Card Number"; input.required=true; }
            else if(method === 'NetBanking') { input.style.display='none'; input.required=false; }
            else { input.style.display='none'; input.required=false; }
        }

        function processPayment() {
            const method = document.querySelector('input[name="pay_method"]:checked').value;
            // Simulate processing
            const btn = document.querySelector('#paymentModal .btn-buy');
            const originalText = btn.innerText;
            btn.innerText = "Processing...";
            btn.disabled = true;
            
            setTimeout(() => {
                alert(`Order Placed Successfully via ${method}! Confirmation sent.`);
                cart = [];
                updateCartUI();
                closeModal('paymentModal');
                btn.innerText = originalText;
                btn.disabled = false;
            }, 2000);
        }

        function toggleTheme() { document.body.classList.toggle('dark-mode'); }
        function openModal(id) { document.getElementById(id).style.display = 'flex'; }
        function closeModal(id) { document.getElementById(id).style.display = 'none'; }
        
        function toggleWishlist(el, id) { 
            el.classList.toggle('active'); 
            let c = document.getElementById('wishlistCount'); 
            c.innerText = el.classList.contains('active') ? parseInt(c.innerText)+1 : parseInt(c.innerText)-1; 
        }
        
        function toggleDropdown() { 
            const d = document.getElementById('dropdownMenu'); 
            d.style.display = d.style.display==='block'?'none':'block'; 
        }
        
        function filterProducts() { 
            const q = document.getElementById('searchInput').value.toLowerCase(); 
            renderProducts(products.filter(p => p.name.toLowerCase().includes(q))); 
        }
        
        // Close modals on outside click
        window.onclick = function(e) { 
            if(e.target.classList.contains('modal')) e.target.style.display='none'; 
            if(!e.target.matches('.fa-ellipsis-v')) document.getElementById('dropdownMenu').style.display='none'; 
        }
    </script>
</body>
</html>
