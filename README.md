# masscan-parser
Massscan Parser
اوامر مفيدة
masscan 130.93.61.0/24 -p80,80-9000 --rate=10000 -oX result.xml -iL ip.txt      يأخد من ملف ايبيهات به رنجات
## Masscan Example:
Save masscan XML result to result.xml and run the script.
Usage example: 
```
masscan -p80 192.168.0.0/16 -oX result.xml --rate=10000
```

## Python script:
After scan, run the script ./parser.py, and you will see output.txt

## Output format: 
`<IP>:<PORT>`
