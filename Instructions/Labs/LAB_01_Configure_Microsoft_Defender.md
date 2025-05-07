---
lab:
  title: |-
    <group id="content" extype="content"><group id="paragraph-101"><trans-unit id="p101" translate="no" xml:space="preserve" restype="x-metadata">
              <source>Microsoft Defender を構成する</source>
            </trans-unit><group id="sentence-101"><trans-unit id="101" translate="yes" xml:space="preserve" restype="x-metadata">
              <source>Microsoft Defender を構成する</source>
            </trans-unit></group></group><group id="paragraph-102"><trans-unit id="p102" translate="no" xml:space="preserve">
              <source>あなたは、Microsoft Defender XDR を実装しようとしている会社で働くセキュリティ運用アナリストです。</source>
            </trans-unit><group id="sentence-102"><trans-unit id="102" translate="yes" xml:space="preserve">
              <source>あなたは、Microsoft Defender XDR を実装しようとしている会社で働くセキュリティ運用アナリストです。</source>
            </trans-unit></group></group><group id="paragraph-103"><trans-unit id="p103" translate="no" xml:space="preserve">
              <source>あなたの役割は、企業の IT チームが Microsoft Defender (XDR) を使用して脅威から防御するのをガイドすることです。</source>
            </trans-unit><group id="sentence-103"><trans-unit id="103" translate="yes" xml:space="preserve">
              <source>あなたの役割は、企業の IT チームが Microsoft Defender (XDR) を使用して脅威から防御するのをガイドすることです。</source>
            </trans-unit></group></group><group id="paragraph-104"><trans-unit id="p104" translate="no" xml:space="preserve">
              <source>会社の役員は、環境内の活動が完了したときに、すべてのガイドラインが準拠され、すべての要件が満たされることを非常に気に掛けています。</source>
            </trans-unit><group id="sentence-104"><trans-unit id="104" translate="yes" xml:space="preserve">
              <source>会社の役員は、環境内の活動が完了したときに、すべてのガイドラインが準拠され、すべての要件が満たされることを非常に気に掛けています。</source>
            </trans-unit></group></group><group id="paragraph-105"><trans-unit id="p105" translate="no" xml:space="preserve">
              <source>Microsoft Defender XDR 環境を構成する</source>
            </trans-unit><group id="sentence-105"><trans-unit id="105" translate="yes" xml:space="preserve">
              <source>Microsoft Defender XDR 環境を構成する</source>
            </trans-unit></group></group><group id="paragraph-106"><trans-unit id="p106" translate="no" xml:space="preserve">
              <source>この演習では、Microsoft Defender XDR 環境をプロビジョニングし、Defender for Endpoint でクライアント ワークステーションをオンボードし、クライアント ワークステーションでシミュレートされた攻撃シナリオを実行します。</source>
            </trans-unit><group id="sentence-106"><trans-unit id="106" translate="yes" xml:space="preserve">
              <source>この演習では、Microsoft Defender XDR 環境をプロビジョニングし、Defender for Endpoint でクライアント ワークステーションをオンボードし、クライアント ワークステーションでシミュレートされた攻撃シナリオを実行します。</source>
            </trans-unit></group></group><group id="paragraph-107"><trans-unit id="p107" translate="no" xml:space="preserve">
              <source>この演習の所要時間は約 <bpt id="p1">**</bpt>10 分から 15 分<ept id="p1">**</ept>です。</source>
            </trans-unit><group id="sentence-107"><trans-unit id="107" translate="yes" xml:space="preserve">
              <source>この演習の所要時間は約 <bpt id="p1">**</bpt>10 分から 15 分<ept id="p1">**</ept>です。</source>
            </trans-unit></group></group><group id="paragraph-108"><trans-unit id="p108" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>重要:<ept id="p1">**</ept>次の演習を実行するのに、Microsoft Defender for Endpoint P2 ライセンスのある Microsoft 365 E5 テナントにアクセスできる必要があります。</source>
            </trans-unit><group id="sentence-108"><trans-unit id="108" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>重要:<ept id="p1">**</ept>次の演習を実行するのに、Microsoft Defender for Endpoint P2 ライセンスのある Microsoft 365 E5 テナントにアクセスできる必要があります。</source>
            </trans-unit></group></group><group id="paragraph-109"><trans-unit id="p109" translate="no" xml:space="preserve">
              <source>また、シミュレートされた攻撃をオンボードして実行する Microsoft Windows 10 または 11 クライアント ワークステーションも必要です。</source>
            </trans-unit><group id="sentence-109"><trans-unit id="109" translate="yes" xml:space="preserve">
              <source>また、シミュレートされた攻撃をオンボードして実行する Microsoft Windows 10 または 11 クライアント ワークステーションも必要です。</source>
            </trans-unit></group></group><group id="paragraph-110"><trans-unit id="p110" translate="no" xml:space="preserve">
              <source>タスク 1: Microsoft Defender XDR ワークスペースの準備</source>
            </trans-unit><group id="sentence-110"><trans-unit id="110" translate="yes" xml:space="preserve">
              <source>タスク 1: Microsoft Defender XDR ワークスペースの準備</source>
            </trans-unit></group></group><group id="paragraph-111"><trans-unit id="p111" translate="no" xml:space="preserve">
              <source>Microsoft Edge ブラウザーで、Microsoft Defender ポータル (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>) に移動します。</source>
            </trans-unit><group id="sentence-111"><trans-unit id="111" translate="yes" xml:space="preserve">
              <source>Microsoft Edge ブラウザーで、Microsoft Defender ポータル (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>) に移動します。</source>
            </trans-unit></group></group><group id="paragraph-112"><trans-unit id="p112" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>Microsoft Defender<ept id="p1">**</ept> ポータルのナビゲーション メニューで、左側の <bpt id="p2">**</bpt>[ホーム]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-112"><trans-unit id="112" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>Microsoft Defender<ept id="p1">**</ept> ポータルのナビゲーション メニューで、左側の <bpt id="p2">**</bpt>[ホーム]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-113"><trans-unit id="p113" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept> メニューの一番上までスクロールする必要がある場合があります。</source>
            </trans-unit><group id="sentence-113"><trans-unit id="113" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept> メニューの一番上までスクロールする必要がある場合があります。</source>
            </trans-unit></group></group><group id="paragraph-114"><trans-unit id="p114" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[アセット]<ept id="p1">**</ept> までメニュー項目を下にスクロールして、<bpt id="p2">**</bpt>[デバイス]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-114"><trans-unit id="114" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[アセット]<ept id="p1">**</ept> までメニュー項目を下にスクロールして、<bpt id="p2">**</bpt>[デバイス]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-115"><trans-unit id="p115" translate="no" xml:space="preserve">
              <source>Defender XDR ワークスペースを展開するプロセスが開始され、<bpt id="p1">*</bpt>"読み込んで初期化しています"<ept id="p1">*</ept> というメッセージがページの上部に短い間表示されるはずで、その後コーヒー マグの画像と <bpt id="p2">**</bpt>"お待ちください。データ用の新しいスペースを準備し、それらを接続しています"<ept id="p2">**</ept> というメッセージが表示されます。</source>
            </trans-unit><group id="sentence-115"><trans-unit id="115" translate="yes" xml:space="preserve">
              <source>Defender XDR ワークスペースを展開するプロセスが開始され、<bpt id="p1">*</bpt>"読み込んで初期化しています"<ept id="p1">*</ept> というメッセージがページの上部に短い間表示されるはずで、その後コーヒー マグの画像と <bpt id="p2">**</bpt>"お待ちください。データ用の新しいスペースを準備し、それらを接続しています"<ept id="p2">**</ept> というメッセージが表示されます。</source>
            </trans-unit></group></group><group id="paragraph-116"><trans-unit id="p116" translate="no" xml:space="preserve">
              <source>完了までに約 5 分かかります。</source>
            </trans-unit><group id="sentence-116"><trans-unit id="116" translate="yes" xml:space="preserve">
              <source>完了までに約 5 分かかります。</source>
            </trans-unit></group></group><group id="paragraph-117"><trans-unit id="p117" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>次のラボに必要なため、ページを開いたままにして完了を確認してください。<ept id="p1">*</ept></source>
            </trans-unit><group id="sentence-117"><trans-unit id="117" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>次のラボに必要なため、ページを開いたままにして完了を確認してください。<ept id="p1">*</ept></source>
            </trans-unit></group></group><group id="paragraph-118"><trans-unit id="p118" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept><bpt id="p2">*</bpt> "データの一部を取得できません"<ept id="p2">*</ept> というポップアップ エラー メッセージは無視してください。</source>
            </trans-unit><group id="sentence-118"><trans-unit id="118" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept><bpt id="p2">*</bpt> "データの一部を取得できません"<ept id="p2">*</ept> というポップアップ エラー メッセージは無視してください。</source>
            </trans-unit></group></group><group id="paragraph-119"><trans-unit id="p119" translate="no" xml:space="preserve">
              <source>"お待ちください。</source>
            </trans-unit><group id="sentence-119"><trans-unit id="119" translate="yes" xml:space="preserve">
              <source>"お待ちください。</source>
            </trans-unit></group></group><group id="paragraph-120"><trans-unit id="p120" translate="no" xml:space="preserve">
              <source>データ用の新しいスペースを準備し、それらを接続しています" というメッセージが表示されない場合、または [設定] - [Microsoft Defender XDR] - [アカウント] ページを開くと <bpt id="p1">*</bpt>"データ ストレージの場所を読み込みめせんでした。後でもう一度やり直してください。"<ept id="p1">*</ept> というメッセージが表示される場合は、[全般] メニューから [アラート サービスの設定] を選択してください。</source>
            </trans-unit><group id="sentence-120"><trans-unit id="120" translate="yes" xml:space="preserve">
              <source>データ用の新しいスペースを準備し、それらを接続しています" というメッセージが表示されない場合、または [設定] - [Microsoft Defender XDR] - [アカウント] ページを開くと <bpt id="p1">*</bpt>"データ ストレージの場所を読み込みめせんでした。後でもう一度やり直してください。"<ept id="p1">*</ept> というメッセージが表示される場合は、[全般] メニューから [アラート サービスの設定] を選択してください。</source>
            </trans-unit></group></group><group id="paragraph-121"><trans-unit id="p121" translate="no" xml:space="preserve">
              <source>新しいワークスペースの初期化が正常に完了すると、<bpt id="p1">**</bpt>[ホーム]<ept id="p1">**</ept> ポータル ページに <bpt id="p2">**</bpt>"SIEM と XDR を 1 か所で取得する"<ept id="p2">**</ept> というバナーが表示されます。</source>
            </trans-unit><group id="sentence-121"><trans-unit id="121" translate="yes" xml:space="preserve">
              <source>新しいワークスペースの初期化が正常に完了すると、<bpt id="p1">**</bpt>[ホーム]<ept id="p1">**</ept> ポータル ページに <bpt id="p2">**</bpt>"SIEM と XDR を 1 か所で取得する"<ept id="p2">**</ept> というバナーが表示されます。</source>
            </trans-unit></group></group><group id="paragraph-122"><trans-unit id="p122" translate="no" xml:space="preserve">
              <source>また、<bpt id="p1">**</bpt>[設定]<ept id="p1">**</ept> において、アカウント、電子メール通知、<bpt id="p2">**</bpt>プレビュー機能<ept id="p2">**</ept>、アラート サービスの設定、アクセス許可とロール、ストリーミング API の Microsoft Defender XDR 全般設定が有効になります。</source>
            </trans-unit><group id="sentence-122"><trans-unit id="122" translate="yes" xml:space="preserve">
              <source>また、<bpt id="p1">**</bpt>[設定]<ept id="p1">**</ept> において、アカウント、電子メール通知、<bpt id="p2">**</bpt>プレビュー機能<ept id="p2">**</ept>、アラート サービスの設定、アクセス許可とロール、ストリーミング API の Microsoft Defender XDR 全般設定が有効になります。</source>
            </trans-unit></group></group><group id="paragraph-123"><trans-unit id="p123" translate="no" xml:space="preserve">
              <source>タスク 2: Microsoft Defender for Office 365 の事前設定されたセキュリティ ポリシーを適用する</source>
            </trans-unit><group id="sentence-123"><trans-unit id="123" translate="yes" xml:space="preserve">
              <source>タスク 2: Microsoft Defender for Office 365 の事前設定されたセキュリティ ポリシーを適用する</source>
            </trans-unit></group></group><group id="paragraph-124"><trans-unit id="p124" translate="no" xml:space="preserve">
              <source>このタスクでは、Microsoft 365 セキュリティ ポータルで、Exchange Online Protection (EOP) と Microsoft Defender for Office 365 の事前設定されたセキュリティ ポリシーを割り当てます。</source>
            </trans-unit><group id="sentence-124"><trans-unit id="124" translate="yes" xml:space="preserve">
              <source>このタスクでは、Microsoft 365 セキュリティ ポータルで、Exchange Online Protection (EOP) と Microsoft Defender for Office 365 の事前設定されたセキュリティ ポリシーを割り当てます。</source>
            </trans-unit></group></group><group id="paragraph-125"><trans-unit id="p125" translate="no" xml:space="preserve">
              <source>パスワード <bpt id="p1">**</bpt>Pa55w.rd<ept id="p1">**</ept> を使用して、管理者として WIN1 仮想マシンにログインします。</source>
            </trans-unit><group id="sentence-125"><trans-unit id="125" translate="yes" xml:space="preserve">
              <source>パスワード <bpt id="p1">**</bpt>Pa55w.rd<ept id="p1">**</ept> を使用して、管理者として WIN1 仮想マシンにログインします。</source>
            </trans-unit></group></group><group id="paragraph-126"><trans-unit id="p126" translate="no" xml:space="preserve">
              <source>Microsoft Edge ブラウザーを起動します。</source>
            </trans-unit><group id="sentence-126"><trans-unit id="126" translate="yes" xml:space="preserve">
              <source>Microsoft Edge ブラウザーを起動します。</source>
            </trans-unit></group></group><group id="paragraph-127"><trans-unit id="p127" translate="no" xml:space="preserve">
              <source>Microsoft Edge ブラウザーで、Microsoft Defender XDR ポータル (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>) にアクセスします。</source>
            </trans-unit><group id="sentence-127"><trans-unit id="127" translate="yes" xml:space="preserve">
              <source>Microsoft Edge ブラウザーで、Microsoft Defender XDR ポータル (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>) にアクセスします。</source>
            </trans-unit></group></group><group id="paragraph-128"><trans-unit id="p128" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[サインイン]<ept id="p1">**</ept> ダイアログ ボックスで、ラボ ホスティング プロバイダーから提供された管理者ユーザー名のテナント電子メール アカウントをコピーして貼り付け、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-128"><trans-unit id="128" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[サインイン]<ept id="p1">**</ept> ダイアログ ボックスで、ラボ ホスティング プロバイダーから提供された管理者ユーザー名のテナント電子メール アカウントをコピーして貼り付け、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-129"><trans-unit id="p129" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[パスワードの入力]<ept id="p1">**</ept> ダイアログ ボックスで、ラボ ホスティング プロバイダーから提供された管理者のテナント パスワードをコピーして貼り付け、<bpt id="p2">**</bpt>[サインイン]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-129"><trans-unit id="129" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[パスワードの入力]<ept id="p1">**</ept> ダイアログ ボックスで、ラボ ホスティング プロバイダーから提供された管理者のテナント パスワードをコピーして貼り付け、<bpt id="p2">**</bpt>[サインイン]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-130"><trans-unit id="p130" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept> "操作を完了できませんでした。</source>
            </trans-unit><group id="sentence-130"><trans-unit id="130" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept> "操作を完了できませんでした。</source>
            </trans-unit></group></group><group id="paragraph-131"><trans-unit id="p131" translate="no" xml:space="preserve">
              <source>後でもう一度やり直してください。</source>
            </trans-unit><group id="sentence-131"><trans-unit id="131" translate="yes" xml:space="preserve">
              <source>後でもう一度やり直してください。</source>
            </trans-unit></group></group><group id="paragraph-132"><trans-unit id="p132" translate="no" xml:space="preserve">
              <source>問題が解決しない場合は、Microsoft サポートにお問い合わせください。"</source>
            </trans-unit><group id="sentence-132"><trans-unit id="132" translate="yes" xml:space="preserve">
              <source>問題が解決しない場合は、Microsoft サポートにお問い合わせください。"</source>
            </trans-unit></group></group><group id="paragraph-133"><trans-unit id="p133" translate="no" xml:space="preserve">
              <source> というメッセージが表示された場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept> をクリックすれば続行できます。</source>
            </trans-unit><group id="sentence-133"><trans-unit id="133" translate="yes" xml:space="preserve">
              <source> というメッセージが表示された場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept> をクリックすれば続行できます。</source>
            </trans-unit></group></group><group id="paragraph-134"><trans-unit id="p134" translate="no" xml:space="preserve">
              <source>表示されている場合は、Microsoft Defender XDR クイック ツアーのポップアップ ウィンドウを閉じます。</source>
            </trans-unit><group id="sentence-134"><trans-unit id="134" translate="yes" xml:space="preserve">
              <source>表示されている場合は、Microsoft Defender XDR クイック ツアーのポップアップ ウィンドウを閉じます。</source>
            </trans-unit></group></group><group id="paragraph-135"><trans-unit id="p135" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept> このラボの後半で、Defender ワークスペースがプロビジョニングされるまで待つ必要があります。この間にガイド付きツアーにアクセスして、Microsoft Defender XDR の詳細を学習することができます。</source>
            </trans-unit><group id="sentence-135"><trans-unit id="135" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept> このラボの後半で、Defender ワークスペースがプロビジョニングされるまで待つ必要があります。この間にガイド付きツアーにアクセスして、Microsoft Defender XDR の詳細を学習することができます。</source>
            </trans-unit></group></group><group id="paragraph-136"><trans-unit id="p136" translate="no" xml:space="preserve">
              <source>ナビゲーション メニューの <bpt id="p1">*</bpt>[メールとコラボレーション]<ept id="p1">*</ept> 領域で、<bpt id="p2">**</bpt>[ポリシーとルール]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-136"><trans-unit id="136" translate="yes" xml:space="preserve">
              <source>ナビゲーション メニューの <bpt id="p1">*</bpt>[メールとコラボレーション]<ept id="p1">*</ept> 領域で、<bpt id="p2">**</bpt>[ポリシーとルール]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-137"><trans-unit id="p137" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[ポリシーとルール]<ept id="p1">*</ept> ダッシュボードで、<bpt id="p2">**</bpt>[脅威ポリシー]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-137"><trans-unit id="137" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[ポリシーとルール]<ept id="p1">*</ept> ダッシュボードで、<bpt id="p2">**</bpt>[脅威ポリシー]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-138"><trans-unit id="p138" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[脅威ポリシー]<ept id="p1">*</ept> ダッシュボードで、<bpt id="p2">**</bpt>[事前設定されたセキュリティ ポリシー]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-138"><trans-unit id="138" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[脅威ポリシー]<ept id="p1">*</ept> ダッシュボードで、<bpt id="p2">**</bpt>[事前設定されたセキュリティ ポリシー]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-139"><trans-unit id="p139" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept>"クライアント エラー - bip ルールの取得時にエラーが発生しました"<bpt id="p2">*</bpt> というメッセージが表示された場合は、<ept id="p2">*</ept><bpt id="p3">**</bpt>[OK]<ept id="p3">**</ept> を選択して続行してください。</source>
            </trans-unit><group id="sentence-139"><trans-unit id="139" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept>"クライアント エラー - bip ルールの取得時にエラーが発生しました"<bpt id="p2">*</bpt> というメッセージが表示された場合は、<bpt id="p3">**</bpt>[OK]<ept id="p3">**</ept> を選択して続行してください。<ept id="p2">*</ept></source>
            </trans-unit></group></group><group id="paragraph-140"><trans-unit id="p140" translate="no" xml:space="preserve">
              <source>このエラーは、既定では有効になっていない Office 365 のテナントのハイドレーション状態が原因です。</source>
            </trans-unit><group id="sentence-140"><trans-unit id="140" translate="yes" xml:space="preserve">
              <source>このエラーは、既定では有効になっていない Office 365 のテナントのハイドレーション状態が原因です。</source>
            </trans-unit></group></group><group id="paragraph-141"><trans-unit id="p141" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept> "クライアント エラー - 事前設定されたセキュリティ ポリシーの取得時にエラーが発生しました。後でもう一度やり直してください。"<bpt id="p2">*</bpt><ept id="p2">*</ept></source>
            </trans-unit><group id="sentence-141"><trans-unit id="141" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept>"クライアント エラー - 事前設定されたセキュリティ ポリシーの取得時にエラーが発生しました。後でもう一度やり直してください。"<bpt id="p2">*</bpt><ept id="p2">*</ept></source>
            </trans-unit></group></group><group id="paragraph-142"><trans-unit id="p142" translate="no" xml:space="preserve">
              <source> というメッセージが表示される場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept> を選択すると続行します。</source>
            </trans-unit><group id="sentence-142"><trans-unit id="142" translate="yes" xml:space="preserve">
              <source> というメッセージが表示される場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept> を選択すると続行します。</source>
            </trans-unit></group></group><group id="paragraph-143"><trans-unit id="p143" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>Ctrl + F5<ept id="p1">**</ept> キーを使用してブラウザーを更新してください。</source>
            </trans-unit><group id="sentence-143"><trans-unit id="143" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>Ctrl + F5<ept id="p1">**</ept> キーを使用してブラウザーを更新してください。</source>
            </trans-unit></group></group><group id="paragraph-144"><trans-unit id="p144" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[事前設定されたセキュリティ ポリシーについて]<ept id="p1">**</ept><bpt id="p2">*</bpt> ポップアウト<ept id="p2">*</ept> ページで、<bpt id="p3">**</bpt>[閉じる]<ept id="p3">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-144"><trans-unit id="144" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>[事前設定されたセキュリティ ポリシーについて]<ept id="p1">**</ept><bpt id="p2">*</bpt> ポップアウト<ept id="p2">*</ept> ページで、<bpt id="p3">**</bpt>[閉じる]<ept id="p3">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-145"><trans-unit id="p145" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[標準保護]<ept id="p1">*</ept> で、<bpt id="p2">**</bpt>[保護設定を管理する]<ept id="p2">**</ept> 選択します。</source>
            </trans-unit><group id="sentence-145"><trans-unit id="145" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[標準保護]<ept id="p1">*</ept> で、<bpt id="p2">**</bpt>[保護設定を管理する]<ept id="p2">**</ept> 選択します。</source>
            </trans-unit></group></group><group id="paragraph-146"><trans-unit id="p146" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept> このオプションが淡色表示されている場合は、<bpt id="p2">**</bpt>Ctrl + F5<ept id="p2">**</ept> キーを使用してブラウザーを更新します。</source>
            </trans-unit><group id="sentence-146"><trans-unit id="146" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept> このオプションが淡色表示されている場合は、<bpt id="p2">**</bpt>Ctrl + F5<ept id="p2">**</ept> キーを使用してブラウザーを更新します。</source>
            </trans-unit></group></group><group id="paragraph-147"><trans-unit id="p147" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Exchange Online Protection を適用する]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[特定の受信者]<ept id="p2">**</ept> を選択し、<bpt id="p3">**</bpt>[ドメイン]<ept id="p3">**</ept> の下でテナントのドメイン名を一部入力して表示されたものを選択し、<bpt id="p4">**</bpt>[次へ]<ept id="p4">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-147"><trans-unit id="147" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Exchange Online Protection を適用する]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[特定の受信者]<ept id="p2">**</ept> を選択し、<bpt id="p3">**</bpt>[ドメイン]<ept id="p3">**</ept> の下でテナントのドメイン名を一部入力して表示されたものを選択し、<bpt id="p4">**</bpt>[次へ]<ept id="p4">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-148"><trans-unit id="p148" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept> テナントのドメイン名は管理者アカウントの名前と同じで、<bpt id="p2">*</bpt>WWLx######.onmicrosoft.com<ept id="p2">*</ept> のようになります。</source>
            </trans-unit><group id="sentence-148"><trans-unit id="148" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept> テナントのドメイン名は管理者アカウントの名前と同じで、<bpt id="p2">*</bpt>WWLx######.onmicrosoft.com<ept id="p2">*</ept> のようになります。</source>
            </trans-unit></group></group><group id="paragraph-149"><trans-unit id="p149" translate="no" xml:space="preserve">
              <source>この構成では、スパム対策、送信スパム フィルター、マルウェア対策、フィッシング対策のポリシーが適用されることに注意してください。</source>
            </trans-unit><group id="sentence-149"><trans-unit id="149" translate="yes" xml:space="preserve">
              <source>この構成では、スパム対策、送信スパム フィルター、マルウェア対策、フィッシング対策のポリシーが適用されることに注意してください。</source>
            </trans-unit></group></group><group id="paragraph-150"><trans-unit id="p150" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Defender for Office 365 保護を適用する]<ept id="p1">*</ept> セクションで、前の手順と同じ構成を適用し、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-150"><trans-unit id="150" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Defender for Office 365 保護を適用する]<ept id="p1">*</ept> セクションで、前の手順と同じ構成を適用し、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-151"><trans-unit id="p151" translate="no" xml:space="preserve">
              <source>この構成では、フィッシング対策、安全な添付ファイル、安全なリンクのポリシーが適用されることに注意してください。</source>
            </trans-unit><group id="sentence-151"><trans-unit id="151" translate="yes" xml:space="preserve">
              <source>この構成では、フィッシング対策、安全な添付ファイル、安全なリンクのポリシーが適用されることに注意してください。</source>
            </trans-unit></group></group><group id="paragraph-152"><trans-unit id="p152" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[偽装保護]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を 4 回選択して次に進みます。</source>
            </trans-unit><group id="sentence-152"><trans-unit id="152" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[偽装保護]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を 4 回選択して次に進みます。</source>
            </trans-unit></group></group><group id="paragraph-153"><trans-unit id="p153" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[ポリシー モード]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[完了時にポリシーを有効にする]<ept id="p2">**</ept> ラジオ ボタンが選択されていることを確認し、<bpt id="p3">**</bpt>[次へ]<ept id="p3">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-153"><trans-unit id="153" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[ポリシー モード]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[完了時にポリシーを有効にする]<ept id="p2">**</ept> ラジオ ボタンが選択されていることを確認し、<bpt id="p3">**</bpt>[次へ]<ept id="p3">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-154"><trans-unit id="p154" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[変更を確認して確定する]<ept id="p1">*</ept> の下の内容を読み、<bpt id="p2">**</bpt>[確定]<ept id="p2">**</ept> を選択して変更を適用し、<bpt id="p3">**</bpt>[完了]<ept id="p3">**</ept> を選択して終了します。</source>
            </trans-unit><group id="sentence-154"><trans-unit id="154" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[変更を確認して確定する]<ept id="p1">*</ept> の下の内容を読み、<bpt id="p2">**</bpt>[確定]<ept id="p2">**</ept>を選択して変更を適用し、<bpt id="p3">**</bpt>[完了]<ept id="p3">**</ept> を選択して終了します。</source>
            </trans-unit></group></group><group id="paragraph-155"><trans-unit id="p155" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept><bpt id="p2">*</bpt> "URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' は PUT 操作に対して無効です。PUT 操作では、URI は、1 つのリソースを URI で参照する必要があります。"<ept id="p2">*</ept></source>
            </trans-unit><group id="sentence-155"><trans-unit id="155" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept><bpt id="p2">*</bpt> "URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' は PUT 操作に対して無効です。PUT 操作では、URI は、1 つのリソースを URI で参照する必要があります。"<ept id="p2">*</ept></source>
            </trans-unit></group></group><group id="paragraph-156"><trans-unit id="p156" translate="no" xml:space="preserve">
              <source>というメッセージが表示された場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept>、<bpt id="p2">**</bpt>[キャンセル]<ept id="p2">**</ept> の順に選択して、メイン ページに戻ってください。</source>
            </trans-unit><group id="sentence-156"><trans-unit id="156" translate="yes" xml:space="preserve">
              <source> というメッセージが表示された場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept>、<bpt id="p2">**</bpt>[キャンセル]<ept id="p2">**</ept> の順に選択して、メイン ページに戻ってください。</source>
            </trans-unit></group></group><group id="paragraph-157"><trans-unit id="p157" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[標準保護が有効になっている]<ept id="p1">*</ept> オプションが有効になっていることがわかります。</source>
            </trans-unit><group id="sentence-157"><trans-unit id="157" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[標準保護が有効になっている]<ept id="p1">*</ept> オプションが有効になっていることがわかります。</source>
            </trans-unit></group></group><group id="paragraph-158"><trans-unit id="p158" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[厳格な保護]<ept id="p1">*</ept> で、<bpt id="p2">**</bpt>[保護設定を管理する]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-158"><trans-unit id="158" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[厳格な保護]<ept id="p1">*</ept> で、<bpt id="p2">**</bpt>[保護設定を管理する]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-159"><trans-unit id="p159" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept><bpt id="p2">*</bpt> [厳格な保護]<ept id="p2">*</ept> は、[メールとコラボレーション] - [ポリシーとルール] - [脅威ポリシー] - [事前設定されたセキュリティ ポリシー] にあります。</source>
            </trans-unit><group id="sentence-159"><trans-unit id="159" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>ヒント:<ept id="p1">**</ept><bpt id="p2">*</bpt> [厳格な保護]<ept id="p2">*</ept> は、[メールとコラボレーション] - [ポリシーとルール] - [脅威ポリシー] - [事前設定されたセキュリティ ポリシー] にあります。</source>
            </trans-unit></group></group><group id="paragraph-160"><trans-unit id="p160" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Exchange Online Protection を適用する]<ept id="p1">*</ept> で、<bpt id="p2">**</bpt>[特定の受信者]<ept id="p2">**</ept> を選択し、<bpt id="p3">**</bpt>[グループ]<ept id="p3">**</ept> の下の <bpt id="p4">**</bpt>[リーダーシップ]<ept id="p4">**</ept> に一部入力して表示されたものをを選択して、<bpt id="p5">**</bpt>[次へ]<ept id="p5">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-160"><trans-unit id="160" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Exchange Online Protection を適用する]<ept id="p1">*</ept>で、<bpt id="p2">**</bpt>[特定の受信者]<ept id="p2">**</ept> を選択し、<bpt id="p3">**</bpt>[グループ]<ept id="p3">**</ept> の下の <bpt id="p4">**</bpt>[リーダーシップ]<ept id="p4">**</ept> に一部入力して表示されたものをを選択して、<bpt id="p5">**</bpt>[次へ]<ept id="p5">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-161"><trans-unit id="p161" translate="no" xml:space="preserve">
              <source>この構成では、スパム対策、送信スパム フィルター、マルウェア対策、フィッシング対策のポリシーが適用されることに注意してください。</source>
            </trans-unit><group id="sentence-161"><trans-unit id="161" translate="yes" xml:space="preserve">
              <source>この構成では、スパム対策、送信スパム フィルター、マルウェア対策、フィッシング対策のポリシーが適用されることに注意してください。</source>
            </trans-unit></group></group><group id="paragraph-162"><trans-unit id="p162" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Defender for Office 365 保護を適用する]<ept id="p1">*</ept> セクションで、前の手順と同じ構成を適用し、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-162"><trans-unit id="162" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[Defender for Office 365 保護を適用する]<ept id="p1">*</ept> セクションで、前の手順と同じ構成を適用し、 <bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-163"><trans-unit id="p163" translate="no" xml:space="preserve">
              <source>この構成では、フィッシング対策、安全な添付ファイル、安全なリンクのポリシーが適用されることに注意してください。</source>
            </trans-unit><group id="sentence-163"><trans-unit id="163" translate="yes" xml:space="preserve">
              <source>この構成では、フィッシング対策、安全な添付ファイル、安全なリンクのポリシーが適用されることに注意してください。</source>
            </trans-unit></group></group><group id="paragraph-164"><trans-unit id="p164" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[偽装保護]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を 4 回選択して次に進みます。</source>
            </trans-unit><group id="sentence-164"><trans-unit id="164" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[偽装保護]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[次へ]<ept id="p2">**</ept> を 4 回選択して次に進みます。</source>
            </trans-unit></group></group><group id="paragraph-165"><trans-unit id="p165" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[ポリシー モード]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[完了時にポリシーを有効にする]<ept id="p2">**</ept> ラジオ ボタンが選択されていることを確認し、<bpt id="p3">**</bpt>[次へ]<ept id="p3">**</ept> を選択します。</source>
            </trans-unit><group id="sentence-165"><trans-unit id="165" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[ポリシー モード]<ept id="p1">*</ept> セクションで、<bpt id="p2">**</bpt>[完了時にポリシーを有効にする]<ept id="p2">**</ept> ラジオ ボタンが選択されていることを確認し、<bpt id="p3">**</bpt>[次へ]<ept id="p3">**</ept> を選択します。</source>
            </trans-unit></group></group><group id="paragraph-166"><trans-unit id="p166" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[変更を確認して確定する]<ept id="p1">*</ept><bpt id="p2"> の下の内容を読み、**</bpt>[確定]<ept id="p2">**</ept> を選択して変更を適用し、<bpt id="p3">**</bpt>[完了]<ept id="p3">**</ept> を選択して終了します。</source>
            </trans-unit><group id="sentence-166"><trans-unit id="166" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[変更を確認して確定する]<ept id="p1">*</ept><bpt id="p2"> の下の内容を読み、**</bpt>[確定]<ept id="p2">**</ept> を選択して変更を適用し、<bpt id="p3">**</bpt>[完了]<ept id="p3">**</ept> を選択して終了します。</source>
            </trans-unit></group></group><group id="paragraph-167"><trans-unit id="p167" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept><bpt id="p2">*</bpt> "URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' は PUT 操作に対して無効です。PUT 操作では、URI は、1 つのリソースを URI で参照する必要があります。"<ept id="p2">*</ept></source>
            </trans-unit><group id="sentence-167"><trans-unit id="167" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>注:<ept id="p1">**</ept><bpt id="p2">*</bpt> "URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' は PUT 操作に対して無効です。PUT 操作では、URI は、1 つのリソースを URI で参照する必要があります。"<ept id="p2">*</ept></source>
            </trans-unit></group></group><group id="paragraph-168"><trans-unit id="p168" translate="no" xml:space="preserve">
              <source> というメッセージが表示された場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept>、<bpt id="p2">**</bpt>[キャンセル]<ept id="p2">**</ept> の順に選択して、メイン ページに戻ってください。</source>
            </trans-unit><group id="sentence-168"><trans-unit id="168" translate="yes" xml:space="preserve">
              <source> というメッセージが表示された場合は、<bpt id="p1">**</bpt>[OK]<ept id="p1">**</ept>、<bpt id="p2">**</bpt>[キャンセル]<ept id="p2">**</ept> の順に選択して、メイン ページに戻ってください。</source>
            </trans-unit></group></group><group id="paragraph-169"><trans-unit id="p169" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[厳格な保護がオンになっている]<ept id="p1">*</ept> オプションが有効になっていることがわかります。</source>
            </trans-unit><group id="sentence-169"><trans-unit id="169" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>[厳格な保護がオンになっている]<ept id="p1">*</ept> オプションが有効になっていることがわかります。</source>
            </trans-unit></group></group><group id="paragraph-170"><trans-unit id="p170" translate="no" xml:space="preserve">
              <source>ラボは以上です</source>
            </trans-unit><group id="sentence-170"><trans-unit id="170" translate="yes" xml:space="preserve">
              <source>ラボは以上です</source>
            </trans-unit></group></group></group>
  module: Configure the Microsoft Defender XDR environment
