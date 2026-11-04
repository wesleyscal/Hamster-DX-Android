# Hamster DX Android — teste

Build experimental da amostra publica da FingerTech para testar a conexao USB OTG e a captura do leitor Hamster DX em tablet Android.

O workflow `.github/workflows/build-apk.yml` baixa a origem oficial durante a execucao, aplica ajustes para teste e tenta compilar um APK de depuracao. Nenhum dado biometrico real deve ser cadastrado neste app experimental.

## Status

A compilacao depende do GitHub Actions e da resolucao de dependencias Android antigas. A geracao e o funcionamento do APK nao estao garantidos ate a verificacao dos logs e um teste no tablet.

Fonte: https://github.com/FingerTechBR/FingertechHamster-AndroidAPP-
