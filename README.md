# HackerRank-Marks-Average
Python-Skript zur Berechnung des Notendurchschnitts von Schülern aus einer Liste, basierend auf einer HackerRank-Challenge. Ausgabe mit zwei Dezimalstellen.

# 1️⃣ Neues Git-Repository erstellen (Falls noch nicht geschehen)
git init

# 2️⃣ Repository mit einem Namen festlegen (Falls noch nicht geschehen)
git remote add origin https://github.com/DEIN-GITHUB-NAME/hackerrank-student-marks-average.git

# 3️⃣ README-Datei mit der Beschreibung erstellen
echo "# 🎓 HackerRank: Student Marks Average

## 📝 Beschreibung
Dieses Python-Skript löst die **HackerRank-Challenge** zur Berechnung des Durchschnitts von Schülernoten.

## 🚀 Problemstellung
- Das Programm liest eine Liste von Schülernamen und deren Noten ein.
- Es speichert die Daten in einem **Dictionary**.
- Anschließend berechnet es den **Durchschnitt der Noten eines bestimmten Schülers**.
- Das Ergebnis wird **mit zwei Dezimalstellen** ausgegeben.

## 📌 Beispiel-Eingabe:
\`\`\`
3
Krishna 67 68 69
Arjun 70 98 63
Malika 52 56 60
Malika
\`\`\`

## 📌 Beispiel-Ausgabe:
\`\`\`
56.00
\`\`\`

## 💡 Lösung in Python
\`\`\`python
if __name__ == '__main__':
    n = int(input())
    student_marks = {}
    for _ in range(n):
        data = input().split()
        name = data[0]
        marks = list(map(float, data[1:]))
        student_marks[name] = marks
    query_name = input()
    average = sum(student_marks[query_name]) / len(student_marks[query_name])
    print(f'{average:.2f}')
\`\`\`

## 🛠 Technologien
- **Python 3**
- **Dictionary & Listen**
- **String-Splitting & \`map()\`**
- **Grundlegende Mathematik (Durchschnittsberechnung)**

## 📜 Lizenz
Dieses Projekt steht unter der **MIT License**.
" > README.md

# 4️⃣ Datei zu Git hinzufügen
git add README.md

# 5️⃣ Erste Commit-Nachricht setzen
git commit -m "Initial commit: HackerRank Student Marks Average Lösung hinzugefügt"

# 6️⃣ Datei in das GitHub-Repository hochladen
git branch -M main
git push -u origin main
