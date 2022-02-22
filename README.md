duration = int(input("Duration:"))
if duration < 60:
    print(duration, "сек")
elif duration < 3600:
    print(duration // 60, 'мин', duration % 60, 'сек')
elif duration < 3600 * 24:
    print(duration // 3600, 'час', duration % 3600 // 60, 'мин', duration % 60, 'сек')

