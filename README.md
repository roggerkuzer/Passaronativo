# Passaronativo — MVP

🌿 **Aplicação offline para notas, base de conhecimento local e busca — tudo no seu navegador.**

## 🚀 Como usar

Acesse a aplicação em: **[https://roggerkuzer.github.io/Passaronativo](https://roggerkuzer.github.io/Passaronativo)**

Tudo funciona **100% offline** — seus dados são salvos apenas no seu navegador (localStorage).

## ✨ Funcionalidades

### 📝 Notas
- Crie notas com título, conteúdo e tags
- Upload de imagens com legenda
- Organize com tags personalizadas
- Acesso rápido e edição

### 📸 Upload de Imagens
- Faça upload de fotos diretamente
- Preview inline
- Adicione títulos e legendas
- Organize com tags

### 📚 Base de Conhecimento Local
- Suba materiais: PDF, DOC, DOCX, TXT, JSON, imagens
- Adicione resumos e observações a cada material
- TXT e JSON são totalmente pesquisáveis
- Imagens aparecem com preview
- Exporte/importe a base em JSON para backup

### 🔍 Busca Integrada
- Busca em tempo real
- Encontra em títulos, conteúdo, tags e observações
- Pesquisa também em TXT/JSON incorporados
- Atalho de teclado: **Ctrl+K** (ou **Cmd+K** no Mac)

### 💾 Dados Locais
- **Nada é enviado para servidores**
- Todos os dados ficam no seu navegador
- Limpe tudo com "Limpar tudo" quando quiser
- Exporte base como JSON para backup

## 📋 Limitações (MVP)

| Formato | Status | Notas |
|---------|--------|-------|
| **Notas de texto** | ✅ Completo | Titulo, conteúdo, tags |
| **Imagens** (PNG, JPG, WebP) | ✅ Completo | Preview e busca |
| **TXT** | ✅ Completo | Conteúdo pesquisável |
| **JSON** | ✅ Completo | Conteúdo pesquisável |
| **PDF** | ⚠️ Limitado | Metadados apenas (sem parsing de conteúdo) |
| **DOC/DOCX** | ⚠️ Limitado | Metadados apenas (sem parsing de conteúdo) |

*Para PDF/DOC/DOCX completos, seria necessário uma biblioteca pesada (pdfjs, docx parser) ou backend.*

## 💡 Dicas de Uso

1. **Organize com tags**: Use tags consistentes para encontrar conteúdo rapidamente
2. **Backup**: Exporte sua base regularmente (botão "Exportar Base")
3. **Restaurar**: Importe um JSON exportado anteriormente
4. **Busca rápida**: Use Ctrl+K para buscar
5. **Descrições claras**: Para PDF/DOC, adicione bons resumos na observação

## 🛠️ Tecnologia

- **Vanilla JavaScript** (sem frameworks)
- **localStorage** para persistência
- **HTML5** para upload de arquivos
- Totalmente **responsivo** (desktop + mobile)

## 📱 Compatibilidade

- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Navegadores modernos com suporte a localStorage

## 🔄 Versão

**v1.0 — MVP** • Criado para uso offline local

---

**Passaronativo** — Seus dados, seu navegador, sua privacidade.
