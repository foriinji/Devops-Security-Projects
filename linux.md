# Linux Kullanıcı Yönetimi ve Geçiş Komutları

# Kullanıcı Oluşturma
sudo adduser <kullanıcı_adı>
# Örneğin: sudo adduser ahmet

# Kullanıcının Gruba Eklenmesi
sudo usermod -aG <grup_adı> <kullanıcı_adı>
# Örneğin: sudo usermod -aG sudo ahmet

# Kullanıcı Silme
sudo deluser <kullanıcı_adı>
# Örneğin: sudo deluser ahmet

# Kullanıcı Şifresini Değiştirme
sudo passwd <kullanıcı_adı>
# Örneğin: sudo passwd ahmet

# Kullanıcı Bilgilerini Görüntüleme
id <kullanıcı_adı>
# Örneğin: id ahmet

# Kullanıcı Arasında Geçiş

# su Komutu
su - kullanici_adı
# Örneğin: su - ahmet

# sudo Komutu
sudo -u kullanici_adı komut
# Örneğin: sudo -u ahmet ls

# Kullanıcı Oturumunu Değiştirme

# -l seçeneğiyle
su -l kullanici_adı
# Örneğin: su -l ahmet

# --login seçeneğiyle
su --login kullanici_adı
# Örneğin: su --login ahmet