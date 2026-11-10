# Slimefun Resource Pack - Minecraft Rust Edition (Horizon 1.21.4+ / 26.3)

Pacote de texturas oficial do **Slimefun** adaptado e compatibilizado para o cliente **Horizon (Minecraft Rust Edition 26.3 / 1.21.4+)**, com suporte nativo ao novo sistema de itens (`assets/minecraft/items/*.json`) e atlas modernos.

Este pacote unifica o melhor do Slimefun clássico, as texturas detalhadas do **Vicarious** e o suporte a múltiplos **Addons**.

---

## ✨ Recursos e Destaques

### 1. Compatibilidade Nativa com Horizon (Minecraft Rust Edition)
- Totalmente convertido para a arquitetura de itens moderna (`minecraft:select` em `minecraft:custom_data` e fallback nativo para `minecraft:range_dispatch` em `minecraft:custom_model_data`).
- `pack_format: 97` compatível com as versões 1.21.4+ e 26.3 do Horizon.
- Suporte a modelos 3D de máquinas, ferramentas e blocos sem conflito de renderização no Vulkan.

### 2. Texturas de Minérios e Lingotes do Vicarious (com Numeração e Porcentagem)
- **Ouros Quilatados:** Texturas com quilates exibidos (`4k`, `6k`, `8k`, `10k`, `12k`, `14k`, `16k`, `18k`, `20k`, **`22k`**, `24k`).
- **Materiais Radioativos:** Indicadores de enriquecimento em porcentagem (**`33%`**, **`66%`**, **`100%`**).
- **Ligas e Pós:** Texturas de alta visibilidade para ligas metálicas (Aço Damasco, Duralumínio, etc.) e pós de minério.

### 3. Interface (GUI) e Botões Corrigidos
- Botões do **Guia do Slimefun** totalmente funcionais e visíveis:
  - 📖 Menu de Configurações
  - 🔍 Pesquisa de Itens
  - ⇦ Página Anterior
  - ⇨ Próxima Página
- Moldura de fundo sólida preenchida com painéis cinzas para visualização limpa de todas as categorias.

### 4. Suporte a Addons Integrados
- **Supreme 2.0:** Armas, ferramentas e armaduras (Titanium, etc.)
- **DyedBackpacks:** Mochilas tingidas de todas as cores
- **Gastronomicon:** Culinária e máquinas de cozinha
- **SlimefunWarfare, ExtraGear, SimpleUtils, Cultivation, SlimeTinker, FastMachines, InfinityExpansion2** e muito mais!

---

## 📥 Como Instalar

1. Baixe o arquivo **[`Slimefun-ResourcePack.zip`](./Slimefun-ResourcePack.zip)** deste repositório.
2. Copie o arquivo para a pasta de pacotes de textura do Horizon:
   - **Linux:** `~/.local/share/horizon/resourcepacks/`
   - **Windows:** `%appdata%\.horizon\resourcepacks\`
3. No Horizon, abra o menu de opções > **Pacotes de Recursos** (ou configure no seu `options.txt`):
   ```json
   ["vanilla", "file/Slimefun-ResourcePack.zip"]
   ```
4. Pronto! O cliente carregará automaticamente todas as texturas e modelos.
