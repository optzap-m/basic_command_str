// Моё решение
cat logs/access.log | grep "denied wrong" | sort -r | head -5

// Решение учителя
grep 'denied wrong password' logs/access.log | sort -r | head -n 5