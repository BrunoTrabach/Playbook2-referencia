# PLAYBOOK AIWA - DOCUMENTAÇÃO COMPLETA
## Histórico Detalhado da Conversa
**Data de criação:** 03/06/2026
**Desenvolvido por:** Bruno Trabach + Meta AI
**Projeto:** Playbook Interativo Boomboxes 2025-2026

---

## 1. EVOLUÇÃO DAS ESTRUTURAS

### ESTRUTURA INICIAL (V4.0)
```
/
├── index.html (básico)
├── historias/
├── comparativos/
└── assets/
```
Problemas: Não responsivo, sem botões, visual simples

### ESTRUTURA ATUAL (V4.7)
```
aiwa-playbook/
├── index.html (Home estilo app)
├── historias/
│   ├── index.html
│   └── dados/
│       ├── historia1.html
│       ├── historia2.html
│       ├── historia3.html
│       └── historia4.html
├── conclusao/
│   ├── index.html
│   ├── completa.html
│   └── resumida.html
├── tecnologias/
│   └── index.html (com JSON completo)
├── comparativos/
│   └── index.html
├── pilares/
│   └── index.html (3 Pilares CHEGA+)
├── treinamento/
├── onde-comprar/
├── sobre/
└── assets/
    ├── css/
    ├── js/
    └── avatares/
```

---

## 2. VERSÕES GERADAS (DETALHADO)

### V4.4 - playbook_v44_completo.zip
**Data:** Início da conversa
**Características:**
- Visual GVBus básico
- 6 botões: Histórias, Comparativos, 3 Pilares, Conclusão, Tecnologias, Sobre
- Histórias com avatares (Bruno, Cristiane, Edy, Fernanda)
- Tabela comparativa com checkboxes
- CSS: gvbus.css com variáveis --c1 a --c6
- Problemas: Não responsivo, tabelas cortando

### V4.5 - playbook_v45_modelo_final.zip
**Data:** Após envio do modelo HTML
**Características:**
- Home copiada do seu modelo Tailwind
- Header vermelho #E30613
- Logo "aiwa" minúsculo 36px
- Grid 2x3 com bordas coloridas
- Bottom navigation
- Status bar mock (9:41)
- Problema: Header muito alto

### V4.6 - playbook_v46_ajustado_final.zip
**Data:** Correção de responsividade
**Mudanças críticas:**
- Header reduzido de 80px para 44px + 30px logo
- Logo reduzido para 30px
- Botões de 130px para 115px altura
- Gap de 16px para 12px
- Header agora ROLA com conteúdo (não fixo)
- Padding reduzido em 40%
- Resultado: 6 botões cabem sem scroll na tela inicial

### V4.7 - playbook_v47_3pilares_final.zip
**Data:** Integração 3 Pilares
**Novidades:**
- Botão "Treinamento" renomeado para "3 Pilares"
- Página pilares/index.html completa
- Design com cards coloridos por pilar
- Scripts de abordagem formatados

---

## 3. CONTEÚDO DETALHADO POR SEÇÃO

### 3.1 HISTÓRIAS (Simulações)
**Local:** /historias/dados/

**História 1:** Abordagem inicial - Cliente indeciso
- Personagens: Promotor, Cliente
- Foco: Demonstração "sente o grave"

**História 2:** Objeção de preço
- Personagens: Vendedor, Cliente
- Foco: Comparativo custo-benefício

**História 3:** Dúvida sobre marca
- Personagens: Promotor, Cristiane
- Foco: Legado AIWA, fábrica Manaus

**História 4:** Fechamento
- Personagens: Fernanda, Vendedor
- Foco: Indicação, pós-venda
- Final: 2 botões para Conclusão

**Navegação:**
- História 1 → 2 → 3 → 4 → Conclusão
- Botões numerados no topo

### 3.2 TECNOLOGIAS E RECURSOS
**Local:** /tecnologias/index.html
**Tecnologia:** JSON embutido + JavaScript

**AIWA BBS-01 (8 tecnologias principais):**
1. Energy Saving - mantém 200W na bateria (JBL perde 25%)
2. Bluetooth 5.3 - estável
3. IP66 - jatos d'água
4. App Aiwa BR Audio - EQ, BOOST, RGB
5. BOOST Graves - exclusivo
6. Power Bank 5V/2A
7. TWS - 2 caixas
8. 3 Vias com 3 amplificadores

**JBL Boombox 3 (4 tecnologias):**
1. JBL Pro Sound - assinatura
2. IP67 - imersão 1m
3. PartyBoost - múltiplas caixas
4. Bateria 24h

**LG XG9S (4 tecnologias):**
1. Meridian Audio - usado em Jaguar/BMW
2. 2 Woofers fibra carbono
3. Projetor de luz
4. 16M cores RGB

