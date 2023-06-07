# Blog

Este e um blog criado no curso de python de Otávio Miranda.

# Comando para gerar SECRET_KEY
python -c "import string as s;from secrets import SystemRandom as SR;print(''.join(SR().choices(s.ascii_letters + s.digits + s.punctuation, k=64)));"