# Junto — teste no GitHub Pages

Aplicativo de finanças com perfis locais, sem login. Compatível com mobile e desktop.

## Publicar
1. Crie um repositório no GitHub. No plano gratuito, GitHub Pages requer repositório público.
2. Envie os arquivos extraídos deste pacote para a raiz do repositório. Não envie o ZIP fechado.
3. Em Settings > Pages, selecione Deploy from a branch, branch main e pasta /(root). Clique Save.
4. Aguarde a implantação e abra o endereço indicado em Settings > Pages.

Este pacote contém index.html, .nojekyll e este README. Ele não contém registros financeiros.
O código do site pode ser público; os lançamentos ficam no armazenamento local de cada navegador.

## Testar
1. Abra o endereço no computador e no celular.
2. Em Ajustes, edite os nomes dos dois perfis.
3. Cadastre uma despesa de R$ 100 no painel percentual, com 60% para o primeiro perfil.
4. Escolha Georgia como pagadora: as parcelas serão R$ 60 e R$ 40; o primeiro perfil deve R$ 60 a Georgia.
5. Cadastre uma despesa de R$ 100 no painel 50/50, paga pelo primeiro perfil.
   Neste painel, Georgia deve R$ 50 ao primeiro perfil. O consolidado líquido será R$ 10 a receber por Georgia.
6. Troque os filtros mensais dos dois painéis e confira que são independentes.
7. Alterne claro/escuro e recarregue para conferir a preferência salva.
8. Teste hover dos gráficos no desktop, seleção dos perfis no formulário e cadastro manual pelo leitor de fotos.
9. Exporte e importe um backup JSON em Ajustes para conferir sua recuperação.

Os passos de saldo assumem um navegador sem outros lançamentos. Use um perfil de navegador de teste.
Cada navegador/dispositivo possui seus próprios dados; publicar no GitHub não habilita sincronização.
Os registros do arquivo local anterior não aparecem automaticamente no endereço publicado.
Para migrar, exporte JSON do aplicativo antigo e importe no novo endereço.
