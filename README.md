# FLAST-FLAGS-RBX-1
Metal
Importante

Somente MacOS

{
    "FFlagDebugGraphicsPreferMetal": "True"
}
Vulcano
Cuidado

Erros visuais e travamentos

{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferVulkan": "True"
}
OpenGL
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferOpenGL": "True"
}
Direto X 10
{
    "FFlagDebugGraphicsPreferD3D11FL10": "True"
}
Direto X 11
{
    "FFlagDebugGraphicsPreferD3D11": "True"
}
Tecnologias de Relâmpagos
Iluminação Voxel (Fase 1)
{
    "DFFlagDebugRenderForceTechnologyVoxel": "True"
}
Iluminação Shadowmap (Fase 2)
{
    "FFlagDebugForceFutureIsBrightPhase2": "True"
}
Iluminação do Futuro (Fase 3)
{
    "FFlagDebugForceFutureIsBrightPhase3": "True"
}
Configurações gráficas
Aumento de partículas em gráficos baixos
@jovemnoob
{
    "FFlagDebugDeterministicParticles" : "True"
}
Deixa as coisas um pouco mais brilhantes
{
    "FFlagRenderFixFog": "True"
}
HyperThreading
{
    "FFlagDebugCheckRenderThreading": "True",
    "FFlagRenderDebugCheckThreading2": "True"
}
Máximo de Fios
{
    "FIntRuntimeMaxNumOfThreads": "2400"
}
Mínimo de Fios
{
    "FIntTaskSchedulerThreadMin": "3"
}
Terreno mais suave
{
    "FFlagDebugRenderingSetDeterministic": "True"
}
Nível de qualidade gráfica de força
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
Desativar sombras do jogador
{
    "FIntRenderShadowIntensity": "0"
}
Desabilitar Sombras
{
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647"
}
Preserve a qualidade da renderização com a configuração de exibição
{
    "DFFlagDisableDPIScale": "True"
}
Baixa qualidade gráfica com distância máxima de renderização/níveis de qualidade FRM
Dica

1-6 são gráficos baixos, acima de 6 são gráficos altos. Como o controle deslizante de gráficos 1-21

