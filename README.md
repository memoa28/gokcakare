&amp;lt;!DOCTYPE html&amp;gt;
&amp;lt;html lang=&amp;quot;tr&amp;quot;&amp;gt;
&amp;lt;head&amp;gt;
    &amp;lt;meta charset=&amp;quot;UTF-8&amp;quot;&amp;gt;
    &amp;lt;title&amp;gt;PROJECT GÖKÇAKAR-CIWS // OFFICIAL R&amp;amp;D PANEL&amp;lt;/title&amp;gt;
    &amp;lt;style&amp;gt;
        body {
            background-color: #050d08;
            color: #33ff33;
            font-family: &amp;#039;Courier New&amp;#039;, Courier, monospace;
            padding: 40px;
            margin: 0;
            overflow-x: hidden;
        }
        .hud-border {
            border: 2px solid #33ff33;
            padding: 20px;
            box-shadow: 0 0 15px rgba(51, 255, 51, 0.2);
            background: rgba(5, 13, 8, 0.8);
        }
        h1 {
            text-align: center;
            letter-spacing: 4px;
            text-shadow: 0 0 10px #33ff33;
            margin-bottom: 5px;
        }
        .subtitle {
            text-align: center;
            color: #88ff88;
            font-size: 14px;
            margin-bottom: 30px;
        }
        .matrix-text {
            font-size: 16px;
            line-height: 1.6;
            white-space: pre-line;
        }
        .status-panel {
            border-top: 1px solid #33ff33;
            margin-top: 30px;
            padding-top: 15px;
            font-size: 12px;
            color: #88ff88;
        }
    &amp;lt;/style&amp;gt;
&amp;lt;/head&amp;gt;
&amp;lt;body&amp;gt;

&amp;lt;div class=&amp;quot;hud-border&amp;quot;&amp;gt;
    &amp;lt;h1&amp;gt;PROJECT GÖKÇAKAR - CIWS&amp;lt;/h1&amp;gt;
    &amp;lt;div class=&amp;quot;subtitle&amp;quot;&amp;gt;AUTONOMOUS CLOSE-IN WEAPON SYSTEM // RECON PROTOCOL v4.0&amp;lt;/div&amp;gt;
    
    &amp;lt;div class=&amp;quot;matrix-text&amp;quot;&amp;gt;
        [SYS_STATUS]: ACTIVE // ALL SYSTEMS OPERATIONAL
        [DEVELOPER]: MEHMET EMRE AKTEN
        [MISSION_SECTOR]: BULANCAK FEN R&amp;amp;D LAB
        -------------------------------------------------------------
        Sistem tamamen asenkron durum makinesi (State Machine) mimarisiyle, millis() saat döngüsü tabanlı çalışmaktadır. 
        
        Sensor Fusion (Çift Kilit) Karar Mekanizması sayesinde, HC-SR04 ultrasonik mesafe verileri ile Analog LDR optik filtre verileri tek bir saniyede işlenerek hedefe kilitlenme (Target Tracking) ve önleme açısı (Lead Angle) h
