WARNING — EDUCATIONAL SIMULATIONS ONLY — DO NOT RUN ON PRODUCTION SYSTEMS

This repository uses the exact folder names provided but contains safe, non-destructive simulations intended only for authorised cybersecurity teaching and lab exercises in isolated environments.

Folders:

ransoware-code
A controlled simulation that mimics the behavioural concept of file encryption for teaching purposes only. The simulation only operates on a designated sandbox directory and uses reversible, non-destructive transformations and clear metadata to allow full recovery. It is not destructive ransomware.

decrypt-code
A matching, safe recovery routine that demonstrates the decryption/restoration process for files modified by the simulation in ransoware-code. Included to teach incident response and validation of backups.

keylogger-code
A benign keystroke-recorder simulator intended for usability testing or pedagogical demonstrations. It writes sanitized, anonymised logs to a local text file and explicitly excludes characters defined in the code. Use only with informed consent in lab environments.

keylogger-email-code
A lab-oriented notifier that demonstrates how log forwarding works in a controlled test: it sends periodic summary reports (every 60 seconds configurable) of synthetic or consented logs to a specified email. Rate-limited and intended for integration/alerting tests only.

AVISO — SIMULAÇÕES EDUCACIONAIS — NÃO EXECUTAR EM SISTEMAS DE PRODUÇÃO

Este repositório mantém exatamente os nomes de pastas indicados, mas contém simulações seguras e não destrutivas, destinadas a aulas e laboratórios autorizados.

Pastas:

ransoware-code
Simulação controlada que ilustra o conceito de encriptação de ficheiros para fins didáticos. Opera apenas numa pasta sandbox e usa transformações reversíveis com metadados claros para permitir restauração total. Não é ransomware real.

decrypt-code
Rotina segura de recuperação que demonstra o processo de descriptografia/restauração dos ficheiros alterados pela simulação em ransoware-code. Usada para treinar resposta a incidentes e validação de backups.

keylogger-code
Simulador benigno de gravação de teclas para testes de usabilidade ou demonstração pedagógica. Gera logs sanitizados/anonimizados em ficheiro texto e exclui caracteres especificados no código. Usar apenas com consentimento e em ambiente de laboratório.

keylogger-email-code
Demonstrador de envio periódico de logs para fins de teste: envia relatórios a cada 60 segundos (configurável) para email escolhido, operando somente com logs sintéticos ou consentidos. Limitado a uso em laboratório.
