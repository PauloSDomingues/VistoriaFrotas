# Sistema de Inspeção de Frota ISP (PWA)

Aplicação web moderna, leve e responsiva desenvolvida para automatizar a rotina de vistorias e inspeções semanais da frota de veículos de um Provedor de Internet (ISP). 

O sistema funciona diretamente no navegador do smartphone (Android/iOS), permite funcionamento sem necessidade de backend, salva os registros localmente e possui suporte para exportação em **PDF** e compartilhamento rápido via **WhatsApp**.

---

## Principais Recursos

  - **Instalável como App (PWA):** Pode ser adicionado à tela inicial do celular via Google Chrome/Edge, funcionando como um aplicativo nativo.
  - **Captura Dupla de Fotos:** Permite tirar fotos diretamente da câmera traseira do smartphone ou escolher imagens salvas na galeria.
  - **Checklist Categorizado para Telecom/ISP:**
  - **Mecânica & Motor:** Óleo, água, freios, fluidos e correias.
  - **Pneus & Segurança:** Calibragem, desgaste, luzes e buzina.
  - **Vidros & Espelhos:** Para-brisa, retrovisores e vidros laterais.
  - **Itens de Emergência:** Estepe, macaco, triângulo e chave de roda.
  - **Equipamentos ISP:** Máquina de fusão, OTDR, Power Meter, escadas e EPIs.
  - **Observações Setorizadas:** Campo de notas individuais em cada categoria para detalhar avarias específicas.
  - **Geração de PDF Completo:** Cria relatórios em A4 com fotos e checklist detalhado.
  - **Compartilhamento via WhatsApp:** Envia o resumo formatado da inspeção direto para grupos da gerência ou mecânica com apenas um toque.
  - **Armazenamento Local (Offline):** Salva o histórico diretamente no dispositivo usando `localStorage`, garantindo privacidade e sem custo de hospedagem.

---

## Tecnologias Utilizadas

- **HTML5 & JavaScript (ES6+)**
- **Tailwind CSS:** Estilização responsiva e moderna.
- **FontAwesome 6:** Ícones de interface.
- **jsPDF:** Biblioteca para montagem e exportação do arquivo PDF.

---

## Como Instalar e Acessar

### 1. Acesso Web
Acesse o aplicativo publicado via GitHub Pages:
> `https://paulosdomingues.github.io/VistoriaFrotas/`

### 2. Instalação no Celular (Android / iOS)
1. Abra o link acima no navegador **Google Chrome** do celular.
2. Toque no menu de três pontinhos (Canto superior direito no Android).
3. Selecione a opção **"Adicionar à tela inicial"** ou **"Instalar aplicativo"**.
4. Confirme a ação. O ícone do aplicativo será criado na tela principal do smartphone.

---

## Como Usar

1. **Preencha os Dados:** Selecione o veículo da frota, informe o nome do motorista/técnico e digite a quilometragem atual.
2. **Realize a Checagem:** Marque a situação de cada item (`Ok` ou `Avaria`). Caso necessário, insira uma observação para a categoria.
3. **Anexe Fotos:** Tire fotos de avarias, do painel (KM) ou da organização das ferramentas.
4. **Finalizar:** Clique em **"Salvar e Finalizar Vistoria"**.
5. **Consultar e Compartilhar:** Acesse a aba **Histórico**, abra a vistoria realizada e clique em **"Enviar WhatsApp"** ou **"Baixar PDF Completo"**.

---

## Estrutura de Arquivos

```
VistoriaFrotas/
│
├── index.html       # Código fonte completo (HTML, CSS e JS)
└── README.md        # Documentação do projeto
```

---

## Contribuição & Suporte

Projeto desenvolvido sob medida para otimização de frotas de Provedores de Internet. Sinta-se à vontade para abrir uma *Issue* ou enviar melhorias via *Pull Request*.
