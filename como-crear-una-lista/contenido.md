Conteúdo
========

Os extras são, precisamente, o conteúdo de uma lista de extras. Use este segundo passo para adicioná\-los, gerenciá\-los ou excluí\-los se não forem mais necessários.

![](../.gitbook/assets/content_add_module.png)

Clique em **Add new extra** para adicionar um extra na lista e preencha os campos necessários:

**List provider** . Indique a origem das informações para configurar os extras da lista:

* **Provider by user CMS** . Selecione esta opción para configurar o extra de maneira manual.
* **Provider by Product ID** . Selecione esta opción para indicar um Product ID e receber as informações do Extra através de API.

{% hint style="info" %}
Estas informações devem ser fornecidas por sua equipe de desenvolvimento.
{% endhint %}

**Icon** 

Adicione o ícone que representa o extra. A versão predeterminada (de **Icon**) é obrigatória e, de maneira opcional, você pode adicionar a versão **Dark icon**, que seria o ícone exibido ao usuário quando ele está em *dark mode* no app.

{% hint style="success" %}
É recomendável carregar as duas versões do ícone e no formato SVG. Também admite o formato PNG.
{% endhint %}

**Name of the extra module**. Nome do extra que aparece embaixo do ícone. 

{% hint style="info" %}
:bulb:É recomendável usar um nome muito curto, caso contrário, ele aparecerá cortado.
{% endhint %}

**Action configuration of your extra** 

* **Not include clickable action**. Selecione esta opção, marcada em forma predeterminada, se você não deseja que o ícone \+ texto do extra seja clicável.
* **Include clickable action**. Marque esta opção para tornar clicável o conjunto de ícone \+ texto do extra e configurar a URL para a qual o usuário é direcionado ao clicar. 
  * **Action navigation to**: 
    * **URL**. Selecione esta opção para incluir uma URL de maneira manual. Indique no campo Web address a URL para direcionar o usuário quando ele clique no extra.
    * **Preconfigured**. Selecione esta opção para escolher um ponto específico do app. Indique o ponto específico na lista suspensa.

**Audiences**. Selecione o público ao qual deve pertencer o usuário para que poder visualizar o extra.

{% hint style="success" %}
🤓Observe que, dentro de uma lista de extras, você pode encontrar extras configurados para diferentes públicos. Obviamente, isso não é um problema, mas é importante não esquecer, porque ao realizar um teste ou as provas necessárias para visualizar extras, é essencial que o usuário pertença a esse público.
{% endhint %}

Se você precisa adicionar mais extras, clique no botão **Add new extra** e repita os passos descritos nesta seção.

Clique em **Continue** para ir ao último passo.

