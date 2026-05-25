╔══════════════════════════════════════════════════════════════════╗
║         COMO PUBLICAR O SITE DA INTEGRAMENTE SST                ║
║                  integralmentesst.com.br                        ║
╚══════════════════════════════════════════════════════════════════╝

Esta pasta "website" contém tudo que precisa para publicar o site.
Arquivos:
  - index.html   → o site completo
  - vercel.json  → configuração de hospedagem

══════════════════════════════════════════════════════════════════
PASSO 1 — REGISTRAR O DOMÍNIO (registro.br)
══════════════════════════════════════════════════════════════════

1. Acesse: https://registro.br
2. Na barra de busca, digite: integralmentesst.com.br
3. Se estiver disponível, clique em "Registrar"
4. Crie uma conta (CPF ou CNPJ)
5. Finalize o pagamento (≈ R$ 40/ano)
6. GUARDE o login e senha do registro.br — vai precisar depois

══════════════════════════════════════════════════════════════════
PASSO 2 — CRIAR CONTA NO VERCEL E PUBLICAR O SITE
══════════════════════════════════════════════════════════════════

1. Acesse: https://vercel.com
2. Clique em "Sign Up" → escolha "Continue with Google"
   (use o e-mail que você vai criar para a empresa)
3. No painel, clique em: "Add New…" → "Project"
4. Role a página até ver "Import Third-Party Git Repository"
   ou procure o link "Browse All Templates"
5. Procure a opção "Deploy without Git" ou "Upload"
   → Se não aparecer, acesse diretamente: https://vercel.com/new
6. ARRASTE a pasta "website" inteira para a área de upload
   (a pasta que contém index.html e vercel.json)
7. Clique em "Deploy"
8. Aguarde 30 segundos → o site ficará no ar em uma URL
   temporária como: https://website-xxx.vercel.app
   TESTE o site nessa URL antes de continuar!

══════════════════════════════════════════════════════════════════
PASSO 3 — CONECTAR SEU DOMÍNIO AO VERCEL
══════════════════════════════════════════════════════════════════

No painel do Vercel, dentro do seu projeto:
1. Clique em "Settings" (menu superior)
2. Clique em "Domains" (menu lateral)
3. No campo, digite: integralmentesst.com.br
4. Clique em "Add"
5. Adicione também: www.integralmentesst.com.br
6. O Vercel vai mostrar registros DNS — ANOTE os valores:
   Tipo A    → aponta para um IP (ex: 76.76.21.21)
   Tipo CNAME → cname.vercel-dns.com

Agora no painel do registro.br:
1. Acesse: https://registro.br → faça login
2. Clique no domínio: integralmentesst.com.br
3. Clique em "Editar zona DNS"
4. Adicione os registros que o Vercel indicou:
   - Registro tipo A:     @ → [IP fornecido pelo Vercel]
   - Registro tipo CNAME: www → cname.vercel-dns.com
5. Salve as alterações
6. Aguarde até 24h para o domínio propagar
   (geralmente funciona em menos de 2h)

Quando o Vercel mostrar o domínio como "Valid" (com ✓ verde),
o site estará no ar em: https://integralmentesst.com.br
com HTTPS gratuito e automático!

══════════════════════════════════════════════════════════════════
PASSO 4 — CRIAR E-MAIL PROFISSIONAL (Zoho Mail — GRÁTIS)
══════════════════════════════════════════════════════════════════

Sugestão de e-mail gratuito com domínio próprio: Zoho Mail

1. Acesse: https://zoho.com/mail
2. Clique em "Sign Up For Free" → escolha plano "Forever Free"
   (1 usuário grátis para sempre)
3. Em "Domain", selecione "I already have a domain"
4. Digite: integralmentesst.com.br
5. Siga o assistente de verificação de domínio
   (vai pedir para adicionar um registro TXT no registro.br)
6. Crie seu e-mail: contato@integralmentesst.com.br

Depois de criar o e-mail, AVISE o Claude para atualizar o site!

══════════════════════════════════════════════════════════════════
PASSO 5 — ATUALIZAR O SITE COM O E-MAIL REAL
══════════════════════════════════════════════════════════════════

Após criar o e-mail, peça ao Claude para substituir o placeholder
"contato@integralmentesst.com.br" pelo e-mail real no index.html.
(O e-mail já está como placeholder no site — só precisa confirmar)

══════════════════════════════════════════════════════════════════
RESUMO DOS CUSTOS
══════════════════════════════════════════════════════════════════

  Hospedagem Vercel    → GRÁTIS
  HTTPS (SSL)          → GRÁTIS (automático pelo Vercel)
  E-mail Zoho Mail     → GRÁTIS (1 conta)
  Domínio registro.br  → ≈ R$ 40/ano

══════════════════════════════════════════════════════════════════
SUPORTE
══════════════════════════════════════════════════════════════════

Qualquer dúvida em qualquer etapa, descreva onde travou
e o Claude te ajuda a resolver.
