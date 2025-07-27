<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Uranus Hub - Key Generator</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: white;
        }

        .container {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.2);
            text-align: center;
            max-width: 500px;
            width: 90%;
            animation: fadeIn 1s ease-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #fff, #e0e0e0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }

        .subtitle {
            font-size: 1.1rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .key-display {
            background: rgba(0, 0, 0, 0.3);
            border: 2px solid rgba(255, 255, 255, 0.3);
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            font-family: 'Courier New', monospace;
            font-size: 1.2rem;
            font-weight: bold;
            color: #00ff88;
            text-shadow: 0 0 10px rgba(0, 255, 136, 0.5);
            word-break: break-all;
            min-height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }

        .key-display.generated {
            animation: glow 0.5s ease-out;
        }

        @keyframes glow {
            0% {
                box-shadow: 0 0 5px rgba(0, 255, 136, 0.5);
            }
            50% {
                box-shadow: 0 0 20px rgba(0, 255, 136, 0.8);
            }
            100% {
                box-shadow: 0 0 5px rgba(0, 255, 136, 0.5);
            }
        }

        .generate-btn {
            background: linear-gradient(45deg, #00ff88, #00cc6a);
            border: none;
            border-radius: 50px;
            padding: 15px 30px;
            font-size: 1.1rem;
            font-weight: bold;
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 255, 136, 0.3);
            margin: 10px;
        }

        .generate-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0, 255, 136, 0.4);
            background: linear-gradient(45deg, #00cc6a, #00ff88);
        }

        .generate-btn:active {
            transform: translateY(0);
        }

        .copy-btn {
            background: linear-gradient(45deg, #4facfe, #00f2fe);
            border: none;
            border-radius: 50px;
            padding: 10px 20px;
            font-size: 0.9rem;
            font-weight: bold;
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(79, 172, 254, 0.3);
            margin: 10px;
        }

        .copy-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(79, 172, 254, 0.4);
        }

        .copy-btn:disabled {
            background: #666;
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }

        .info {
            margin-top: 20px;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            font-size: 0.9rem;
            opacity: 0.8;
        }

        .format-example {
            color: #ffeb3b;
            font-family: 'Courier New', monospace;
            font-weight: bold;
        }

        .copied-message {
            position: fixed;
            top: 20px;
            right: 20px;
            background: #00ff88;
            color: #000;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: bold;
            opacity: 0;
            transition: opacity 0.3s ease;
            z-index: 1000;
        }

        .copied-message.show {
            opacity: 1;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🪐 Uranus Hub</h1>
        <p class="subtitle">Generate Your Key</p>
        
        <div class="key-display" id="keyDisplay">
            Click "Generate Key" to create your unique key
        </div>
        
        <button class="generate-btn" onclick="generateKey()">
            🔑 Generate Key
        </button>
        
        <button class="copy-btn" id="copyBtn" onclick="copyKey()" disabled>
            📋 Copy Key
        </button>
        
        <div class="info">
            <p><strong>Key Format:</strong> <span class="format-example">Uranus_78DY-DYGH-09SJH</span></p>
            <p>Each key contains 3 segments separated by dashes (4-4-5 characters)</p>
        </div>
    </div>

    <div class="copied-message" id="copiedMessage">
        Key copied to clipboard! ✓
    </div>

    <script>
        let currentKey = '';

        function generateRandomString(length) {
            const chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789';
            let result = '';
            for (let i = 0; i < length; i++) {
                result += chars.charAt(Math.floor(Math.random() * chars.length));
            }
            return result;
        }

        function generateKey() {
            const part1 = generateRandomString(4);
            const part2 = generateRandomString(4);
            const part3 = generateRandomString(5);
            const newKey = `Uranus_${part1}-${part2}-${part3}`;
            
            const keyDisplay = document.getElementById('keyDisplay');
            const copyBtn = document.getElementById('copyBtn');
            
            // Add generation animation
            keyDisplay.classList.remove('generated');
            setTimeout(() => {
                currentKey = newKey;
                keyDisplay.textContent = newKey;
                keyDisplay.classList.add('generated');
                copyBtn.disabled = false;
            }, 100);
        }

        function copyKey() {
            if (currentKey) {
                navigator.clipboard.writeText(currentKey).then(() => {
                    showCopiedMessage();
                }).catch(() => {
                    // Fallback for older browsers
                    const textArea = document.createElement('textarea');
                    textArea.value = currentKey;
                    document.body.appendChild(textArea);
                    textArea.select();
                    document.execCommand('copy');
                    document.body.removeChild(textArea);
                    showCopiedMessage();
                });
            }
        }

        function showCopiedMessage() {
            const message = document.getElementById('copiedMessage');
            message.classList.add('show');
            setTimeout(() => {
                message.classList.remove('show');
            }, 2000);
        }

        // Generate a key on page load
        window.addEventListener('load', () => {
            setTimeout(generateKey, 500);
        });

        // Allow Enter key to generate new key
        document.addEventListener('keydown', (e) => {
            if (e.key === 'Enter') {
                generateKey();
            }
        });
    </script>
</body>
</html>