---
You're a Security Operations Analyst working at a company that is implementing Microsoft Defender XDR. Your role is to guide the company’s IT team in defending against threats with Microsoft Defender (XDR). The company’s executives are very concerned that all guidelines are followed and that all requirements are met when you complete the activities in their environment.

# Configure the Microsoft Defender XDR environment

In this exercise you will provision your Microsoft Defender XDR environment, onboard client workstations in Defender for Endpoint and perform a simulated attack scenario on a client workstation.

This exercise should take approximately <bpt id="p1">**</bpt>10 - 15<ept id="p1">**</ept> minutes to complete.

><bpt id="p1">**</bpt>Important:<ept id="p1">**</ept> You'll need to have access to a Microsoft 365 E5 Tenant with a Microsoft Defender for Endpoint P2 license to perform the following exercises. You will also need to have Microsoft Windows 10 or 11 client workstations to onboard and perform simulated attacks on.

## Task 1- Preparing the Microsoft Defender XDR workspace

1. In the Microsoft Edge browser, go to the Microsoft Defender portal at (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>).
1. On the <bpt id="p1">**</bpt>Microsoft Defender<ept id="p1">**</ept> portal, from the navigation menu, select <bpt id="p2">**</bpt>Home<ept id="p2">**</ept> from the left.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> You may need to scroll all the way to the menu top.

