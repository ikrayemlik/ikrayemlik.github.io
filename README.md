# İkra Yemlik — Portfolio

Türkçe ve İngilizce kişisel portfolyo. HTML, CSS ve JavaScript kullanır; kurulum veya derleme gerektirmez.

## Bilgisayarda açma

`index.html` dosyasına çift tıklayın. VS Code içinde düzenlemek için bu klasörü açın. İsterseniz Live Server eklentisi ile çalıştırın.

Python yüklüyse klasörde terminal açıp `python -m http.server 8000` çalıştırın ve `http://localhost:8000` adresine gidin.

## Dosyalar

- `index.html`: sayfanın başlangıcı ve metaveriler.
- `style.css`: koyu tema ve responsive yerleşim.
- `app.js`: Türkçe/İngilizce içerikler, projeler ve dil geçişi.
- `ikra-yemlik-cv.pdf`: indirilebilir Türkçe CV.
- `.nojekyll`: GitHub Pages üzerinde dosyaları doğrudan sunmak için.

## GitHub Pages

1. `ikrayemlik.github.io` adlı repository oluşturun.
2. Bu klasörün dosyalarını repository köküne yükleyin.
3. Settings → Pages → Build and deployment → Deploy from a branch.
4. Branch: `main`, Folder: `/ (root)` seçip Save’e basın.
5. Pages ayarlarında başarılı yayın adresini kontrol edin. Beklenen adres: `https://ikrayemlik.github.io`.

Ücretsiz kişisel hesapta GitHub Pages için public repository kullanın. Yayınlanan web sitesi herkese açıktır.

## Saklama ve değişiklikler

GitHub kodların sürüm geçmişini tutar. Bilgisayarınızda bu klasörün bir kopyasını ve ZIP yedeğini saklayabilirsiniz. Google Drive veya OneDrive’a da yedekleyebilirsiniz.

Site metinleri ve proje bilgileri `app.js` içinde `content.tr`, `content.en` ve `projects` alanlarından düzenlenir. Renkler `style.css` dosyasındaki `:root` alanındadır.

GitHub Pages üzerinden çalıştırmak için ChatGPT’nin açık olması gerekmez. Dosyalar düz statik dosyalardır; uygulamaya özel bir çalışma bağımlılığı yoktur. Google Fonts için internet bağlantısı gerekir; çevrimdışı durumda sistem yazı tipi kullanılır.

## English

A bilingual Turkish/English static portfolio. Open `index.html` locally or serve the folder using `python -m http.server 8000`. Edit `app.js` for content and `style.css` for styling. Publish the root directory with GitHub Pages; the included CV is in Turkish.
