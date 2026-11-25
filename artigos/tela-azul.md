# [resolução da tela azul no windows]

- Autor(a): bernardo augusto da silva reis
- Categoria: Artigo: Diagnóstico e Reparo de Tela Azul (BSOD) no Windows

> Alerta de Segurança: Antes de iniciar,salve seus arquivos importantes e faça backup dos dados.Desligue o computador antes de realizar qualquer manutenção física e utilize pulseira aniestática para evitar danso aos componentes

## 1. Sintoma e Diagnóstico Inicial

A tela azul ocorre quando o windows apresenta uma falha grave e reinicia ou desliga o computador.As causa mais comuns são drivers incompatíveis,problemas na memória ram,arquivos corrompidos,ou falhas de hardware.

## 2. Ferramentas e Recursos Necessários

- Hardware / Bancada: Computador,memoria ram e pen drive para recuperação,se necessário.
- Software / Utilitário: Prompt de Comando (Administrador), Gerenciador de Dispositivos, Visualizador de Eventos, Monitor de Confiabilidade e Diagnóstico de Memória do Windows.

## 3. Procedimento de Solução (Passo a Passo)

1. Identificar o erro: Anotar o código de parada (Stop Code) apresentado na tela azul e verificar quando o problema acontece.
2. Verificar os drivers: Abrir o Gerenciador de Dispositivos e procurar drivers com erros. Atualizar ou reverter drivers instalados recentemente.
* Analisar os arquivos do sistema: Abrir o Prompt de Comando como administrador e executar:
DISM /Online /Cleanup-Image /RestoreHealth
sfc /scannow

3. Verificar a memória RAM: Executar o Diagnóstico de Memória do Windows, digitando mdsched.exe no menu Iniciar e reiniciando o computador para realizar o teste.
* Verificar a estabilidade: Reiniciar o computador, observar se a tela azul continua aparecendo e consultar o Monitor de Confiabilidade para identificar novas falhas.

## 4. Checklist de Validação (Teste Final)

1.Código de parada identificado e registrado.

2.Drivers recentes analisados e corrigidos.

3.Arquivos do sistema verificados e reparados.

4.Memória RAM testada.

5.Computador reiniciado sem apresentar tela azul.

6.Sistema operacional funcionando normalmente e com estabilidade.