1. Scroll down the menu items to <bpt id="p1">**</bpt>Assets<ept id="p1">**</ept> and select <bpt id="p2">**</bpt>Devices<ept id="p2">**</ept>.

1. The process to deploy the Defender XDR workspace should start and you should see messages saying <bpt id="p1">*</bpt>loading and Initializing<ept id="p1">*</ept> briefly displayed at the top of the page, and then you're going to see an image of a coffee mug and a message that reads: <bpt id="p2">**</bpt>Hang on! We're preparing new spaces for your data and connecting them.<ept id="p2">**</ept> It takes approximately 5 minutes to finish. <bpt id="p1">*</bpt>Leave the page open and make sure it finishes since it's required for the next Lab.<ept id="p1">*</ept>

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> Disregard pop-up error messages saying <bpt id="p2">*</bpt>Some of your data cannot be retrieved<ept id="p2">*</ept>. If the message "Hang on! We're preparing new spaces for your data and connecting them" does not appear, or the "Settings &gt; Microsoft Defender XDR &gt; Account" page opens, but you see the message <bpt id="p1">*</bpt>Failed to load data storage location. Please try again later<ept id="p1">*</ept>, select "Alert service settings" from the "General" menu.

1. When the new workspace initialization completes successfully, the <bpt id="p1">**</bpt>Home<ept id="p1">**</ept> portal page will display a <bpt id="p2">**</bpt>Get your SIEM and XDR in one place<ept id="p2">**</ept> banner. And, in <bpt id="p1">**</bpt>Settings<ept id="p1">**</ept>, the Microsoft Defender XDR General settings for Account, Email notifications, <bpt id="p2">**</bpt>Preview Features<ept id="p2">**</ept>, Alert service settings, Permissions and roles and Streaming API are now turned on.

