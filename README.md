message = (
    f"**Proje adı:** {project_name}\n"
    f"**Proje açıklaması:** {description}\n"
    f"**Projenin GitHub deposuna bir bağlantı:** {url}\n"
    f"**Proje durumu:** {status_name}\n"
    f"**Projede kullanılan beceri:** {skills_text}"
)

# 2. Düzenlenen mesajı Discord kanalına gönder
await ctx.send(message)
