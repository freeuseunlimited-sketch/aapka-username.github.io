# aapka-username.github.io        #input-area {
            display: flex;
            gap: 10px;
        }

        input {
            flex: 1;
            padding: 12px;
            border-radius: 25px;
            border: none;
            outline: none;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        button {
            padding: 10px 20px;
            border-radius: 25px;
            border: none;
            background: #ff69b4;
            color: white;
            cursor: pointer;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div id="ui-layer">
        <div id="chat-box">Acha ji, ab yaad aayi meri? 😤🥺</div>
        <div id="input-area">
            <input type="text" id="user-input" placeholder="Talk to Isha...">
            <button onclick="sendMessage()">Send</button>
        </div>
    </div>

    <!-- Load Three.js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <script>
        // --- 3D WORLD SETUP ---
        const scene = new THREE.Scene();
        scene.