### Task 2: Apply Microsoft Defender for Office 365 preset security policies

In this task, you'll assign preset security policies for Exchange Online Protection (EOP) and Microsoft Defender for Office 365 in the Microsoft 365 security portal.

1. Log in to WIN1 virtual machine as Admin with the password: <bpt id="p1">**</bpt>Pa55w.rd<ept id="p1">**</ept>.  

1. Start the Microsoft Edge browser.

1. In the Microsoft Edge browser, go to the Microsoft Defender XDR portal at (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>).

1. In the <bpt id="p1">**</bpt>Sign in<ept id="p1">**</ept> dialog box, copy, and paste in the tenant Email account for the admin username provided by your lab hosting provider and then select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept>.

1. In the <bpt id="p1">**</bpt>Enter password<ept id="p1">**</ept> dialog box, copy, and paste in the admin's tenant password provided by your lab hosting provider and then select <bpt id="p2">**</bpt>Sign in<ept id="p2">**</ept>.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive a message "The operation could not be completed. Please try again later. If the problem persists, contact Microsoft support." just click <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> to continue.  

1. If shown, close the Microsoft Defender XDR quick tour pop-up window. <bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> Later in this lab, you'll need to wait until the Defender workspace is provisioned, you can take this time to navigate through the guided tours to learn more about Microsoft Defender XDR.

