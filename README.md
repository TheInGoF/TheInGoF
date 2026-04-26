### Hi, I'm building stuff at home

Hobby projects — sketches with rough edges and ambitious scope. Mostly
self-hosted things that scratch my own itches: ideas, architecture and
deploy decisions are mine; an LLM does most of the typing. I commit
what works, throw out what doesn't, ship when it runs end-to-end.

Day-job is elsewhere. This is the side where I get to be the architect.

---

### Currently public

#### 📚 [PageMentor](https://github.com/TheInGoF/PageMentor)
Self-hosted study companion. Drop in a lecture PDF, get back an M4B
audiobook, AI flashcards and a timed exam trainer — fully local
Ollama + Qwen3-TTS, no cloud. Built for the open-uni-and-a-long-commute
combo.

#### 🚗 [IDMate](https://github.com/TheInGoF/IDMate)
Self-hosted EV telemetry & trip log for non-Tesla EVs. Same spirit as
TeslaMate, but the data comes from CAN/OBD2 over MQTT-AES instead of
a vendor API. Trips, journeys, charge tracker (with Tibber-vs-flat
comparison), battery health analysis.

#### 🔌 [IDTelemetry](https://github.com/TheInGoF/IDTelemetry)
Companion firmware for IDMate. ESP32-S3 stick that lives in the OBD2
port, does CAN + LTE-M MQTT + BLE ELM327 + deep-sleep wake patterns.

---

### Stack-of-the-day

Python · Bun · Hono · React · TypeScript · SQLite · InfluxDB ·
Meilisearch · Docker / Portainer · Ollama · ESP-IDF · MQTT · Home
Assistant.

Self-host first. AGPL where possible. No telemetry phoning home unless
I built that telemetry myself.

---

[![Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/lordvonbaum)

> Donations are voluntary and just keep the homelab humming. They don't
> influence anything other than my coffee budget.
