# Cronosmart v4.0

## Como rodar

1. Abra a pasta no VSCode
2. Abra o terminal (Ctrl + `)
3. Execute:

```bash
npm install
npm run dev
```

4. Acesse http://localhost:5173

## Imagens

Coloque os arquivos `logo.png` e `splash.png` dentro da pasta `public/`

## Firebase (Modo Rede)

Copie o arquivo `.env.example` para `.env` e preencha com suas chaves do Firebase.
O app funciona normalmente em modo local sem o `.env`.

## Estrutura

```
src/
├── App.jsx              # Roteador principal
├── config/theme.js      # Cores e tema
├── utils/time.js        # Funções de tempo
├── hooks/               # useTiming, useAthletes, useRecords, useFirebase
├── modules/             # firebase, export, network
├── components/ui/       # Header, NumPad, CronoDisplay, ExportButtons
├── screens/             # 12 telas do app
└── adapters/            # Integrações externas (TicketSports, etc.)
```