1. From the navigation menu, under <bpt id="p1">*</bpt>Email &amp; Collaboration<ept id="p1">*</ept> area, select <bpt id="p2">**</bpt>Policies &amp; rules<ept id="p2">**</ept>.

1. On the <bpt id="p1">*</bpt>Policy &amp; rules<ept id="p1">*</ept> dashboard, select <bpt id="p2">**</bpt>Threat policies<ept id="p2">**</ept>.

1. On the <bpt id="p1">*</bpt>Threat policies<ept id="p1">*</ept> dashboard, select <bpt id="p2">**</bpt>Preset Security Policies<ept id="p2">**</ept>.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"Client Error - Error when getting bip rule"<ept id="p2">*</ept> select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept> to continue. The error is due to the hydration status of your tenant at Office 365 which is not enabled by default.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"Client Error - An error occurred when retrieving preset security policies. Please try again later."<ept id="p2">*</ept> select <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> to continue. Refresh your browser using <bpt id="p1">**</bpt>Ctrl+F5<ept id="p1">**</ept>.

1. On the <bpt id="p1">**</bpt>Learn about preset security policies<ept id="p1">**</ept> <bpt id="p2">*</bpt>pop-out<ept id="p2">*</ept> page, select <bpt id="p3">**</bpt>Close<ept id="p3">**</ept>.

