<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>वैष्णवी जन सेवा केंद्र - UP e-District आवेदन फॉर्म</title>
    <style>
        :root {
            --navy: #0f172a;
            --primary: #1d4ed8;
            --primary-dark: #1e3a8a;
            --accent: #f59e0b;
            --wa: #25D366;
            --bg: #eef2f6;
            --card: #ffffff;
            --text: #111827;
            --muted: #64748b;
            --border: #cbd5e1;
        }
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }
        body {
            background: var(--bg);
            color: var(--text);
            padding: 12px;
        }
        .app-wrap {
            max-width: 560px;
            margin: 0 auto;
            background: var(--card);
            border-radius: 16px;
            box-shadow: 0 10px 26px rgba(15, 23, 42, 0.1);
            overflow: hidden;
        }
        .header {
            background: linear-gradient(135deg, var(--navy), var(--primary-dark), var(--primary));
            color: #ffffff;
            padding: 20px 16px;
            text-align: center;
        }
        .header h1 {
            font-size: 21px;
            font-weight: 700;
            margin-bottom: 4px;
        }
        .header p {
            font-size: 12.5px;
            opacity: 0.92;
        }
        .badge {
            display: inline-block;
            background: var(--accent);
            color: #111827;
            font-size: 11px;
            font-weight: 700;
            padding: 4px 12px;
            border-radius: 999px;
            margin-top: 10px;
        }
        .tabs {
            display: grid;
            grid-template-columns: 1fr 1fr;
            background: #f8fafc;
            border-bottom: 1px solid #e2e8f0;
        }
        .tab-btn {
            padding: 12px;
            border: none;
            background: transparent;
            font-size: 13.5px;
            font-weight: 600;
            color: var(--muted);
            cursor: pointer;
            border-bottom: 3px solid transparent;
        }
        .tab-btn.active {
            color: var(--primary);
            border-bottom-color: var(--primary);
            background: #ffffff;
        }
        .body-area {
            padding: 18px;
        }
        .pane {
            display: none;
        }
        .pane.active {
            display: block;
        }
        .box-card {
            background: #f8fafc;
            border: 1px solid #e2e8f0;
            border-radius: 12px;
            padding: 14px;
            margin-bottom: 14px;
        }
        .box-title {
            font-size: 13px;
            font-weight: 700;
            color: var(--primary-dark);
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 0.3px;
        }
        .group {
            margin-bottom: 12px;
        }
        .group:last-child {
            margin-bottom: 0;
        }
        label {
            display: block;
            font-size: 12.8px;
            font-weight: 600;
            color: #1f2937;
            margin-bottom: 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px 12px;
            border: 1.5px solid var(--border);
            border-radius: 9px;
            font-size: 14px;
            background: #ffffff;
            color: var(--text);
        }
        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: var(--primary);
        }
        .row-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }
        .row-3 {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 8px;
        }
        .doc-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 8px;
        }
        .doc-item {
            display: flex;
            align-items: center;
            gap: 7px;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            padding: 8px 10px;
            border-radius: 8px;
            font-size: 12.5px;
            font-weight: 500;
            margin-bottom: 0;
            cursor: pointer;
        }
        .doc-item input {
            width: auto;
        }
        .file-preview {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
            margin-top: 8px;
        }
        .file-chip {
            background: #dbeafe;
            color: #1e40af;
            font-size: 11.5px;
            font-weight: 600;
            padding: 4px 8px;
            border-radius: 6px;
        }
        .btn-wa {
            width: 100%;
            background: var(--wa);
            color: #ffffff;
            border: none;
            padding: 14px;
            border-radius: 11px;
            font-size: 15.5px;
            font-weight: 700;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(37, 211, 102, 0.28);
        }
        .btn-sub {
            width: 100%;
            background: #e2e8f0;
            color: #0f172a;
            border: none;
            padding: 11px;
            border-radius: 10px;
            font-size: 13px;
            font-weight: 600;
            cursor: pointer;
            margin-top: 8px;
        }
        .btn-copy-sm {
            background: #eff6ff;
            color: var(--primary-dark);
            border: 1px solid #bfdbfe;
            padding: 5px 10px;
            border-radius: 7px;
            font-size: 11.5px;
            font-weight: 700;
            cursor: pointer;
        }
        .btn-del-sm {
            background: #fef2f2;
            color: #b91c1c;
            border: 1px solid #fecaca;
            padding: 5px 10px;
            border-radius: 7px;
            font-size: 11.5px;
            font-weight: 700;
            cursor: pointer;
        }
        .rec-card {
            background: #f8fafc;
            border: 1px solid #e2e8f0;
            border-radius: 12px;
            padding: 12px;
            margin-bottom: 10px;
        }
        .rec-head {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 8px;
            margin-bottom: 8px;
        }
        .rec-badge {
            background: #dbeafe;
            color: #1e3a8a;
            font-size: 11.5px;
            font-weight: 700;
            padding: 3px 9px;
            border-radius: 6px;
        }
        .rec-actions {
            display: flex;
            gap: 6px;
        }
        .rec-details {
            font-size: 12.5px;
            line-height: 1.55;
            color: #1f2937;
        }
        .empty {
            text-align: center;
            color: var(--muted);
            padding: 28px 10px;
            font-size: 13.5px;
        }
        .note {
            font-size: 11.5px;
            color: var(--muted);
            text-align: center;
            margin-top: 12px;
            line-height: 1.45;
        }
        @media (max-width: 480px) {
            .row-2, .row-3, .doc-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<div class="app-wrap">
    <div class="header">
        <h1>वैष्णवी जन सेवा केंद्र</h1>
        <p>झरेखापुर पुलिस चौकी के सामने, सीतापुर (उ.प्र.) • सिद्धार्थ गुरु जी</p>
        <span class="badge">UP e-District • आय • जाति • निवास • ऑनलाइन फॉर्म</span>
    </div>

    <div class="tabs">
        <button type="button" class="tab-btn active" id="btnTabForm" onclick="openTab('form')">📝 आवेदन फॉर्म भरें</button>
        <button type="button" class="tab-btn" id="btnTabRec" onclick="openTab('records')">📂 आवेदन रिकॉर्ड (<span id="recCount">0</span>)</button>
    </div>

    <div class="body-area">
        <div id="paneForm" class="pane active">
            <form id="edistrictForm" onsubmit="submitForm(event)">
                <div class="box-card">
                    <div class="box-title">1. सेवा और आवेदक विवरण</div>

                    <div class="group">
                        <label for="certService">प्रमाण पत्र / सेवा चुनें *</label>
                        <select id="certService" required onchange="toggleServiceHints()">
                            <option value="">-- सेवा चुनें --</option>
                            <option value="आय प्रमाण पत्र (Income Certificate - UP e-District)">आय प्रमाण पत्र (Income Certificate)</option>
                            <option value="जाति प्रमाण पत्र (Caste Certificate - UP e-District)">जाति प्रमाण पत्र (Caste Certificate)</option>
                            <option value="निवास प्रमाण पत्र (Domicile / Niwas - UP e-District)">निवास प्रमाण पत्र (Domicile / Niwas)</option>
                            <option value="ऑनलाइन नौकरी / प्रवेश फॉर्म (Job / Admission Form)">ऑनलाइन नौकरी / प्रवेश फॉर्म</option>
                            <option value="पेंशन / राशन / पैन / अन्य CSC सेवा">पेंशन / राशन / पैन / अन्य CSC सेवा</option>
                        </select>
                    </div>

                    <div class="row-2">
                        <div class="group">
                            <label for="appName">आवेदक का नाम *</label>
                            <input type="text" id="appName" placeholder="आधार के अनुसार नाम" required>
                        </div>
                        <div class="group">
                            <label for="gender">लिंग (Gender) *</label>
                            <select id="gender" required>
                                <option value="">चुनें</option>
                                <option value="पुरुष (Male)">पुरुष (Male)</option>
                                <option value="महिला (Female)">महिला (Female)</option>
                                <option value="अन्य">अन्य</option>
                            </select>
                        </div>
                    </div>

                    <div class="row-2">
                        <div class="group">
                            <label for="guardianName">पिता / पति का नाम *</label>
                            <input type="text" id="guardianName" placeholder="पिता या पति का नाम" required>
                        </div>
                        <div class="group">
                            <label for="momName">माता का नाम *</label>
                            <input type="text" id="momName" placeholder="माता का नाम" required>
                        </div>
                    </div>

                    <div class="row-2">
                        <div class="group">
                            <label for="phoneNo">मोबाइल नंबर (10 अंक) *</label>
                            <input type="tel" id="phoneNo" pattern="[0-9]{10}" maxlength="10" placeholder="98XXXXXXXX" required>
                        </div>
                        <div class="group">
                            <label for="aadhaarNo">आधार नंबर (12 अंक) *</label>
                            <input type="tel" id="aadhaarNo" pattern="[0-9]{12}" maxlength="12" placeholder="12 अंकों का आधार" required>
                        </div>
                    </div>
                </div>

                <div class="box-card">
                    <div class="box-title">2. पता (ग्राम / पोस्ट / तहसील / जिला)</div>

                    <div class="row-2">
                        <div class="group">
                            <label for="village">ग्राम / मोहल्ला *</label>
                            <input type="text" id="village" placeholder="ग्राम का नाम" required>
                        </div>
                        <div class="group">
                            <label for="postOffice">पोस्ट (Post) *</label>
                            <input type="text" id="postOffice" placeholder="जैसे: झरेखापुर" required>
                        </div>
                    </div>

                    <div class="row-3">
                        <div class="group">
                            <label for="tehsil">तहसील *</label>
                            <input type="text" id="tehsil" placeholder="तहसील का नाम" required>
                        </div>
                        <div class="group">
                            <label for="blockArea">विकासखंड (Block)</label>
                            <input type="text" id="blockArea" placeholder="ब्लॉक का नाम">
                        </div>
                        <div class="group">
                            <label for="district">जिला *</label>
                            <input type="text" id="district" value="सीतापुर" required>
                        </div>
                    </div>
                </div>

                <div class="box-card">
                    <div class="box-title">3. आय / जाति / निवास / फॉर्म विशेष विवरण</div>

                    <div class="row-2">
                        <div class="group">
                            <label for="casteCat">जाति श्रेणी (Caste Category)</label>
                            <select id="casteCat">
                                <option value="नहीं लागू">चुनें / लागू नहीं</option>
                                <option value="सामान्य (General)">सामान्य (General)</option>
                                <option value="अन्य पिछड़ा वर्ग (OBC)">अन्य पिछड़ा वर्ग (OBC)</option>
                                <option value="अनुसूचित जाति (SC)">अनुसूचित जाति (SC)</option>
                                <option value="अनुसूचित जनजाति (ST)">अनुसूचित जनजाति (ST)</option>
                            </select>
                        </div>
                        <div class="group">
                            <label for="casteName">उपजाति / जाति का नाम</label>
                            <input type="text" id="casteName" placeholder="जैसे: यादव, मौर्य, वर्मा आदि">
                        </div>
                    </div>

                    <div class="row-2">
                        <div class="group">
                            <label for="annualIncome">कुल वार्षिक आय (₹ में)</label>
                            <input type="text" id="annualIncome" placeholder="जैसे: 48000 या 60000">
                        </div>
                        <div class="group">
                            <label for="familyCount">परिवार के कुल सदस्य</label>
                            <input type="number" id="familyCount" min="1" placeholder="जैसे: 5">
                        </div>
                    </div>

                    <div class="group">
                        <label for="incomeSources">आय के स्रोत (नौकरी / कृषि / मजदूरी / अन्य)</label>
                        <input type="text" id="incomeSources" placeholder="जैसे: कृषि ₹30,000 + मजदूरी ₹18,000">
                    </div>

                    <div class="group">
                        <label for="extraDetails">अतिरिक्त जानकारी (पिछला प्रमाण पत्र नंबर / फॉर्म विवरण)</label>
                        <textarea id="extraDetails" rows="2" placeholder="यदि पहले आय/जाति/निवास बना है या किसी विशेष फॉर्म की जानकारी है तो लिखें"></textarea>
                    </div>
                </div>

                <div class="box-card">
                    <div class="box-title">4. उपलब्ध दस्तावेज और फाइलें</div>

                    <div class="group">
                        <div class="doc-grid">
                            <label class="doc-item"><input type="checkbox" name="docsList" value="फोटो"> पासपोर्ट फोटो</label>
                            <label class="doc-item"><input type="checkbox" name="docsList" value="आधार कार्ड"> आधार कार्ड</label>
                            <label class="doc-item"><input type="checkbox" name="docsList" value="राशन कार्ड"> राशन कार्ड</label>
                            <label class="doc-item"><input type="checkbox" name="docsList" value="स्वप्रमाणित घोषणा पत्र"> घोषणा पत्र</label>
                            <label class="doc-item"><input type="checkbox" name="docsList" value="परिवार रजिस्टर / खतौनी"> परिवार रजिस्टर / खतौनी</label>
                            <label class="doc-item"><input type="checkbox" name="docsList" value="मार्कशीट / प्रमाण पत्र"> मार्कशीट / प्रमाण पत्र</label>
                        </div>
                    </div>

                    <div class="group">
                        <label for="uploadFiles">फोटो / डॉक्यूमेंट फाइलें चुनें (WhatsApp में साथ भेजने हेतु)</label>
                        <input type="file" id="uploadFiles" multiple accept="image/*,.pdf" onchange="renderFileChips()">
                        <div id="fileChips" class="file-preview"></div>
                    </div>
                </div>

                <button type="submit" class="btn-wa">📲 सेव करें और WhatsApp पर भेजें</button>
                <button type="reset" class="btn-sub" onclick="resetFormExtras()">🔄 फॉर्म साफ करें</button>

                <p class="note">
                    सबमिट करने पर विवरण सेव होगा और WhatsApp खुलेगा। कृपया WhatsApp चैट में आधार, फोटो और अन्य डॉक्यूमेंट की फोटो भी साथ भेज दें।
                </p>
            </form>
        </div>

        <div id="paneRecords" class="pane">
            <div id="recordsList"></div>
            <button type="button" class="btn-sub" onclick="copyAllFormatted()">📋 सभी रिकॉर्ड e-District फॉर्मेट में कॉपी करें</button>
            <button type="button" class="btn-sub" style="background:#fee2e2;color:#b91c1c;" onclick="clearRecords()">🗑️ सभी रिकॉर्ड मिटाएं</button>
        </div>
    </div>
</div>

<script>
    const CSC_WA_NUMBER = "919918488373";
    const STORAGE_KEY = "vaishnavi_edistrict_records_v2";

    function openTab(name) {
        const isForm = name === "form";
        document.getElementById("paneForm").classList.toggle("active", isForm);
        document.getElementById("paneRecords").classList.toggle("active", !isForm);
        document.getElementById("btnTabForm").classList.toggle("active", isForm);
        document.getElementById("btnTabRec").classList.toggle("active", !isForm);
        if (!isForm) renderRecords();
    }

    function toggleServiceHints() {
        const svc = document.getElementById("certService").value;
        const incInput = document.getElementById("annualIncome");
        if (svc.includes("आय")) {
            incInput.placeholder = "आय प्रमाण पत्र के लिए वार्षिक आय अनिवार्य (जैसे: 48000)";
        } else {
            incInput.placeholder = "जैसे: 48000 या 60000";
        }
    }

    function renderFileChips() {
        const input = document.getElementById("uploadFiles");
        const box = document.getElementById("fileChips");
        box.innerHTML = "";
        if (!input.files || !input.files.length) return;
        Array.from(input.files).forEach((f) => {
            const chip = document.createElement("span");
            chip.className = "file-chip";
            chip.textContent = "📎 " + f.name;
            box.appendChild(chip);
        });
    }

    function resetFormExtras() {
        document.getElementById("fileChips").innerHTML = "";
    }

    function loadRecords() {
        try {
            return JSON.parse(localStorage.getItem(STORAGE_KEY)) || [];
        } catch (err) {
            return [];
        }
    }

    function saveRecords(list) {
        localStorage.setItem(STORAGE_KEY, JSON.stringify(list));
        refreshCounter();
    }

    function refreshCounter() {
        document.getElementById("recCount").textContent = loadRecords().length;
    }

    function buildFormatText(d) {
        return (
            `*वैष्णवी जन सेवा केंद्र (UP e-District)*\n` +
            `====================================\n` +
            `*सेवा:* ${d.certService}\n` +
            `*दिनांक/समय:* ${d.createdAt}\n` +
            `------------------------------------\n` +
            `*आवेदक का नाम:* ${d.appName}\n` +
            `*लिंग:* ${d.gender}\n` +
            `*पिता/पति का नाम:* ${d.guardianName}\n` +
            `*माता का नाम:* ${d.momName}\n` +
            `*मोबाइल:* ${d.phoneNo} | *आधार:* ${d.aadhaarNo}\n` +
            `------------------------------------\n` +
            `*ग्राम/मोहल्ला:* ${d.village}\n` +
            `*पोस्ट:* ${d.postOffice} | *ब्लॉक:* ${d.blockArea}\n` +
            `*तहसील:* ${d.tehsil} | *जिला:* ${d.district}\n` +
            `------------------------------------\n` +
            `*जाति श्रेणी:* ${d.casteCat} (${d.casteName})\n` +
            `*वार्षिक आय:* ${d.annualIncome} | *सदस्य:* ${d.familyCount}\n` +
            `*आय के स्रोत:* ${d.incomeSources}\n` +
            `*अतिरिक्त विवरण:* ${d.extraDetails}\n` +
            `------------------------------------\n` +
            `*दस्तावेज:* ${d.docsText}\n` +
            `*चुनी फाइलें:* ${d.filesText}\n` +
            `====================================\n` +
            `_कृपया नीचे आधार कार्ड, फोटो और संबंधित डॉक्यूमेंट्स की साफ फोटो भेजें।_`
        );
    }

    function submitForm(event) {
        event.preventDefault();

        const docsChecked = Array.from(document.querySelectorAll('input[name="docsList"]:checked')).map((el) => el.value);
        const fileInput = document.getElementById("uploadFiles");
        const filesNames = fileInput.files && fileInput.files.length > 0
            ? Array.from(fileInput.files).map((f) => f.name).join(", ")
            : "कोई नहीं";

        const record = {
            id: Date.now(),
            createdAt: new Date().toLocaleString("hi-IN"),
            certService: document.getElementById("certService").value,
            appName: document.getElementById("appName").value.trim(),
            gender: document.getElementById("gender").value,
            guardianName: document.getElementById("guardianName").value.trim(),
            momName: document.getElementById("momName").value.trim(),
            phoneNo: document.getElementById("phoneNo").value.trim(),
            aadhaarNo: document.getElementById("aadhaarNo").value.trim(),
            village: document.getElementById("village").value.trim(),
            postOffice: document.getElementById("postOffice").value.trim(),
            blockArea: document.getElementById("blockArea").value.trim() || "-",
            tehsil: document.getElementById("tehsil").value.trim(),
            district: document.getElementById("district").value.trim() || "सीतापुर",
            casteCat: document.getElementById("casteCat").value,
            casteName: document.getElementById("casteName").value.trim() || "-",
            annualIncome: document.getElementById("annualIncome").value.trim() || "-",
            familyCount: document.getElementById("familyCount").value.trim() || "-",
            incomeSources: document.getElementById("incomeSources").value.trim() || "-",
            extraDetails: document.getElementById("extraDetails").value.trim() || "-",
            docsText: docsChecked.length ? docsChecked.join(", ") : "कोई चयन नहीं",
            filesText: filesNames
        };

        const list = loadRecords();
        list.unshift(record);
        saveRecords(list);

        const waMessage = buildFormatText(record);
        const waUrl = `https://wa.me/${CSC_WA_NUMBER}?text=${encodeURIComponent(waMessage)}`;
        window.open(waUrl, "_blank");
    }

    function renderRecords() {
        const container = document.getElementById("recordsList");
        const list = loadRecords();

        if (!list.length) {
            container.innerHTML = `<div class="empty">अभी कोई आवेदन रिकॉर्ड सेव नहीं है।</div>`;
            return;
        }

        container.innerHTML = list.map((r) => `
            <div class="rec-card">
                <div class="rec-head">
                    <span class="rec-badge">${esc(r.certService)}</span>
                    <div class="rec-actions">
                        <button type="button" class="btn-copy-sm" onclick="copySingle(${r.id})">कॉपी</button>
                        <button type="button" class="btn-del-sm" onclick="deleteSingle(${r.id})">हटाएं</button>
                    </div>
                </div>
                <div class="rec-details">
                    <strong>नाम:</strong> ${esc(r.appName)} (${esc(r.gender)}) | <strong>पिता/पति:</strong> ${esc(r.guardianName)}<br>
                    <strong>माता:</strong> ${esc(r.momName)} | <strong>मो.:</strong> ${esc(r.phoneNo)} | <strong>आधार:</strong> ${esc(r.aadhaarNo)}<br>
                    <strong>पता:</strong> ग्राम ${esc(r.village)}, पोस्ट ${esc(r.postOffice)}, ब्लॉक ${esc(r.blockArea)}, तहसील ${esc(r.tehsil)}, जिला ${esc(r.district)}<br>
                    <strong>जाति/आय:</strong> ${esc(r.casteCat)} (${esc(r.casteName)}) | आय: ${esc(r.annualIncome)} | सदस्य: ${esc(r.familyCount)}<br>
                    <strong>अतिरिक्त:</strong> ${esc(r.extraDetails)}<br>
                    <small style="color:#64748b;">समय: ${esc(r.createdAt)}</small>
                </div>
            </div>
        `).join("");
    }

    function copySingle(id) {
        const rec = loadRecords().find((x) => x.id === id);
        if (!rec) return;
        const plain = [
            `सेवा: ${rec.certService}`,
            `नाम: ${rec.appName} (${rec.gender})`,
            `पिता/पति: ${rec.guardianName}`,
            `माता: ${rec.momName}`,
            `मोबाइल: ${rec.phoneNo}`,
            `आधार: ${rec.aadhaarNo}`,
            `पता: ग्राम ${rec.village}, पोस्ट ${rec.postOffice}, ब्लॉक ${rec.blockArea}, तहसील ${rec.tehsil}, जिला ${rec.district}`,
            `जाति श्रेणी: ${rec.casteCat} (${rec.casteName})`,
            `वार्षिक आय: ${rec.annualIncome} | परिवार सदस्य: ${rec.familyCount}`,
            `आय के स्रोत: ${rec.incomeSources}`,
            `अतिरिक्त विवरण: ${rec.extraDetails}`
        ].join("\n");

        navigator.clipboard.writeText(plain).then(() => {
            alert("आवेदन विवरण कॉपी हो गया है। अब आप e-District फॉर्म में पेस्ट कर सकते हैं।");
        });
    }

    function deleteSingle(id) {
        const updated = loadRecords().filter((x) => x.id !== id);
        saveRecords(updated);
        renderRecords();
    }

    function copyAllFormatted() {
        const list = loadRecords();
        if (!list.length) {
            alert("कॉपी करने के लिए कोई रिकॉर्ड नहीं है।");
            return;
        }
        const combined = list.map((r, idx) => `${idx + 1}. ` + buildFormatText(r)).join("\n\n");
        navigator.clipboard.writeText(combined).then(() => {
            alert("सभी रिकॉर्ड कॉपी हो गए हैं।");
        });
    }

    function clearRecords() {
        if (confirm("क्या आप सभी रिकॉर्ड हटाना चाहते हैं?")) {
            localStorage.removeItem(STORAGE_KEY);
            refreshCounter();
            renderRecords();
        }
    }

    function esc(v) {
        return String(v)
            .replace(/&/g, "&amp;")
            .replace(/</g, "&lt;")
            .replace(/>/g, "&gt;")
            .replace(/"/g, "&quot;");
    }

    refreshCounter();
</script>

</body>
</html>