**Philco PBX01 (3 tecnologias):**
1. Bluetooth 5.4 (mais novo)
2. ExBass
3. 300W nominal

### 3.3 3 PILARES - MÉTODO CHEGA+
**Local:** /pilares/index.html

**Pilar 1: UX & Descoberta**
- Conceito: Quebrar defesa do cliente
- Script: "Fique à vontade para aumentar o volume..."
- Pergunta chave: Casa ou festa? Lembra da AIWA antiga?
- Cor: Vermelho #E30613

**Pilar 2: Legado e Engenharia**
- Conceito: Destruir objeção de procedência
- Script: "Fabricada em Manaus, ex-fábrica Sony..."
- Foco: Qualidade japonesa, durabilidade
- Cor: Azul #0077B6

**Pilar 3: Demonstração Sensorial**
- Conceito: Validação física
- Script: "Coloque a mão na lateral, sinta o radiador..."
- Foco: Grave sem vibração, sem distorção
- Cor: Verde #009639

### 3.4 CONCLUSÃO
**Local:** /conclusao/

**Completa:** Texto longo sobre relacionamento, venda direta/indireta, experiência
**Resumida:** Versão curta para consulta rápida

---

## 4. ESPECIFICAÇÕES TÉCNICAS

### CSS Principal (Home)
```css
- max-width: 420px (mobile first)
- background: #f0f2f5
- Header: #E30613
- Fonte: Inter
- Border-radius: 16-20px
- Shadow: 0 4px 14px rgba(0,0,0,.06)
- Botões: border-2 com cores específicas
```

### Cores dos Botões:
1. Simulações: #E30613 (vermelho Aiwa)
2. Mensagem Final: #0077B6 (azul)
3. Tecnologias: #009639 (verde)
4. Comparativos: #D90429 (vermelho escuro)
5. 3 Pilares: #6c757d (cinza)
6. Onde Comprar: #FF9500 (laranja)

### Responsividade:
- Mobile: < 420px (100% width)
- Tablet: 420-768px (centralizado)
- Desktop: > 768px (max 420px, sombra)

---

## 5. COMANDOS TERMUX (PASSO A PASSO)

```bash
# 1. Entrar na pasta
cd ~/aiwa-playbook

# 2. Descompactar nova versão
unzip -o /sdcard/Download/playbook_v47_3pilares_final.zip

# 3. Verificar arquivos
ls -la

# 4. Adicionar ao git
git add .

# 5. Commit
git commit -m "V4.7 - descricao da mudanca"

# 6. Enviar para GitHub
git push origin main

# 7. Verificar site (aguardar 60-90s)
# https://brunotrabach.github.io/aiwa-playbook/
```

---

## 6. ESTRUTURA DE ARQUIVOS NO GITHUB

**Repositório:** https://github.com/BrunoTrabach/aiwa-playbook
**Branch:** main
**GitHub Pages:** Ativado

**Arquivos importantes:**
- index.html (raiz)
- .nojekyll (para GitHub Pages funcionar)

---

## 7. PRÓXIMOS PASSOS PENDENTES

1. **Comparativos completos** - Aguardando seu arquivo
   - Deve conter: tabela lado a lado com todas specs
   - Potência, bateria, IP, preço, etc.

2. **Onde Comprar** - Integrar links de lojas

3. **Sobre** - Adicionar vídeo institucional
   - Colocar MP4 em /assets/videos/

4. **Avatares** - Adicionar imagens reais
   - Bruno_promotor_aiwa.png
   - Cristiane_cliente.png
   - Edy_vendedor.png
   - Fernanda Cliente.png

---

## 8. DICAS DE MANUTENÇÃO

**Para editar textos:**
1. Edite o HTML direto no Termux com nano
2. Ou edite no PC e faça upload

**Para atualizar:**
- Sempre use unzip -o para sobrescrever
- Faça commit descritivo
- Teste no celular após 2 minutos

**Backup:**
- Mantenha todos os ZIPs salvos
- GitHub é seu backup principal

---

## 9. CONTATOS E REFERÊNCIAS

**Marca:** AIWA Brasil - Grupo MK
**Fábrica:** Manaus (ex-Sony)
**Site oficial:** www.aiwa.com.br
**App:** Aiwa BR Audio (Play Store / App Store)

**Modelos cobertos:**
- AIWA BBS-01 (200W RMS)
- JBL Boombox 3 (180W/136W)
- LG XG9S (120W)
- Philco PBX01 (300W nominal)

---

**Documento gerado automaticamente em 03/06/2026**
**Versão do playbook: 4.7**
**Total de arquivos gerados: 4 ZIPs principais**