1. Under <bpt id="p1">*</bpt>Standard protection<ept id="p1">*</ept>, select <bpt id="p2">**</bpt>Manage protection settings<ept id="p2">**</ept>. <bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> If you see this option grayed out, refresh your browser using <bpt id="p2">**</bpt>Ctrl+F5<ept id="p2">**</ept>.

1. In the <bpt id="p1">*</bpt>Apply Exchange Online Protection<ept id="p1">*</ept> section, select <bpt id="p2">**</bpt>Specific recipients<ept id="p2">**</ept> and under <bpt id="p3">**</bpt>Domains<ept id="p3">**</ept> start writing your tenant's domain name, select it, and then select <bpt id="p4">**</bpt>Next<ept id="p4">**</ept>.

    ><bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> Your tenant's domain name is the same name that you have for your admin account, it might be something like <bpt id="p2">*</bpt>WWLx######.onmicrosoft.com<ept id="p2">*</ept>. Notice that this configuration applies policies for anti-spam, outbound spam filter, anti-malware, anti-phishing.

1. In the <bpt id="p1">*</bpt>Apply Defender for Office 365 protection<ept id="p1">*</ept> section, apply the same configuration as the previous step and select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept>. Notice that this configuration applies policies for anti-phishing, Safe Attachments, Safe Links.

