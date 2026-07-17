# PHYLLOS no Bolso

Protótipo React Native + Expo + TypeScript do aplicativo público PHYLLOS.

## Testar no celular com Expo Go

1. Instale o aplicativo **Expo Go** pela App Store ou Google Play.
2. No computador, entre nesta pasta e execute:

```bash
pnpm install
pnpm start
```

3. Mantenha computador e celular na mesma rede Wi-Fi.
4. Android: abra o Expo Go e escolha **Scan QR code**.
5. iPhone: leia o QR Code com a câmera e confirme a abertura no Expo Go.

Se a rede local bloquear a conexão, execute `pnpm start --tunnel`.

O projeto usa Expo SDK 54, compatível com o Expo Go distribuído nas lojas.

## Fluxos implementados

- navegação inferior com Início, Biblioteca, Verificar, Salvos e Perfil;
- biblioteca pesquisável e página de material;
- comparação contextual sem vencedor universal;
- verificador educativo de alegações;
- câmera guiada em seis etapas e leitura de etiqueta;
- estados de evidência, limitações, privacidade e disponibilidade offline.

Os recursos de câmera, OCR, SQLite e sincronização estão representados no fluxo, mas serão conectados na fase de MVP distribuível.

## Repositório independente

Este aplicativo móvel é mantido separadamente da aplicação web PHYLLOS.