{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
Níveis FRM
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
Controle deslizante de qualidade gráfica FRM 21
{
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagFixGraphicsQuality": "True"
}
Baixa distância de renderização
Dica

Ver níveis de FRM

{
    "DFIntDebugRestrictGCDistance": "1"
}
Limita atualizações leves
{
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6"
}
Desativa a animação de fade in e fade out a cada atualização de luz
{
    "FIntRenderLocalLightFadeInMs": "0"
}
Faz os avatares brilharem
Dica

Tudo fica escuro aqui em baixo <3

[!NOTA] DFIntDebugFRMQualityLevelOverride está lá para definir seus gráficos para 3 barras

Dica

Você pode alterá-lo para qualquer valor acima de 3

{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
Desabilitar PostFX
{
    "FFlagDisablePostFx": "True"
}
Pausar Voxelizer/Desativar Baked Shadows
{
    "DFFlagDebugPauseVoxelizer": "True"
}
Céu cinza
Importante

Aplica-se somente a jogos com o skybox padrão

{
    "FFlagDebugSkyGray": "True"
}
Forçar LOD em malhas
{
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
Atenuação de iluminação
{
    "FFlagNewLightAttenuation": "True"
}
Habilitar GPULightCulling
Dica

Combine com atenuação de iluminação para melhor visão

{
    "FFlagFastGPULightCulling3": "True"
}
Habilitar CPULightCulling
{
    "FFlagDebugForceFSMCPULightCulling": "True"
}
Buffer de quadro
Dica

0 faz a tela branca 1-3 faz com que outros jogadores tenham movimentos lentos, 4 é estável, tem melhor desempenho do que 10 e menos atraso de entrada

{
    "DFIntMaxFrameBufferSize": "4"
}
Texturas de terreno de baixa qualidade
Dica

4 para menor qualidade 16, 32, 64 para maior qualidade

{
    "FIntTerrainArraySliceSize": "4"
}
Qualidade da textura da força
Dica

Defina qualquer valor de 0 a 3

{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3"
}
Texturas de qualidade inferior
{
    "DFIntPerformanceControlTextureQualityBestUtility": "-1"
}
Sem texturas de avatar
{
    "DFIntTextureCompositorActiveJobs": "0"
}
Gerenciador de texturas
Dica

-1 Remove quase tudo, 1-4 Desfocado, 5-7 Baixa qualidade também remove pinos, 8 Remove quase tudo (este é melhor)

{
    "FIntDebugTextureManagerSkipMips": "-1"
}
Remover grama
{
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
}
Força MSAA
Importante

Valores: 0, 1, 2, 4, 8

Cuidado

Valores acima de 4> causarão erros na janela de visualização

{
    "FIntDebugForceMSAASamples": "4"
}
Viés do ShadowMap
Importante

Somente Future e ShadowMap

{
    "FIntRenderShadowmapBias": "75"
}
Limita o número de animações sendo reproduzidas
Dica

0 remove a maioria das animações do jogador, 1-5 remove a animação de caminhada após pular

{
    "DFIntMaxActiveAnimationTracks": "0"
}
Qualidade de vida
Remove mensagem traduzida com suporte ao ingressar
Observação

"Roblox automatically translates supported languages in chat."

{
    "FFlagChatTranslationEnableSystemMessage": false
}
Permite que você personalize quais idiomas estão disponíveis para o recurso de tradução do chat
Importante

O inglês não pode ser removido.

@ocarafrancês4
{
    "FStringChatTranslationEnabledLocales": "es_es,fr_fr,pt_br,de_de,it_it,ja_jp,ko_kr,id_id,tr_tr,zh_cn,zh_tw,th_th,pl_pl,vi_vn,ru_ru,"
}
Desativar atalho de teclado de captura
{
    "FFlagEnableCapturesHotkeyExperiment_v4": "False"
}
Partícula de item de avatar reduzida em FP
{
    "FFlagUserHideCharacterParticlesInFirstPerson": "True"
}
Desbloqueador FPS nas configurações do menu Roblox
{
    "FFlagGameBasicSettingsFramerateCap5": "True",
    "DFIntTaskSchedulerTargetFps": "0"
}
Desbloqueador FPS ilimitado
{
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
    "DFIntTaskSchedulerTargetFps": "9999"
}
Alternadores de ocultação da GUI
{
    "FFlagUserShowGuiHideToggles": "True",
    "GuiHidingApiSupport2": "True"
}
Esconder guis
Importante

Substitua "ID" por qualquer ID de grupo do qual você faça parte.

Combinação de teclas	Ação
Ctrl + Shift + B	Alterna GUIs no espaço 3D (BillboardGuis, SurfaceGuis, etc.)
Ctrl + Shift + C	Alterna ScreenGuis definidos pelo jogo
Ctrl + Shift + G	Alterna Roblox CoreGuis
Ctrl + Shift + N	Alterna os nomes dos jogadores e outros BillboardGuis que aparecem acima de um jogador
{
    "DFIntCanHideGuiGroupId": "ID"
}
Remover roupas em camadas relacionadas para pesquisa no catálogo do aplicativo lua
{
    "FStringAXCategories": "ClassicShirts.ClassicTShirts.ClassicPants"
}
Desativar barra de título em tela cheia
{
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
Correção de animação gaguejante
{
    "DFIntTimestepArbiterThresholdCFLThou": "300"
}
Desativar anúncios no jogo
{
    "FFlagAdServiceEnabled": "False"
}
Desativar telemetria
{
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True"
}
Navegue na web dentro do Roblox
Importante

Clique no emblema Beta ou no emblema 13+ para abrir o navegador webview.

{
    "FFlagTopBarUseNewBadge": "True",
    "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
MTU
Dica

Identifique a MTU atual

Windows : Abra o Prompt de Comando e digite netsh interface ipv4 show subinterfaces.
Linux : Use ifconfigou ip link showpara encontrar a MTU atual da sua interface de rede.
Dica

Determinar a MTU ideal

Teste de ping : use o pingcomando com o -fsinalizador (para evitar fragmentação) e o sinalizador -l(ou no Linux) para definir o tamanho do pacote.-s
Exemplo para Windows :
ping roblox.com -f -l 1472
Exemplo para Linux :
ping -s 1472 -M do roblox.com
Comece com um tamanho de pacote de 1472 bytes, então reduza em 10-12 bytes se necessário até encontrar o maior tamanho que não fragmente. Adicione 28 bytes a esse número para obter o MTU ideal.
{
    "DFIntConnectionMTUSize": "MTU_HERE"
}
Sem desconexão da Internet
Observação

Você ainda será expulso, mas a mensagem não será exibida.

{
    "DFFlagDebugDisableTimeoutDisconnect": "True"
}
Ajustar tempo limite padrão
Dica

1 segundo = 1000

@dis_spencer
{
    "DFIntDefaultTimeoutTimeMs": "10000"
}
Início rápido do jogo
Cuidado

Isso pode causar alguns bugs

{
    "FFlagEnableQuickGameLaunch": "True"
}
Aumento da contagem de pré-carregamento de ativos
Observação

Aumentar o limite máximo de ativos pré-carregados de 100 para infinito permite que os jogos que você já jogou carreguem muito mais rápido, acessando instantaneamente os ativos carregados anteriormente.

Importante

Para que isso seja eficaz, o jogo deve ter sido totalmente carregado pelo menos uma vez, de preferência com o mapa inteiro armazenado em cache.

Dica

Se um jogo tiver um botão "Skip Loading", é recomendado usá-lo. Esses jogos normalmente incluem um cronômetro de contagem regressiva que, após chegar a zero, apenas confirma que todos os ativos foram carregados.

@espectroscópico
{
    "DFIntNumAssetsMaxToPreload": "9999999",
    "DFIntAssetPreloading": "9999999"
}
Desativar compras no jogo
{
    "DFFlagOrder66": "True"
}
Desativar bate-papo
{
    "FFlagDebugForceChatDisabled": "True"
}
Desativar animações dinâmicas de cabeças
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
Desativa automaticamente o som do seu microfone ao entrar (VC)
{
    "FFlagDebugDefaultChannelStartMuted": "False"
}
opt-out Experiência Idioma
Observação

Remove a opção Idioma da experiência nas configurações

{
    "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
Permite que você altere o limite de zoom out
Importante

Aplica-se somente a jogos que não alteraram o limite de zoom padrão

{
    "FIntCameraMaxZoomDistance": "9999"
}
Exclusivo em tela cheia
Dica

Alt + Excluir

{
    "FFlagHandleAltEnterFullscreenManually": "False"
}
Interface do usuário/Visuais
Quebrar movimento reduzido V4
@kezcn
imagem

{
    "FFlagFixReducedMotionStuckIGM2": "False"
}
Reverter "Gráficos" de volta para Discovery
{
    "FFlagLuaAppChartsPageRenameIXP": "False"
}
Desativar barra lateral
{
    "FFlagEnableNavBarLabels3": "False"
}
Cardápio V1
{
    "FFlagDisableNewIGMinDUA": "True",
    "FFlagEnableInGameMenuControls": "False",
    "FFlagEnableInGameMenuModernization": "False",
    "FFlagEnableMenuControlsABTest": "False",
    "FFlagEnableMenuModernizationABTest": "False",
    "FFlagEnableMenuModernizationABTest2": "False",
    "FFlagEnableV3MenuABTest3": "False"
}
Cardápio V2
{
    "FIntNewInGameMenuPercentRollout3": "1000"
}
Mensagem de desconexão personalizada
{
    "FFlagReconnectDisabled": "True",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
Exibir FPS
{
    "FFlagDebugDisplayFPS": "True"
}
Emblema verificado
Observação

Somente para o cliente

{
    "FStringWhitelistVerifiedUserId": "UserID"
}
Distintivo verificado em todos
Observação

Somente para o cliente

{
    "FFlagOverridePlayerVerifiedBadge": "True"
}
Aplica cores frias às coisas
{
    "FFlagDebugDisplayUnthemedInstances": "True"
}
Reverter novo menu de convite
{
    "FFlagEnableNewInviteMenuIXP2": "False"
}
Reverter espaçamento em caso de erros
{
    "FFlagErrorPromptResizesHeight": "False"
}
Remover Desfoque de Desconexão/Desfoque de Carregamento
{
    "FIntRobloxGuiBlurIntensity": "0"
}
Desabilitar novas configurações de tradução de bate-papo
{
    "FFlagChatTranslationSettingEnabled3": "False"
}
Novo modo de câmera
{
    "FFlagNewCameraControls": "True"
}
Escala MicroProfile Personalizada
{
    "DFIntMicroProfilerDpiScaleOverride":  "100"
}
Definir tamanho de fonte personalizado
{
    "FIntFontSizePadding": "1"
}
Ajustar velocidade de rolagem
{
    "FIntScrollWheelDeltaAmount": "140"
}
Definir comprimento de mensagem de kick personalizado
{
    "FIntMaxKickMessageLength": "1"
}
Tema escuro mais escuro
{
    "FFlagLuaAppUseUIBloxColorPalettes1": "True",
    "FFlagUIBloxUseNewThemeColorPalettes": "True"
}
Menu V4 sem transparência (2023)
{
    "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
Página de Assinaturas
{
    "FFlagLuaAppDevSubsEnabled": "True"
}
Sobreposição que mostra o que você digita
{
    "FFlagDebugTextBoxServiceShowOverlay": "True"
}
Quantidade de linhas a serem mostradas de uma vez para acima
{
    "DFIntTextBoxServiceHistorySize": "1"
}
Esconde gui
{
    "FFlagDebugAdornsDisabled":  "True"
}
Não renderizar UI
{
    "FFlagDebugDontRenderUI": "True"
}
Não renderize GUIs de tela
{
    "FFlagDebugDontRenderScreenGui": "True"
}
Desativar preenchimento automático
{
    "FFlagEnableCommandAutocomplete": "False"
}
Quebrar Menu da Barra Superior
{
    "FStringNewInGameMenuForceds": "UserID",
    "FFlagEnableInGameMenuChrome": "True"
}
Quebrar Ícone Colecionável
{
    "FFlagDisplayCollectiblesIcon": "False"
}
Desativar o bate-papo com bolhas
{
    "FFlagEnableBubbleChatFromChatService": "False"
}
Desativar câmera e autovisualização
{
    "FFlagSelfieViewEnabled": "True"
}
Desativar bate-papo do Avatar
{
    "FFlagAvatarChatServiceEnabled3": "False"
}
Remover o emblema VC Beta
{
    "FFlagVoiceBetaBadge": "False",
    "FFlagTopBarUseNewBadge": "False",
    "FFlagBetaBadgeLearnMoreLinkFormview": "False",
    "FFlagControlBetaBadgeWithGuac": "False",
    "FStringVoiceBetaBadgeLearnMoreLink": "null"
}
Transparência do controlador VR
{
    "FIntVRTouchControllerTransparency": "0"
}
Desativar VR Collision Fade
{
    "FFlagViewCollisionFadeToBlackInVR": "False"
}
Limitar a reprodução de vídeos
{
    "DFIntVideoMaxNumberOfVideosPlaying": "0"
}
Desabilitar relatórios DSA no jogo
@kezcn
{
    "FFlagDSAIllegalContentReporting2": "False"
}
Ferramentas de desenvolvimento de aplicativos de desktop
Importante

Funciona somente em janelas de visualização da web, como perfis, Ctrl + Shift + I

{
    "FFlagDebugEnableNewWebView2DevTool": "True"
}
Interface do usuário/Visuais Experimental
Posições de acessórios personalizados
{
    "FFlagAXAccessoryAdjustment": "True",
    "FFlagAXAccessoryAdjustmentIXPEnabled": "True",
    "FFlagAXAccessoryAdjustmentIXPEnabledForAll": "True",
    "FFlagAXAvatarFetchResultCamelCase": "True",
    "FFlagAccessoryAdjustmentEnabled3": "True",
    "FFlagAccessoryAdjustmentEnabled4": "True"
}
Habilitar a experiência do usuário pela primeira vez para a interface do usuário do Chrome
{
    "FFlagEnableChromeFTUX": "True"
}
Desativar opção de háptica
{
    "FFlagAddHapticsToggle": "False"
}
Habilitar melhor haptics
{
    "FFlagEnableBetterHapticsResultHandling": "True"
}
Barra superior da interface do usuário do Chrome
{
    "FFlagEnableReportAbuseMenuRoactABTest2": "True",
    "FFlagEnableInGameMenuChromeABTest2": "True",
    "FFlagEnableInGameMenuChromeABTest3": "True"
}
Remoção da barra superior da interface do usuário do Chrome
{
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableInGameMenuChromeABTest3": "False"
}
Ocultar botão de fechar lista de jogadores na interface do Chrome
{
    "FFlagDisablePlayerListDisplayCloseBtn": "True"
}
Fixar bate-papo na interface do usuário do Chrome
{
    "FFlagEnableChromePinnedChat": "True"
}
Tipo de Morte Ragdoll
Importante

Somente estúdio

Observação

Eu tentei Ragdollver se alguma coisa aconteceria kkk foi assim que eu encontrei isso (achei isso há muito tempo)

@burguerboxer
{
    "DFStringDefaultAvatarDeathType": "Ragdoll"
}
Áudio relacionado
Permite que você altere a distância do bate-papo por voz
Observação

Padrão: [Mín. 7 Máx. 80]

{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
Os sons usam velocidade física e ficam distorcidos
Observação

<2017 Áudio

{
    "FFlagSoundsUsePhysicalVelocity": "True"
}
Oclusão de áudio
{
    "FFlagSoundsUsePhysicalVelocity": "True"
}
Limitar áudios que estão sendo reproduzidos
{
    "DFIntMaxLoadableAudioChannelCount": "1"
}
Mexa no volume do chat de voz
Observação

Padrão: 1000

{
    "DFIntVoiceChatVolumeThousandths": "100000"
}
Nenhum som
{
    "FFlagDebugRomarkMockingAudioDevices": "True"
}
Física (Abusivo)
Observação

Ajude-me a encontrar alguns desses FastFlags (com créditos no @burgerboxer) comprando https://www.roblox.com/game-pass/895489152/ ou impulsionando nosso servidor!

Ferramenta Desync
{
    "DFIntSimBlockLargeLocalToolWeldManipulationsThreshold": "-1"
}
Remapear R6 para R15 Rigs/Movimento estranho
{
    "FFlagRemapAnimationR6ToR15Rig": "True"
}
Movimento estranho das pernas
{
    "DFFlagAnimatorPostProcessIK": "True"
}
Grampos de ajuste de altura do quadril
{
    "DFIntHipHeightClamp": "-48"
}
Saltos altos aleatórios
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
Bêbado
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
Sem animações
Observação

Impede que o jogo tente replicar suas animações no servidor. Você não tem animações no servidor, mas tem para seu cliente

{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
Cole as partes não ancoradas em você
Dica

- = para cima, + = para baixo

{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
Distância máxima de Raycast
Observação

Raycasting é o uso de testes de intersecção para resolver problemas no Roblox. O uso mais comum do raycasting é determinar o primeiro objeto interceptado por um raio. Isso é feito lançando um raio virtual de um certo ponto em uma direção e determinando a primeira superfície com a qual ele interceptou.

Dica

Quebrar colisão de pernas de 2 para -inf, meio que quebra a câmera em valores acima de 3, câmera noclip em 3

{
    "DFIntRaycastMaxDistance": "3"
}
Possível super salto
{
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500"
}
Alterar taxa do DataSender
Observação

Aka não deixa você carregar jogos

{
    "DFIntDataSenderRate": "-1"
}
Desativar eventos de toque
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
Lag falso
{
    "DFIntS2PhysicsSenderRate": "1"
}
Invisível 1
Observação

Impede que a física do seu personagem seja enviada para o servidor, para que seu personagem não se mova para o servidor. Você pode se mover no seu cliente.

{
    "DFIntS2PhysicsSenderRate": "-30"
}
Invisível 2
Observação

Bloqueia a posição do seu personagem no servidor para (0, 0, 0), tendo o efeito colateral de torná-lo invisível. Isso afeta apenas o servidor e outros clientes, não você. Coisas do lado do servidor que dependem da sua posição, como clicar para obter ferramentas, não funcionarão. Em alguns jogos, elas podem ser abusáveis. Aqui está uma lista delas: Link

{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
Invisível 3
Observação

Restringe o cliente de enviar qualquer informação relacionada à física. Isso significa que outras pessoas podem derrubá-lo.

{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
Invisível do lado do cliente
{
    "FIntParallelDynamicPartsFastClusterBatchSize": "-1"
}
Deformação e câmera lenta
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
}
Nenhum clipe 1
Dica

Ajuste o valor para não cair no chão

{
    "DFIntAssemblyExtentsExpansionStudHundredth": "-50"
}
Nenhum clipe 2
Dica

Ajuste o valor para não cair no chão

{
    "DFIntSimBroadPhasePairCountMax": "50"
}
Nenhum clipe 3
@burgerboxer e @dis_spencer
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntMaximumFreefallMoveTimeInTenths": "1000",
    "DFIntDebugSimPrimalStiffness": "0"
}
Congelar
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "0"
}
Altura do quadril
Observação

Salto muito controlável, só funciona com valores negativos

Dica

0 permite que você passe o mouse

{
    "DFIntMaxAltitudePDStickHipHeightPercent": "-200"
}
Deslizar na parede
{
    "DFIntUnstickForceAttackInTenths": "-4"
}
Propriedade da rede
Observação

melhor propriedade de rede de peças

[!CUIDADO] Isso pode fazer com que você seja banido em alguns jogos com anticheats (Limbobbia)

{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000"
}
Baixa gravidade 1
Observação

'FFlagDebugSimDefaultPrimalSolver' : True
Este sinalizador habilita o novo mecanismo de simulação ou o que quer que seja.

Cuidado

'DFIntDebugSimPrimalLineSearch' : 1
Esta configuração é uma gravidade/voo de um homem pobre. O valor padrão é 100:

Acima de 0: Baixa gravidade.
Abaixo de 1 para -1: tornará a jogabilidade estranha, especialmente com a física.
Abaixo de -1: Atua como um modo de voo para pobres (não é realmente utilizável).
@Amizade
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "3"
}
Partes vazias não ancoradas
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "222"
}
Baixa Gravidade 2
Cuidado

Isso é mais bugado

{
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalPreconditioner": "100",
  "DFIntDebugSimPrimalPreconditionerMinExp": "100",
  "DFIntDebugSimPrimalNewtonIts": "1",
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalWarmstartVelocity": "-150",
  "DFIntDebugSimPrimalWarmstartForce": "-775",
  "DFIntDebugSimPrimalToleranceInv": "1"
}
Melhoria do controle de peças do Low Gravity 2
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalNewtonIts": "1",
    "DFIntDebugSimPrimalPreconditioner": "15",
    "DFIntDebugSimPrimalPreconditionerMinExp": "10",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalWarmstartForce": "-150",
    "DFIntDebugSimPrimalWarmstartVelocity": "100"
}
Ferramenta Fly
{
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "DFIntMaxClientSimulationRadius": "2147000000",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntNonSolidFloorPercentForceApplication": "-12000",
    "DFIntDebugSimPrimalPreconditioner": "100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "100",
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalWarmstartVelocity": "-150",
    "DFIntDebugSimPrimalWarmstartForce": "-775",
    "DFIntDebugSimPrimalToleranceInv": "1"
}
SpeedHax para trás
Aviso

Bugginess e velocidade dependem do valor de DFIntDebugSimPrimalWarmstartForce. Os valores recomendados são 775e o valor que eu coloquei.

Dica

Para DFIntDebugSimPrimalWarmstartVelocity, é recomendado usar um valor de 150. No entanto, pode ser difícil de controlar.

Observação

Talvez eu não tenha descoberto isso primeiro, mas descobri sozinho.

{
  "DFIntDebugSimPrimalNewtonIts": "1",
  "DFIntDebugSimPrimalPreconditioner": "69",
  "DFIntDebugSimPrimalPreconditionerMinExp": "69",
  "DFIntDebugSimPrimalToleranceInv": "1",
  "DFIntDebugSimPrimalWarmstartForce": "-885",
  "DFIntDebugSimPrimalWarmstartVelocity": "-350",
  "FFlagDebugSimDefaultPrimalSolver": "True"
}
Velocidade do veículo 1
{
    "DFIntDebugSimPrimalWarmstartForce": "40",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "41"
}
Velocidade do veículo 2
Dica

Ajuste DFIntDebugSimPrimalWarmstartVelocityou DFIntBulletContactBreakOrthogonalThresholdPercentencontre os melhores valores para você

{
    "DFIntDebugSimPrimalLineSearch": "50",
    "DFIntDebugSimPrimalWarmstartVelocity": "103",
    "DFIntDebugSimPrimalStiffness": "300",
    "DFIntBulletContactBreakOrthogonalThresholdPercent": "10000"
}
GRAH GRAH
{
    "DFIntDebugSimPrimalLineSearch": "1",
    "DFIntDebugSimPrimalWarmstartForce": "160",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True"
}
Giro 1
@corvo-sangue
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FIntDebugSimPrimalGSLumpAlpha": "-2147483647",
    "DFIntDebugSimPrimalPreconditioner": "1100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "DFIntDebugSimPrimalWarmstartForce": "-800",
    "DFIntDebugSimPrimalToleranceInv": "1"
}
Giro 2
Observação

Girar + voar

vídeo 1 vídeo 2
@kezcn
{

    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "50",
    "DFIntDebugSimPrimalWarmstartVelocity": "103",
    "DFIntDebugSimPrimalStiffness": "300",
    "DFIntBulletContactBreakOrthogonalThresholdPercent": "10000"
}
Velocidade 2
Observação

Não para trás, mas com mais bugs

{
    "DFIntDebugSimPrimalWarmstartForce": "-285",
    "DFIntDebugSimPrimalWarmstartVelocity": "750",
    "FIntDebugSimPrimalGSLumpAlpha": "-2147483647",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalPreconditioner": "100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
    "DFIntDebugSimPrimalNewtonIts": "1",
    "DFIntDebugSimPrimalToleranceInv": "10",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntDebugSimPrimalLineSearch": "100"
}
Visuais abusivos
Semi Fullbright
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True"
}
Desenha um círculo sob os avatares
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest2": "False"
}
Esboço Humanoide
Observação

Desenha um contorno em torno de cada parte e de cada humanoide

{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
fflag acima mas mais complexo
Observação

Desenha um contorno em torno de cada parte do corpo

{
    "DFFlagDebugDrawBvhNodes": "True"
}
Câmera Buggy ZPlane
{
    "FIntCameraFarZPlane": "1"
}
Adiciona uma IU no jogo, que destaca qualquer parte tocada pelo jogador (como chão, Meshes etc.). É uma IU que não funciona também. Também adiciona um círculo azul ao seu humanoide.
{
    "FFlagDebugHumanoidRendering": "True"
}
Raio X
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
Predefinições específicas de jogos abusivos
Você pode contribuir fazendo uma solicitação de pull.
Arremessar coisas e pessoas
Mandem as pessoas para o inferno 😈😈
{
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntDebugSimPrimalWarmstartVelocity": "-10",
    "DFIntDebugSimPrimalWarmstartForce": "1750",
    "DFIntDebugSimPrimalPreconditioner": "-20",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalToleranceInv": "2"
}
Mandar as pessoas para o inferno V2
Dica

Modifique o warmstart para alterar a velocidade

{
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalPreconditioner": "1100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalWarmstartForce": "-800",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FIntDebugSimPrimalGSLumpAlpha": "-2147483647"
}
Mandar pessoas para o céu
{
    "DFIntDebugSimPrimalNewtonIts": "1",
    "DFIntDebugSimPrimalPreconditioner": "15",
    "DFIntDebugSimPrimalPreconditionerMinExp": "10",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalWarmstartForce": "-150",
    "DFIntDebugSimPrimalWarmstartVelocity": "100",
    "FFlagDebugSimDefaultPrimalSolver": "True",
}
lol
Impeça os chineses de espionar você
{
    "FStringTencentAuthPath": "null"
}
Não toque na parede! 1
{
    "DFIntDebugSimPrimalNewtonIts": "-2147483647",
    "DFIntDebugSimPrimalToleranceInv": "-2147483647",
    "FFlagDebugSimDefaultPrimalSolver": "True"
}
Não toque na parede! 2
{
    "DFIntDebugSimPrimalPreconditionerMinExp": "20",
    "DFIntDebugSimPrimalWarmstartVelocity": "-101",
    "DFIntDebugSimPrimalPreconditioner": "1000",
    "DFIntDebugSimPrimalWarmstartForce": "1",
    "DFIntDebugSimPrimalNewtonIts": "4000",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalToleranceInv": "6",
    "DFIntDebugSimPrimalLineSearch": "1"
}
Nossa, não acredito que o Roblox é tão idiota a ponto de fazer isso...
{
    "FIntPhysicsGridHierarchyLowestLevelInitBinCount": "199999999",
    "FIntPhysicsGridHierarchyLowestLevelInitBinCountWorldModel": "100000000",
    "FIntPhysicsSolverCollisionPoolBucketSize": "2147483647",
    "FIntPhysicsSolverCollisionPoolBucketSizeWorldModel": "2147483647"
}
Bater Roblox 1
{
    "DFIntTimestepArbiterThresholdCFLThou": "0"
}
Bater Roblox 2
{
    "DFFlagVideoCaptureServiceEnabled": "False"
}
Aumentar Ping
{
    "DFIntDataSenderMaxBandwidthBps": "150"
}
Depurar
Mostra o estado de uma bandeira
{
    "FStringDebugShowFlagState": "FLAG_HERE"
}
[!DICA]

{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
Mostrar pedaços delineados
{
    "FFlagDebugLightGridShowChunks": "True"
}
Mostrar blocos delineados que estão sendo interagidos
{
    "DFFlagDebugEnableStreamingSolverVisualization": "True"
}
Impede que eventos remotos sejam executados
@espectroscópico
{
    "DFIntRemoteEventSingleInvocationSizeLimit": "1"
}
registra coisas no console de desenvolvimento
{
    "FStringDebugLuaLogLevel": "debug",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
}
Validação Octree
{
    "FFlagDebugEnableOctreeValidation": "True"
}
Autoexplicativo 1
{
    "DFFlagDebugPrintDataPingBreakDown": "True"
}
Autoexplicativo 2
{
    "DFFlagDebugAudioLogging": "True"
}
Duplicado de Acima
{
    "DFFlagDebugAudioLogging2": "True"
}
Autoexplicativo 3
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
Autoexplicativo 4
Observação

Desativar detectores de arrasto

{
    "FFlagDragDetectors1": "False"
}
Autoexplicativo 5
Observação

Desativar escalada CTM

{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "False"
}
Autoexplicativo 6
Observação

Desativar botão de feedback no ESC

{
    "FFlagDisableFeedbackSoothsayerCheck": "False"
}
Autoexplicativo 7
@ocarafrancês4
{
    "FFlagRenamePassesAndGearToSubscriptionsAndPasses": "False"
}
Predefinições da comunidade
Não estamos aceitando Fast Flags de desempenho que não estejam listados ou sejam conhecidos.
mate completamente a qualidade do seu jogo com fflags que eu conheço
@dinamitebumblemouth
{
    "FFlagDisablePostFx": "True",
    "FIntDebugTextureManagerSkipMips": "-1",
    "DFIntTextureCompositorActiveJobs": "0",
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderShadowIntensity": "0",
    "FIntRenderShadowmapBias": "1",
    "FIntDebugForceMSAASamples": "-1",
    "FIntFRMMinGrassDistance": "0",
    "DFIntTextureQualityOverride": "1"
}