1. In the <bpt id="p1">*</bpt>Impersonation protection<ept id="p1">*</ept> section, select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept> four times (4x) to continue.

1. In the <bpt id="p1">*</bpt>Policy mode<ept id="p1">*</ept> section, make sure the <bpt id="p2">**</bpt>Turn on the policy when finished<ept id="p2">**</ept> radio button is selected, and then select <bpt id="p3">**</bpt>Next<ept id="p3">**</ept>.

1. Read the content under <bpt id="p1">*</bpt>Review and confirm your changes<ept id="p1">*</ept> and select <bpt id="p2">**</bpt>Confirm<ept id="p2">**</ept> to apply the changes and then select <bpt id="p3">**</bpt>Done<ept id="p3">**</ept> to finish.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"The URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' is not valid for PUT operation. The URI must point to a single resource for PUT operations."<ept id="p2">*</ept> just select <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> and then select <bpt id="p2">**</bpt>Cancel<ept id="p2">**</ept> to return to the main page. You will see that <bpt id="p1">*</bpt>Standard protection is on<ept id="p1">*</ept> option enabled.

1. Under <bpt id="p1">*</bpt>Strict protection<ept id="p1">*</ept>, select <bpt id="p2">**</bpt>Manage protection settings<ept id="p2">**</ept>. <bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> <bpt id="p2">*</bpt>Strict protection<ept id="p2">*</ept> is found under "Email &amp; Collaboration - Policies &amp; rules - Threat policies - Preset security policies".

