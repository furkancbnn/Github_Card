# Github_Card

![](GİthubPr.gif)

**GitHub Kullanıcı Bilgisi ve Repositories Çekme Uygulaması**

Bu JavaScript dosyası, GitHub API kullanarak belirli bir kullanıcının bilgilerini ve depolarını çeken bir web uygulamasını oluşturur. İlgili GitHub projesi için sade ve açıklayıcı bir açıklama aşağıdaki gibi olabilir:

**GitHub Proje Açıklaması:**

Bu proje, GitHub API kullanarak belirli bir kullanıcının profil bilgilerini çeker ve bu bilgileri kullanıcı dostu bir kart arayüzünde görüntüler. Aynı zamanda, kullanıcının en son depolarını da listeler.

- **JavaScript Kodu:**
  - `getUser` fonksiyonu: Kullanıcı adını parametre olarak alır, GitHub API'sine istek gönderir ve kullanıcının bilgilerini çeker. Ardından, bu bilgileri göstermek için `createUserCard` fonksiyonunu çağırır ve aynı zamanda `getRepos` fonksiyonunu çağırarak kullanıcının depolarını çeker.
  - `createUserCard` fonksiyonu: Kullanıcının bilgilerini içeren bir HTML kartını oluşturur ve bu kartı sayfada görüntüler.
  - `createErrorCard` fonksiyonu: Hata durumunda kullanıcıya gösterilecek bir HTML kartı oluşturur ve sayfada görüntüler.
  - `getRepos` fonksiyonu: Kullanıcının depolarını çeker ve bu depoları göstermek için `addReposToCard` fonksiyonunu çağırır.
  - `addReposToCard` fonksiyonu: Kullanıcının depolarını içeren bir HTML listesini oluşturur ve sayfada görüntüler.

- **HTML Yapısı:**
  - Kullanıcı adını girmek için bir form.
  - Kullanıcının bilgilerini göstermek ve depolarını listelemek için bir ana bölme (`<main>`).
  - Kullanıcının bilgilerini ve depolarını göstermek için bir kart yapısı.

- **Kullanılan Teknolojiler:**
  - Axios kütüphanesi (HTTP istekleri için).
  - GitHub API.

Projeyi kullanmak için:
1. GitHub API anahtarınızı kullanım başına sınırlamalara göre ekleyin.
2. Web sayfasını tarayıcıda açın.
3. Arama çubuğuna bir GitHub kullanıcı adı yazın ve "Ara" butonuna tıklayın.

Bu proje, belirli bir GitHub kullanıcısının profil bilgilerini ve depolarını hızlıca çekmek ve görüntülemek isteyenler için basit ve kullanıcı dostu bir arayüz sağlar.
