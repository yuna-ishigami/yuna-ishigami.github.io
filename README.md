<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MFプロダクト領域2Qキックオフアンケート分析報告書</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Lucide Icons for visual enhancements -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5;
            color: #333;
        }
        .container {
            max-width: 960px;
            margin: 40px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
        }
        .section-title {
            font-size: 1.875rem; /* 30px */
            font-weight: 700;
            color: #2c3e50;
            margin-bottom: 20px;
            border-bottom: 3px solid #e74c3c;
            padding-bottom: 10px;
        }
        .subsection-title {
            font-size: 1.5rem; /* 24px */
            font-weight: 600;
            color: #34495e;
            margin-top: 30px;
            margin-bottom: 15px;
        }
        .category-title {
            font-size: 1.25rem; /* 20px */
            font-weight: 600;
            color: #e74c3c;
            margin-top: 20px;
            margin-bottom: 10px;
        }
        .good-point, .bad-point, .next-point {
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 15px;
            line-height: 1.6;
        }
        .good-point {
            background-color: #e6ffe6; /* Light green */
            border-left: 5px solid #27ae60; /* Green */
        }
        .bad-point {
            background-color: #ffe6e6; /* Light red */
            border-left: 5px solid #c0392b; /* Red */
        }
        .next-point {
            background-color: #e6f7ff; /* Light blue */
            border-left: 5px solid #3498db; /* Blue */
        }
        /* Removed .chart-container, .bar, .bar-label, .bar-value, .bar-title styles */
        .summary-card {
            background-color: #fdfdfd;
            border: 1px solid #e0e0e0;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            display: flex;
            align-items: flex-start;
            gap: 15px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
        }
        .summary-card-icon {
            flex-shrink: 0;
            color: #e74c3c;
        }
        .summary-card-content h4 {
            font-weight: 700;
            color: #2c3e50;
            margin-bottom: 5px;
        }
        .summary-card-content p {
            font-size: 0.95rem;
            color: #555;
        }
        .suggestion-item {
            display: flex;
            align-items: flex-start;
            gap: 10px;
            margin-bottom: 15px;
        }
        .suggestion-icon {
            flex-shrink: 0;
            color: #3498db;
            margin-top: 4px; /* Align icon with text */
        }
        .suggestion-text strong {
            color: #e74c3c; /* Highlight key phrases */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="section-title">MFプロダクト領域2Qキックオフアンケート分析報告書</h1>

        <div class="mb-8">
            <h2 class="subsection-title">サマリ</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <div class="summary-card">
                    <i data-lucide="award" class="summary-card-icon w-8 h-8"></i>
                    <div class="summary-card-content">
                        <h4>キックオフ目的</h4>
                        <p>①前期表彰案件の共有の理解促進、表彰者の称賛。</p>
                        <p>②当期戦略（VPメッセージ）の理解深化。</p>
                    </div>
                </div>
                <div class="summary-card">
                    <i data-lucide="bar-chart-2" class="summary-card-icon w-8 h-8"></i>
                    <div class="summary-card-content">
                        <h4>全体評価</h4>
                        <p>キックオフ全体の満足度: <span class="font-bold text-red-600">4.24 / 5.00</span></p>
                        <p>VPメッセージ理解度: <span class="font-bold text-red-600">4.41 / 5.00</span></p>
                    </div>
                </div>
                <div class="summary-card">
                    <i data-lucide="video" class="summary-card-icon w-8 h-8"></i>
                    <div class="summary-card-content">
                        <h4>高評価ポイント</h4>
                        <p>動画クオリティの向上とスムーズな運営が特に好評であった。</p>
                    </div>
                </div>
                <div class="summary-card">
                    <i data-lucide="lightbulb" class="summary-card-icon w-8 h-8"></i>
                    <div class="summary-card-content">
                        <h4>改善提案</h4>
                        <p>新人・異動者紹介の内容充実、表彰案件の具体的な深掘りに関する要望が挙がっている。</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- 数値評価の可視化セクションを削除 -->

        <h2 class="subsection-title">詳細フィードバック分析</h2>

        <div class="mb-8">
            <h3 class="category-title">1. キックオフ全体の満足度</h3>
            <div class="good-point">
                <p class="font-bold text-green-700 mb-2">Good（良かった点）</p>
                <ul class="list-disc list-inside">
                    <li>動画クオリティが大幅に向上し、コンテンツが聞き取りやすくなった。</li>
                    <li>スムーズな運営と適切な時間配分で視聴しやすかった。</li>
                    <li>録画視聴が可能であった点が好評であった。</li>
                    <li>画面越しでも熱量が伝わり、多くの気づきと刺激があった。</li>
                    <li>他部署の取り組みを知る良い機会となった。</li>
                </ul>
            </div>
            <div class="bad-point">
                <p class="font-bold text-red-700 mb-2">Bad（改善が必要な点 - 明示的な不満点）</p>
                <ul class="list-disc list-inside">
                    <li>特になし。</li>
                </ul>
            </div>
            <div class="next-point">
                <p class="font-bold text-blue-700 mb-2">Next（次回の改善点・要望）</p>
                <ul class="list-disc list-inside">
                    <li>動画にタイムスタンプを付けてほしい。</li>
                    <li>新人・異動者向けに、表彰案件の前提となるプロジェクト概要説明を補足してほしい。</li>
                    <li>表彰案件の具体的な内容（何をやったのか）をより詳細に知りたい。</li>
                </ul>
            </div>
        </div>

        <div class="mb-8">
            <h3 class="category-title">2. 新任＆異動者紹介パート</h3>
            <div class="good-point">
                <p class="font-bold text-green-700 mb-2">Good（良かった点）</p>
                <ul class="list-disc list-inside">
                    <li>新メンバーについて楽しく知ることができ、ボリューム感も適切であった。</li>
                    <li>司会者のコメントが温かく、雰囲気が良かった。</li>
                </ul>
            </div>
            <div class="bad-point">
                <p class="font-bold text-red-700 mb-2">Bad（改善が必要な点 - 明示的な不満点）</p>
                <ul class="list-disc list-inside">
                    <li>特になし。</li>
                </ul>
            </div>
            <div class="next-point">
                <p class="font-bold text-blue-700 mb-2">Next（次回の改善点・要望）</p>
                <ul class="list-disc list-inside">
                    <li>日程調整や拠点都合もあって難しいのは重々承知の上であるが、対象者がご自身で話す方が人となりが一発で掴めて良い。</li>
                </ul>
            </div>
        </div>

        <div class="mb-8">
            <h3 class="category-title">3. VPメッセージ（中西VP＆森VPのお話）</h3>
            <div class="good-point">
                <p class="font-bold text-green-700 mb-2">Good（良かった点）</p>
                <ul class="list-disc list-inside">
                    <li>内容が非常に分かりやすく、プロジェクト外のメンバーにも簡潔に伝わった。</li>
                    <li>森VPの「変わるのは怖い、変わらないのはもっと怖い」というメッセージが心に響いた。</li>
                    <li>「お届けゼクシィ」の具体的な話が分かりやすく、ローンチへの期待が高まった。</li>
                    <li>既存の強みを土台に新しい価値を築く組織の一員として、業務への意欲が高まった。</li>
                    <li>動画クオリティの向上により、メッセージの本気度と伝わり方が向上した。</li>
                    <li>CSの記録だけでなく記憶に残る体験への進化、ブランドへの変化にワクワクした。</li>
                </ul>
            </div>
            <div class="bad-point">
                <p class="font-bold text-red-700 mb-2">Bad（改善が必要な点 - 明示的な不満点）</p>
                <ul class="list-disc list-inside">
                    <li>特になし。</li>
                </ul>
            </div>
            <div class="next-point">
                <p class="font-bold text-blue-700 mb-2">Next（次回の改善点・要望）</p>
                <ul class="list-disc list-inside">
                    <li>「お届けゼクシィ」の具体的な定量的な効果見込みについて知りたい。</li>
                    <li>「お届けゼクシィ」の地域限定提供に関する救済措置（例：首都圏在住だが地元で式を挙げる場合）について質問があった。</li>
                    <li>「お届けゼクシィ」のリリースに伴う不安や、カスタマーの戸惑いへの対応策について、知恵を出し合いながら育てていきたい。</li>
                </ul>
            </div>
        </div>

        <div class="mt-10 pt-5 border-t border-gray-300">
            <h2 class="subsection-title">結論と今後のキックオフへの提言</h2>
            <p class="text-gray-700 leading-relaxed">
                今回のキックオフは、動画クオリティの向上とスムーズな運営により、参加者から高い満足度とVPメッセージへの理解度が得られたことが確認された。特に「お届けゼクシィ」に関する具体的な説明は、多くの参加者の関心を引き、今後の展開への期待を高めている。
            </p>
            <p class="text-gray-700 leading-relaxed mt-2">
                次回のキックオフをさらに質の高いものにするためには、以下の点を考慮することをお勧めする。
            </p>
            <div class="mt-5">
                <div class="suggestion-item">
                    <i data-lucide="trending-up" class="suggestion-icon w-6 h-6"></i>
                    <p class="suggestion-text"><strong>表彰案件の深掘り</strong>: 表彰された案件について、その背景、具体的な取り組み内容、成果をより詳細に共有する時間や資料を設けることで、社員の戦略への理解と自身の業務への応用を促進できるだろう。新人社員向けに、前提となるプロジェクトの概要説明を補足することも有効である。</p>
                </div>
                <div class="suggestion-item">
                    <i data-lucide="user-plus" class="suggestion-icon w-6 h-6"></i>
                    <p class="suggestion-text"><strong>新人・異動者紹介の個別化</strong>: 可能であれば、新人や異動者自身が短い時間でも直接自己紹介する機会を設けることで、より個人の「人となり」を伝えることができ、エンゲージメントの向上に繋がる可能性がある。録画での自己紹介も有効な手段である。</p>
                </div>
                <div class="suggestion-item">
                    <i data-lucide="message-square" class="suggestion-icon w-6 h-6"></i>
                    <p class="suggestion-text"><strong>VPメッセージの補足情報</strong>: VPメッセージについては高い理解度を示しているが、具体的な施策（例: お届けゼクシィ）の定量的な効果見込みや、具体的な顧客影響に関する補足情報を提供することで、さらなる理解の深化と業務への接続を促すことができると考えられる。また、個別の質問にも対応できるようなQ&Aセッションや、参照資料の提供なども検討すると良いだろう。</p>
                </div>
            </div>
            <p class="text-gray-700 leading-relaxed mt-4">
                これらの改善点を踏まえることで、ゼクシィ事業のキックオフが、より戦略への理解を深め、社員のエンゲージメントを高める場となることを期待する。
            </p>
        </div>
    </div>
    <script>
        // Initialize Lucide icons
        lucide.createIcons();
    </script>
</body>
</html>
