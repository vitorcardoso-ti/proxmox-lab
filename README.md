# 🖥️ Proxmox Lab

Documentação e configurações de laboratório de virtualização com Proxmox VE e XCP-ng.

## 🎯 Objetivo

Registrar a construção e manutenção de um ambiente de virtualização usado para testes, estudos e
homologação de soluções de infraestrutura.

## 🛠️ Tecnologias Utilizadas

![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![XCP-ng](https://img.shields.io/badge/XCP--ng-0A0A0A?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

## 📁 Estrutura do Projeto

```
proxmox-lab/
├── vm-templates/     # Templates de VMs/containers
├── scripts/          # Scripts de automação de provisionamento
├── docs/             # Conceitos, implementação, troubleshooting
└── README.md
```

## 💡 Casos de Uso

- Provisionamento rápido de VMs de teste.
- Homologação de novas versões de sistemas antes de produção.
- Ambiente de estudo para Windows Server, Linux e serviços de rede.

## 📚 Documentação

Documentação técnica completa em [infrastructure-documentation](https://github.com/vitorcardoso-ti/infrastructure-documentation).
Laboratórios práticos relacionados em [homelab](https://github.com/vitorcardoso-ti/homelab).

## 🗺️ Roadmap Futuro

- [ ] Publicar templates de VM padronizados
- [ ] Documentar estratégia de backup do cluster (Veeam)
- [ ] Adicionar diagramas de topologia do lab
