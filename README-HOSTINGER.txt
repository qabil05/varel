VAREL v15.7 — Hostinger

ZIP-in daxilindəkiləri public_html qovluğuna çıxarın.
Əvvəl mövcud saytın ehtiyat nüsxəsini saxlayın, sonra index.html və assets daxil olmaqla faylları yeniləyin.
index.html birbaşa public_html daxilində olmalıdır. Node.js və ayrıca build lazım deyil.
Hostinger cache-ni təmizləyin, brauzerdə səhifəni yeniləyin.

Düzəlişlər:
- Son seçim düymələri yalnız son bölmədə aktivdir; digər bölmələrə toxunanda restart baş vermir.
- Mobil detal baxışı hər girişdə 01-dən başlayır.
- Saat seçimi VAREL keçidini dərhal başladır; örtük açıldıqdan sonra saat dəyişir və səhifə başa qayıdır.
- İkiqat klik təkrar restart başlatmır.
- İlk yüklənmə üçün HTML daxilindəki VAREL ekranı saxlanılıb.

Yoxlama: TypeScript və production build uğurlu; 390x844 mobil və desktop brauzerində detal/son seçim keçidləri yoxlanılıb.