1. In the <bpt id="p1">*</bpt>Apply Exchange Online Protection<ept id="p1">*</ept>, select <bpt id="p2">**</bpt>Specific recipients<ept id="p2">**</ept> and under <bpt id="p3">**</bpt>Groups<ept id="p3">**</ept> start writing <bpt id="p4">**</bpt>Leadership<ept id="p4">**</ept>, select it, and then select <bpt id="p5">**</bpt>Next<ept id="p5">**</ept>. Notice that this configuration applies policies for anti-spam, outbound spam filter, anti-malware, anti-phishing.

1. In the <bpt id="p1">*</bpt>Apply Defender for Office 365 protection<ept id="p1">*</ept> section, apply the same configuration as the previous step and select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept>. Notice that this configuration applies policies for anti-phishing, Safe Attachments, Safe Links.

1. In the <bpt id="p1">*</bpt>Impersonation protection<ept id="p1">*</ept> section, select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept> four times (4x) to continue.

1. In the <bpt id="p1">*</bpt>Policy mode<ept id="p1">*</ept> section, make sure the <bpt id="p2">**</bpt>Turn on the policy when finished<ept id="p2">**</ept> radio button is selected, and then select <bpt id="p3">**</bpt>Next<ept id="p3">**</ept>.

1. Read the content under <bpt id="p1">*</bpt>Review and confirm your changes<ept id="p1">*</ept> and select <bpt id="p2">**</bpt>Confirm<ept id="p2">**</ept> to apply the changes and then select <bpt id="p3">**</bpt>Done<ept id="p3">**</ept> to finish.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"The URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' is not valid for PUT operation. The URI must point to a single resource for PUT operations."<ept id="p2">*</ept> just select <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> and then select <bpt id="p2">**</bpt>Cancel<ept id="p2">**</ept> to return to the main page. You will see the <bpt id="p1">*</bpt>Strict protection is on<ept id="p1">*</ept> option enabled.

## You have completed the lab
