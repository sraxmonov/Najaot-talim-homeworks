# Najaot-talim-homeworks
# Sonlar ro‘yxati berilgan.
# map()` va `lambda` yordamida har bir sonni 3 ga ko‘paytiring.



# ismlar = ["Alisher", "Valilisher", "Sanjarbek", "Abdulloh"]

# uzunliklar = list(map(len, ismlar))

# print(uzunliklar)

# ---------------------------------------------------------------------------

# Sonlar ro‘yxatidan `map()` orqali
# har bir sonning kvadratini hisoblang.


# sonlar = [2, 4, 34, 23, 12, 23, 56]
# kvadrati = list(map(lambda x:x**2, sonlar))

# print(kvadrati)



# ---------------------------------------------------------------------------

# 3.

# Berilgan satrlar ro‘yxatida
# `map()` yordamida har bir satrni katta harflarga o‘tkazing.

# satrlar = ["O'zbekiston", "Toshkent", "Bu kitob", "dasturlash"]
# katta_harf = list(map(str.upper, satrlar))
# print(katta_harf)


# ---------------------------------------------------------------------------

# 4
# Ismlar ro‘yxatidan `map()` orqali
# har bir ismning uzunligini hisoblang.

# ismlar = ["Alisher", "Valilisher", "Sanjarbek", "Abdulloh", "Otabek"]
# ism_uzunligi = list(map(len, ismlar))
# print(ism_uzunligi)


# ---------------------------------------------------------------------------

# 5
# Sonlar ro‘yxatida `map()` yordamida
# manfiy sonlarni musbatga aylantiring (`abs` ishlatilmasin).


# sonlar = [-23, -3, -56, 8, -12, -46, -34, -27, -58, -19]
# musbatga = list(map(lambda x : -x if x<0 else x, sonlar))
# print(musbatga)

# ---------------------------------------------------------------------------

# 6
# narxlar ro‘yxati berilgan.
# `map()` orqali har bir narxga 15% qo‘shilgan holatini hisoblang.

# narxlar = [12_000, 10_000, 25_000, 8_000]
# yangi_narxlar = list(map(lambda x: x*1.15, narxlar))

# print(yangi_narxlar)

# ---------------------------------------------------------------------------

# 7

# Sonlar ro‘yxatida `map()` yordamida
# juft sonlarni 0 ga, toq sonlarni esa o‘z holicha qoldiring.


# sonlar = [23, 3, 56, 8, 12, 46, 34, 27, 58, 19]
# natija =list (map(lambda x: 0 if x%2 == 0 else x, sonlar))
# print(natija)

# ---------------------------------------------------------------------------
#8

# Satrlar ro‘yxatida `map()` orqali
# har bir satr oxiriga `!` belgisi qo‘shing.

# satrlar = ["O'zbekiston", "Toshkent", "Bu kitob", "dasturlash"]
# natija = list(map(lambda x: x + "!", satrlar))
# print(natija)

# ---------------------------------------------------------------------------
#9

# Sonlar ro‘yxatidan `filter()` yordamida
# faqat juft sonlarni ajrating.

# sonlar = [23, 3, 56, 8, 12, 46, 34, 27, 58, 19]
# juft = list(filter(lambda x: x % 2 ==0, sonlar))
# print(juft)

# ---------------------------------------------------------------------------

#10
# Sonlar ro‘yxatidan
# 0 dan katta bo‘lgan sonlarni `filter()` bilan oling.

# sonlar = [23, 3, -56, 8, -12, 46, 34, 27, -58, 19]
# natija = list(filter(lambda x : x > 0 ,sonlar))
# print(natija)

# ---------------------------------------------------------------------------

#11

# Satrlar ro‘yxatidan
# uzunligi 5 ta belgidan katta bo‘lgan so‘zlarni ajrating.

# satrlar = ["O'zbekiston", "Toshkent", "Bu kitob", "dasturlash", "Salom"]
# natija = list(filter(lambda x :len(x) > 5, satrlar))

# print(natija)

# ---------------------------------------------------------------------------
#12

# Sonlar ro‘yxatidan `filter()` yordamida
# 5 ga bo‘linadigan sonlarni tanlab oling.

# sonlar = [23, 3, 55, 8, 12, 45, 34, 25, 58, 19]
# natija = list(filter(lambda x:x%5 ==0 , sonlar))

# print(natija)


# ---------------------------------------------------------------------------

#13
# Ismlar ro‘yxatidan
# `A` harfi bilan boshlanadigan ismlarni ajrating.

# ismlar = ["Alisher", "Valilisher", "Sanjarbek", "Abdulloh", "Otabek"]

# natija = list(filter(lambda x: x.startswith("A"), ismlar))

# print(natija)

# ---------------------------------------------------------------------------

#14
#
# Sonlar ro‘yxatidan
# manfiy bo‘lmagan (0 va musbat) sonlarni `filter()` bilan oling.

# sonlar = [23, -3, 55, 8, 12, -45, 34, 25, -58, 19]
# natija = list(filter(lambda x: x > 0, sonlar ))
# print(natija)

# ---------------------------------------------------------------------------

#15


# Satrlar ro‘yxatidan
# ichida `python` so‘zi bor bo‘lgan satrlarni `filter()` orqali toping.

satrlar = ["O'zbekiston", "Toshkent", "Bu kitob", "dasturlash", "Salom"]
natija = list(filter(lambda x: "python" in x.lower(), satrlar))
print(natija)
