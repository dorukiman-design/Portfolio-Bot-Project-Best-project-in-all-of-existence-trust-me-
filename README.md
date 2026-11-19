embed = discord.Embed(title="Proje Detayları")
embed.add_field(name="Proje adı", value=project_name, inline=False)
embed.add_field(name="Proje açıklaması", value=description, inline=False)
embed.add_field(name="Projenin GitHub deposuna bir bağlantı", value=url, inline=False)
embed.add_field(name="Proje durumu", value=status_name, inline=False)
embed.add_field(name="Projede kullanılan beceri", value=skills_text, inline=False)

# 2. Hazırlanan embed mesajını kanala gönder
await ctx.send(embed=embed)
