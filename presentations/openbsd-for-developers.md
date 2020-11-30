# Conteúdo
1. [Por que OpenBSD?](#por-que-openbsd)
2. [Implementações inovadoras](#implementações-inovadoras)
3. [Ambiente padrão de desenvolvimento](#ambiente-padrão-de-desenvolvimento)
4. [Tour pelo código fonte](#tour-pelo-código-fonte)
5. [Como contribuir](#como-contribuir)

## Por que OpenBSD?
 - Sistema operacional totalmente livre
 - Completo (kernel + userland + ports), tudo no repositório CVS
 - Ênfase em ser correto, **seguro**, respeitar padrões e portável
 - Ignorar retro-compatibilidade principalmente quando o assunto é segurança
 - Compromisso de ter uma release a cada 6 meses
 - Foco em ser orientado aos desenvolvedores, principalmente os que estão desenvolvendo o OpenBSD

## Implementações inovadoras
- strlcpy & strlcat (2.4)
- Privilege separation (3.2)
- Stack protector (3.3)
- W^X (3.3; default on 6.0)
- gcc-local(1) (3.4)
- malloc(3) randomization (3.8)
- fork+exec (sshd(8) 2004)
- pledge (5.9)
- KARL (6.2)

## Ambiente padrão de desenvolvimento
- clang
- gcc
- outras linguagens

## Tour pelo código fonte
- src
- ports
- xenocara & www

## Como contribuir
- [Mailing lists](https://www.openbsd.org/mail.html)
- [ports(7)](https://man.openbsd.org/ports.7)
- [style(9)](https://man.openbsd.org/style.9)
- [mdoc(7)](https://man.openbsd.org/mdoc.7)
