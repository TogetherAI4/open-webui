# Open WebUI (Früher Ollama WebUI) 👋

![GitHub Sterne](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
![GitHub Forks](https://img.shields.io/github/forks/open-webui/open-webui?style=social)
![GitHub Beobachter](https://img.shields.io/github/watchers/open-webui/open-webui?style=social)
![GitHub Repository Größe](https://img.shields.io/github/repo-size/open-webui/open-webui)
![GitHub Sprachenanzahl](https://img.shields.io/github/languages/count/open-webui/open-webui)
![GitHub Top-Sprache](https://img.shields.io/github/languages/top/open-webui/open-webui)
![GitHub letzter Commit](https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Follama-webui%2Follama-wbui&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

Open WebUI ist eine [erweiterbare](https://github.com/open-webui/pipelines), funktionsreiche und benutzerfreundliche selbstgehostete WebUI, die vollständig offline betrieben werden kann. Sie unterstützt verschiedene LLM-Runner, darunter Ollama- und OpenAI-kompatible APIs. Weitere Informationen findest du in unserer [Open WebUI-Dokumentation](https://docs.openwebui.com/).

![Open WebUI Demo](./demo.gif)

## Hauptmerkmale von Open WebUI ⭐

- 🚀 **Mühelose Einrichtung**: Installiere nahtlos über Docker oder Kubernetes (kubectl, kustomize oder helm) für eine problemlose Erfahrung mit Unterstützung für `:ollama`- und `:cuda`-getaggte Images.

- 🤝 **Ollama/OpenAI API-Integration**: Integriere mühelos OpenAI-kompatible APIs für vielseitige Konversationen neben Ollama-Modellen. Passe die OpenAI API-URL an, um sie mit **LMStudio, GroqCloud, Mistral, OpenRouter und mehr** zu verknüpfen.

- 🧩 **Pipelines, Open WebUI Plugin-Support**: Integriere benutzerdefinierte Logik und Python-Bibliotheken nahtlos in Open WebUI mit dem [Pipelines Plugin Framework](https://github.com/open-webui/pipelines). Starte deine Pipelines-Instanz, setze die OpenAI-URL auf die Pipelines-URL und erkunde endlose Möglichkeiten. [Beispiele](https://github.com/open-webui/pipelines/tree/main/examples) umfassen **Function Calling**, Benutzer-**Rate-Limiting** zur Zugriffssteuerung, **Nutzungsüberwachung** mit Tools wie Langfuse, **Live-Übersetzung mit LibreTranslate** für mehrsprachige Unterstützung, **Filterung toxischer Nachrichten** und vieles mehr.

- 📱 **Responsive Design**: Genieße ein nahtloses Erlebnis auf Desktop-PCs, Laptops und Mobilgeräten.

- 📱 **Progressive Web App (PWA) für Mobilgeräte**: Genieße ein naturnahes App-Erlebnis auf deinem Mobilgerät mit unserer PWA, die Offline-Zugriff auf localhost und eine nahtlose Benutzeroberfläche bietet.

- ✒️🔢 **Vollständige Markdown- und LaTeX-Unterstützung**: Hebe dein LLM-Erlebnis mit umfassender Markdown- und LaTeX-Unterstützung für eine bereicherte Interaktion auf eine neue Stufe.

- 🎤📹 **Freihändige Sprach-/Videoanrufe**: Erlebe nahtlose Kommunikation mit integrierten freihändigen Sprach- und Videoanruffunktionen, die eine dynamischere und interaktivere Chat-Umgebung ermöglichen.

- 🛠️ **Modell-Builder**: Erstelle Ollama-Modelle mühelos über die Web-Oberfläche. Erstelle und füge benutzerdefinierte Charaktere/Agenten hinzu, passe Chatelemente an und importiere Modelle problemlos über die Integration der [Open WebUI Community](https://openwebui.com/).

- 🐍 **Native Python-Funktionsaufrufe**: Erweitere deine LLMs mit eingebauter Unterstützung für Code-Editoren im Tool-Workspace. Bring Your Own Function (BYOF) einfach durch Hinzufügen deiner reinen Python-Funktionen und ermögliche nahtlose Integration mit LLMs.

- 📚 **Lokale RAG-Integration**: Tauche ein in die Zukunft der Chat-Interaktionen mit bahnbrechender Retrieval Augmented Generation (RAG)-Unterstützung. Diese Funktion integriert Dokumenteninteraktionen nahtlos in dein Chaterlebnis. Du kannst Dokumente direkt in den Chat laden oder Dateien zu deiner Dokumentenbibliothek hinzufügen und sie mühelos mit dem `#`-Befehl vor einer Abfrage abrufen.

- 🔍 **Websuche für RAG**: Führe Websuchen mit Anbietern wie `SearXNG`, `Google PSE`, `Brave Search`, `serpstack`, `serper`, `Serply`, `DuckDuckGo` und `TavilySearch` durch und füge die Ergebnisse direkt in dein Chaterlebnis ein.

- 🌐 **Web-Browsing-Funktion**: Integriere nahtlos Websites in dein Chaterlebnis mit dem `#`-Befehl gefolgt von einer URL. Diese Funktion ermöglicht es dir, Webinhalte direkt in deine Gespräche einzubinden, was die Reichhaltigkeit und Tiefe deiner Interaktionen erhöht.

- 🎨 **Bildgenerierungs-Integration**: Integriere nahtlos Bildgenerierungsfunktionen mit Optionen wie AUTOMATIC1111 API oder ComfyUI (lokal) und OpenAI's DALL-E (extern) und bereichere dein Chaterlebnis mit dynamischen visuellen Inhalten.

- ⚙️ **Vielzahl von Modell-Konversationen**: Führe mühelos Gespräche mit verschiedenen Modellen gleichzeitig, nutze deren einzigartige Stärken für optimale Antworten. Verbessere dein Erlebnis, indem du eine vielfältige Auswahl an Modellen parallel einsetzt.

- 🔐 **Rollenbasierte Zugriffssteuerung (RBAC)**: Stelle sicheren Zugriff mit eingeschränkten Berechtigungen sicher; nur autorisierte Personen können auf dein Ollama zugreifen, und exklusive Rechte zur Modellerstellung/zum Modellzugriff sind Administratoren vorbehalten.

- 🌐🌍 **Mehrsprachige Unterstützung**: Erlebe Open WebUI in deiner bevorzugten Sprache mit unserer Internationalisierungsunterstützung (i18n). Schließe dich uns an, um unsere unterstützten Sprachen zu erweitern! Wir suchen aktiv nach Mitwirkenden!

- 🌟 **Kontinuierliche Updates**: Wir sind bestrebt, Open WebUI mit regelmäßigen Updates, Fehlerbehebungen und neuen Funktionen zu verbessern.

Möchtest du mehr über die Funktionen von Open WebUI erfahren? Schaue dir unsere [Open WebUI-Dokumentation](https://docs.openwebui.com/features) für einen umfassenden Überblick an!

## 🔗 Sieh dir auch die Open WebUI Community an!

Vergiss nicht, unser Schwesterprojekt, die [Open WebUI Community](https://openwebui.com/), zu erkunden, wo du benutzerdefinierte Modelfiles entdecken, herunterladen und erkunden kannst. Die Open WebUI Community bietet eine breite Palette aufregender Möglichkeiten, um deine Chat-Interaktionen mit Open WebUI zu verbessern! 🚀

## So installierst du 🚀

> [!HINWEIS]  
> Bitte beachte, dass für bestimmte Docker-Umgebungen zusätzliche Konfigurationen erforderlich sein können. Wenn du auf Verbindungsprobleme stößt, steht dir unser detaillierter Leitfaden in der [Open WebUI-Dokumentation](https://docs.openwebui.com/) zur Verfügung.

### Schneller Start mit Docker 🐳

> [!WARNUNG]
> Wenn du Docker verwendest, um Open WebUI zu installieren, achte darauf, das `-v open-webui:/app/backend/data` in deinem Docker-Befehl einzuschließen. Dieser Schritt ist entscheidend, da er sicherstellt, dass deine Datenbank ordnungsgemäß eingebunden ist und Datenverluste verhindert werden.

> [!TIPP]  
> Wenn du Open WebUI mit eingeschlossenem Ollama oder CUDA-Beschleunigung nutzen möchtest, empfehlen wir die Verwendung unserer offiziellen Images, die entweder mit `:cuda` oder `:ollama` getaggt sind. Um CUDA zu aktivieren, musst du das [Nvidia CUDA-Container-Toolkit](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/) auf deinem Linux-/WSL-System installieren.

### Installation mit Standardkonfiguration

- **Wenn Ollama auf deinem Computer installiert ist**, verwende diesen Befehl:

  ```bash
  docker run

 -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **Wenn Ollama auf einem anderen Server installiert ist**, verwende diesen Befehl:

  Um eine Verbindung zu Ollama auf einem anderen Server herzustellen, ändere die `OLLAMA_BASE_URL` auf die URL des Servers:

  ```bash
  docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

  - **Um Open WebUI mit Nvidia GPU-Unterstützung auszuführen**, verwende diesen Befehl:

  ```bash
  docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:cuda
  ```

### Installation für die ausschließliche Nutzung der OpenAI API

- **Wenn du nur die OpenAI API verwendest**, verwende diesen Befehl:

  ```bash
  docker run -d -p 3000:8080 -e OPENAI_API_KEY=dein_geheimer_schlüssel -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

### Installation von Open WebUI mit gebündelter Ollama-Unterstützung

Diese Installationsmethode verwendet ein einzelnes Container-Image, das Open WebUI mit Ollama bündelt, um eine vereinfachte Einrichtung über einen einzigen Befehl zu ermöglichen. Wähle den passenden Befehl basierend auf deiner Hardwarekonfiguration:

- **Mit GPU-Unterstützung**:
  Nutze GPU-Ressourcen, indem du den folgenden Befehl ausführst:

  ```bash
  docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

- **Nur für CPU**:
  Wenn du keine GPU verwendest, verwende stattdessen diesen Befehl:

  ```bash
  docker run -d -p 3000:8080 -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

Beide Befehle ermöglichen eine integrierte, mühelose Installation sowohl von Open WebUI als auch Ollama und stellen sicher, dass du alles schnell zum Laufen bringen kannst.

Nach der Installation kannst du Open WebUI unter [http://localhost:3000](http://localhost:3000) aufrufen. Viel Spaß! 😄

### Andere Installationsmethoden

Wir bieten verschiedene Installationsalternativen, einschließlich nicht-Docker-native Installationsmethoden, Docker Compose, Kustomize und Helm. Besuche unsere [Open WebUI-Dokumentation](https://docs.openwebui.com/getting-started/) oder trete unserer [Discord-Community](https://discord.gg/5rJgQTnV4s) bei, um umfassende Anleitungen zu erhalten.

### Fehlerbehebung

Treten Verbindungsprobleme auf? Unsere [Open WebUI-Dokumentation](https://docs.openwebui.com/troubleshooting/) hilft dir weiter. Für zusätzliche Unterstützung und um unserer lebendigen Community beizutreten, besuche den [Open WebUI Discord](https://discord.gg/5rJgQTnV4s).

#### Open WebUI: Serververbindungsfehler

Wenn du auf Verbindungsprobleme stößt, liegt dies häufig daran, dass der WebUI-Docker-Container den Ollama-Server unter 127.0.0.1:11434 (host.docker.internal:11434) im Container nicht erreichen kann. Verwende das `--network=host`-Flag in deinem Docker-Befehl, um dies zu beheben. Beachte, dass sich der Port von 3000 auf 8080 ändert, was zu folgendem Link führt: `http://localhost:8080`.

**Beispiel Docker-Befehl**:

```bash
docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```

### Halte deine Docker-Installation auf dem neuesten Stand

Falls du deine lokale Docker-Installation auf die neueste Version aktualisieren möchtest, kannst du dies mit [Watchtower](https://containrrr.dev/watchtower/) tun:

```bash
docker run --rm --volume /var/run/docker.sock:/var/run/docker.sock containrrr/watchtower --run-once open-webui
```

Ersetze im letzten Teil des Befehls `open-webui` durch deinen Container-Namen, falls dieser anders ist.

Sieh dir unseren Migrationsleitfaden in unserer [Open WebUI-Dokumentation](https://docs.openwebui.com/migration/) an.

### Nutzung des Dev-Branch 🌙

> [!WARNUNG]
> Der `:dev`-Branch enthält die neuesten instabilen Funktionen und Änderungen. Verwende ihn auf eigenes Risiko, da er Fehler oder unvollständige Funktionen enthalten kann.

Wenn du die neuesten, allerneuesten Funktionen ausprobieren möchtest und mit gelegentlicher Instabilität einverstanden bist, kannst du den `:dev`-Tag wie folgt verwenden:

```bash
docker run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui --add-host=host.docker.internal:host-gateway --restart always ghcr.io/open-webui/open-webui:dev
```

## Was kommt als nächstes? 🌟

Entdecke kommende Funktionen auf unserer Roadmap in der [Open WebUI-Dokumentation](https://docs.openwebui.com/roadmap/).

## Unterstützer ✨

Ein großes Dankeschön an unsere großartigen Unterstützer, die dieses Projekt möglich machen! 🙏

### Platin-Sponsoren 🤍

- Wir suchen nach Sponsoren!

### Anerkennungen

Besonderer Dank gilt [Prof. Lawrence Kim](https://www.lhkim.com/) und [Prof. Nick Vincent](https://www.nickmvincent.com/) für ihre unschätzbare Unterstützung und Anleitung bei der Gestaltung dieses Projekts zu einem Forschungsprojekt. Dankbar für eure Mentorschaft während des gesamten Weges! 🙌

## Lizenz 📜

Dieses Projekt ist unter der [MIT-Lizenz](LICENSE) lizenziert – siehe die [LICENSE](LICENSE)-Datei für Details. 📄

## Unterstützung 💬

Wenn du Fragen, Vorschläge oder Hilfe benötigst, öffne bitte ein Issue oder tritt unserer
[Open WebUI Discord-Community](https://discord.gg/5rJgQTnV4s) bei, um dich mit uns zu verbinden! 🤝

## Stern-Historie

<a href="https://star-history.com/#open-webui/open-webui&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
  </picture>
</a>

---

Erstellt von [Timothy J. Baek](https://github.com/tjbck) - Lass uns gemeinsam Open WebUI noch großartiger machen! 💪
