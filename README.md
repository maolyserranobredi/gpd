# gpd

graph TD;

    Inicio((Início))
    Marcas[Marcas]
    Profissionais[Profissionais]
    Experiencias[Experiências]
    Servicos[Serviços]
    Lojas[Lojas]
    App[App]
    Sustentabilidade[Sustentabilidade]
    Configuracoes[Configurações]
    Ajuda[Ajuda]

    Inicio --> Marcas
    Inicio --> Profissionais
    Inicio --> Experiencias
    Inicio --> Servicos
    Inicio --> Lojas
    Inicio --> App
    Inicio --> Sustentabilidade
    Inicio --> Configuracoes
    Inicio --> Ajuda

    Marcas --> SCA
    Marcas --> SpazioDelBagno
    Marcas --> Saccaro
    Marcas --> MaisDesign
    Marcas --> Portobello

    Profissionais --> Arquitetos
    Profissionais --> DesignersInteriores
    Profissionais --> Projetistas
    Profissionais --> Engenheiros

    Experiencias --> ProjetosRealizados
    Experiencias --> AvaliacoesDepoimentos

    Servicos --> ConsultoriaDecoracao
    Servicos --> ProjetosPersonalizados
    Servicos --> InstalacaoManutencao

    Lojas --> Localizacao
    Lojas --> HorarioFuncionamento
    Lojas --> InformacoesContato

    App --> AreaCadastroLogin
    App --> RecursosProfissionais
    App --> SuporteTecnico

    Sustentabilidade --> CompromissosAmbientais
    Sustentabilidade --> ParticipacaoCausasSociais

    Configuracoes --> PerfilUsuario
    Configuracoes --> PreferenciasNotificacao
    Configuracoes --> Idioma

    Ajuda --> PerguntasFrequentes
    Ajuda --> CentralAjuda
    Ajuda --> Contato
