```mermaid
graph TD;
    M["MEXICO"]
    M --> B_BUSINESS_SERVICES_and_DEVELOPMEN["BUSINESS SERVICES & DEVELOPMEN"]
    B_BUSINESS_SERVICES_and_DEVELOPMEN --> 6_ASSOCIATE_CEBALLOS_MEJIA_IVAN["6. ASSOCIATE (CEBALLOS MEJIA, IVAN)"]
    B_BUSINESS_SERVICES_and_DEVELOPMEN --> 6_ASSOCIATE_VALDEZ_MONROY_ALBERTO["6. ASSOCIATE (VALDEZ MONROY, ALBERTO)"]
    B_BUSINESS_SERVICES_and_DEVELOPMEN --> 7_ANALYST_DIAZ_LIMON_DANIEL_ALEJANDRO["7. ANALYST (DIAZ LIMON, DANIEL ALEJANDRO)"]
    6_ASSOCIATE_CEBALLOS_MEJIA_IVAN --> 7_ANALYST_DIAZ_LIMON_DANIEL_ALEJANDRO
    6_ASSOCIATE_VALDEZ_MONROY_ALBERTO --> 7_ANALYST_DIAZ_LIMON_DANIEL_ALEJANDRO
    M --> B_CASH_SALES["CASH SALES"]
    B_CASH_SALES --> 6_ASSOCIATE_ALANIS_DE_LA_MAZA_DAVID["6. ASSOCIATE (ALANIS DE LA MAZA, DAVID)"]
    B_CASH_SALES --> 7_ANALYST_VILLAFUERTE_CEDILLO_PAOLA["7. ANALYST (VILLAFUERTE CEDILLO, PAOLA)"]
    6_ASSOCIATE_ALANIS_DE_LA_MAZA_DAVID --> 7_ANALYST_VILLAFUERTE_CEDILLO_PAOLA
    M --> B_CORPORATE_SALES_MEXICO["CORPORATE SALES MEXICO"]
    B_CORPORATE_SALES_MEXICO --> 6_ASSOCIATE_MENDOZA_MONZON_RODRIGO["6. ASSOCIATE (MENDOZA MONZON, RODRIGO)"]
    B_CORPORATE_SALES_MEXICO --> 7_ANALYST_PONCE_OLVERA_EMILIO["7. ANALYST (PONCE OLVERA, EMILIO)"]
    6_ASSOCIATE_MENDOZA_MONZON_RODRIGO --> 7_ANALYST_PONCE_OLVERA_EMILIO
    M --> B_CREDIT_MÉXICO_I["CREDIT MÉXICO I"]
    B_CREDIT_MÉXICO_I --> 6_ASSOCIATE_NOGUEDA_DIAZ_JUAN["6. ASSOCIATE (NOGUEDA DIAZ, JUAN)"]
    M --> B_CREDIT_NEW_PRODUCTS["CREDIT NEW PRODUCTS"]
    M --> B_Custodia_y_derivados_execution["Custodia y derivados execution"]
    B_Custodia_y_derivados_execution --> 6_ASSOCIATE_CASTRO_HERNANDEZ_HUGO_MOISES_ALONSO["6. ASSOCIATE (CASTRO HERNANDEZ, HUGO MOISES ALONSO)"]
    B_Custodia_y_derivados_execution --> 7_ANALYST_MARIN_OSORIO_MARIA_DEL_CARMEN["7. ANALYST (MARIN OSORIO, MARIA DEL CARMEN)"]
    6_ASSOCIATE_CASTRO_HERNANDEZ_HUGO_MOISES_ALONSO --> 7_ANALYST_MARIN_OSORIO_MARIA_DEL_CARMEN
    M --> B_Custodia_y_derivados_Intellige["Custodia y derivados Intellige"]
    B_Custodia_y_derivados_Intellige --> 7_ANALYST_RODRIGUEZ_GONZALEZ_OSCAR_DANIEL["7. ANALYST (RODRIGUEZ GONZALEZ, OSCAR DANIEL)"]
    M --> B_Custodia_y_Derivados_Strategy["Custodia y Derivados Strategy"]
    B_Custodia_y_Derivados_Strategy --> 6_ASSOCIATE_GADEA_MENDOZA_BENJAMIN["6. ASSOCIATE (GADEA MENDOZA, BENJAMIN)"]
    B_Custodia_y_Derivados_Strategy --> 6_ASSOCIATE_GARIBAY_AVALOS_BRENDA_ELENA["6. ASSOCIATE (GARIBAY AVALOS, BRENDA ELENA)"]
    B_Custodia_y_Derivados_Strategy --> 6_ASSOCIATE_MUÑOZ_ZAMORA_CARLOS["6. ASSOCIATE (MUÑOZ ZAMORA, CARLOS)"]
    B_Custodia_y_Derivados_Strategy --> 6_ASSOCIATE_VAZQUEZ_PEREZ_LAURA_GABRIELA["6. ASSOCIATE (VAZQUEZ PEREZ, LAURA GABRIELA)"]
    B_Custodia_y_Derivados_Strategy --> 7_ANALYST_ILLESCAS_NAVA_LUIS_FRANCISCO["7. ANALYST (ILLESCAS NAVA, LUIS FRANCISCO)"]
    6_ASSOCIATE_GADEA_MENDOZA_BENJAMIN --> 7_ANALYST_ILLESCAS_NAVA_LUIS_FRANCISCO
    6_ASSOCIATE_GARIBAY_AVALOS_BRENDA_ELENA --> 7_ANALYST_ILLESCAS_NAVA_LUIS_FRANCISCO
    6_ASSOCIATE_MUÑOZ_ZAMORA_CARLOS --> 7_ANALYST_ILLESCAS_NAVA_LUIS_FRANCISCO
    6_ASSOCIATE_VAZQUEZ_PEREZ_LAURA_GABRIELA --> 7_ANALYST_ILLESCAS_NAVA_LUIS_FRANCISCO
    M --> B_Custody_and_Derivatives["Custody and Derivatives"]
    B_Custody_and_Derivatives --> 6_ASSOCIATE_JAIMES_DIAZ_IVAN["6. ASSOCIATE (JAIMES DIAZ, IVAN)"]
    B_Custody_and_Derivatives --> 7_ANALYST_ZAMORA_BERNAL_SERGIO["7. ANALYST (ZAMORA BERNAL, SERGIO)"]
    6_ASSOCIATE_JAIMES_DIAZ_IVAN --> 7_ANALYST_ZAMORA_BERNAL_SERGIO
    M --> B_CVA_and_FVA_TRADING["CVA & FVA TRADING"]
    M --> B_DCM["DCM"]
    B_DCM --> 6_ASSOCIATE_GRACIA_BOBADILLA_PABLO["6. ASSOCIATE (GRACIA BOBADILLA, PABLO)"]
    B_DCM --> 6_ASSOCIATE_ULLOA_RIVAS_SALVADOR["6. ASSOCIATE (ULLOA RIVAS, SALVADOR)"]
    B_DCM --> 7_ANALYST_LINARES_PEREZ_ELLIOT_BRADLEY["7. ANALYST (LINARES PEREZ, ELLIOT BRADLEY)"]
    6_ASSOCIATE_GRACIA_BOBADILLA_PABLO --> 7_ANALYST_LINARES_PEREZ_ELLIOT_BRADLEY
    6_ASSOCIATE_ULLOA_RIVAS_SALVADOR --> 7_ANALYST_LINARES_PEREZ_ELLIOT_BRADLEY
    M --> B_DELEGATED_PROCESSES["DELEGATED PROCESSES"]
    B_DELEGATED_PROCESSES --> 6_ASSOCIATE_RUIZ_RAMIREZ_CESAR_ALBERTO["6. ASSOCIATE (RUIZ RAMIREZ, CESAR ALBERTO)"]
    B_DELEGATED_PROCESSES --> 7_ANALYST_MUÑOZ_MOLINA_DIRERI_ITZEL["7. ANALYST (MUÑOZ MOLINA, DIRERI ITZEL)"]
    6_ASSOCIATE_RUIZ_RAMIREZ_CESAR_ALBERTO --> 7_ANALYST_MUÑOZ_MOLINA_DIRERI_ITZEL
    B_DELEGATED_PROCESSES --> 7_ANALYST_SANCHEZ_CARDENAS_AREMY_MELISSA["7. ANALYST (SANCHEZ CARDENAS, AREMY MELISSA)"]
    6_ASSOCIATE_RUIZ_RAMIREZ_CESAR_ALBERTO --> 7_ANALYST_SANCHEZ_CARDENAS_AREMY_MELISSA
    B_DELEGATED_PROCESSES --> 7_ANALYST_TORRES_MORENO_JORGE_LUIS["7. ANALYST (TORRES MORENO, JORGE LUIS)"]
    6_ASSOCIATE_RUIZ_RAMIREZ_CESAR_ALBERTO --> 7_ANALYST_TORRES_MORENO_JORGE_LUIS
    M --> B_DERIVATIVES["DERIVATIVES"]
    B_DERIVATIVES --> 6_ASSOCIATE_PEREZ_LOPEZ_RICARDO_OSMAR["6. ASSOCIATE (PEREZ LOPEZ, RICARDO OSMAR)"]
    M --> B_DIVISIONAL_FX_BAJIO["DIVISIONAL FX BAJIO"]
    B_DIVISIONAL_FX_BAJIO --> 6_ASSOCIATE_CABRERA_MENDOZA_JOSUE_MISAEL["6. ASSOCIATE (CABRERA MENDOZA, JOSUE MISAEL)"]
    B_DIVISIONAL_FX_BAJIO --> 7_ANALYST_WONG_SANCHEZ_AXHEL_RICARDO["7. ANALYST (WONG SANCHEZ, AXHEL RICARDO)"]
    6_ASSOCIATE_CABRERA_MENDOZA_JOSUE_MISAEL --> 7_ANALYST_WONG_SANCHEZ_AXHEL_RICARDO
    M --> B_DIVISIONAL_FX_METROPOLITANA["DIVISIONAL FX METROPOLITANA"]
    B_DIVISIONAL_FX_METROPOLITANA --> 6_ASSOCIATE_GOMEZ_VARGAS_GABRIELA_IVONNE["6. ASSOCIATE (GOMEZ VARGAS, GABRIELA IVONNE)"]
    B_DIVISIONAL_FX_METROPOLITANA --> 6_ASSOCIATE_HORTA_PIMENTEL_KARLA["6. ASSOCIATE (HORTA PIMENTEL, KARLA)"]
    B_DIVISIONAL_FX_METROPOLITANA --> 6_ASSOCIATE_VILLADOZOLA_MOLINA_PATRICIA["6. ASSOCIATE (VILLADOZOLA MOLINA, PATRICIA)"]
    B_DIVISIONAL_FX_METROPOLITANA --> 7_ANALYST_AGUILLON_PACHO_JORGE["7. ANALYST (AGUILLON PACHO, JORGE)"]
    6_ASSOCIATE_GOMEZ_VARGAS_GABRIELA_IVONNE --> 7_ANALYST_AGUILLON_PACHO_JORGE
    6_ASSOCIATE_HORTA_PIMENTEL_KARLA --> 7_ANALYST_AGUILLON_PACHO_JORGE
    6_ASSOCIATE_VILLADOZOLA_MOLINA_PATRICIA --> 7_ANALYST_AGUILLON_PACHO_JORGE
    B_DIVISIONAL_FX_METROPOLITANA --> 7_ANALYST_SANCHEZ_ROJAS_JULIO_ALBERTO["7. ANALYST (SANCHEZ ROJAS, JULIO ALBERTO)"]
    6_ASSOCIATE_GOMEZ_VARGAS_GABRIELA_IVONNE --> 7_ANALYST_SANCHEZ_ROJAS_JULIO_ALBERTO
    6_ASSOCIATE_HORTA_PIMENTEL_KARLA --> 7_ANALYST_SANCHEZ_ROJAS_JULIO_ALBERTO
    6_ASSOCIATE_VILLADOZOLA_MOLINA_PATRICIA --> 7_ANALYST_SANCHEZ_ROJAS_JULIO_ALBERTO
    M --> B_DIVISIONAL_FX_NORESTE["DIVISIONAL FX NORESTE"]
    B_DIVISIONAL_FX_NORESTE --> 6_ASSOCIATE_CANEPA_CALDERON_JONATHAN["6. ASSOCIATE (CANEPA CALDERON, JONATHAN)"]
    B_DIVISIONAL_FX_NORESTE --> 6_ASSOCIATE_ROJAS_CHAVEZ_NORBERTO["6. ASSOCIATE (ROJAS CHAVEZ, NORBERTO)"]
    B_DIVISIONAL_FX_NORESTE --> 7_ANALYST_GARCIA_TOVAR_DANIELA_SOFIA["7. ANALYST (GARCIA TOVAR, DANIELA SOFIA)"]
    6_ASSOCIATE_CANEPA_CALDERON_JONATHAN --> 7_ANALYST_GARCIA_TOVAR_DANIELA_SOFIA
    6_ASSOCIATE_ROJAS_CHAVEZ_NORBERTO --> 7_ANALYST_GARCIA_TOVAR_DANIELA_SOFIA
    M --> B_DIVISIONAL_FX_NOROESTE["DIVISIONAL FX NOROESTE"]
    B_DIVISIONAL_FX_NOROESTE --> 6_ASSOCIATE_CASTRO_CASTRO_MARCO_ANTONIO["6. ASSOCIATE (CASTRO CASTRO, MARCO ANTONIO)"]
    B_DIVISIONAL_FX_NOROESTE --> 6_ASSOCIATE_GARCIA_RAMIREZ_JOSE_IRAN["6. ASSOCIATE (GARCIA RAMIREZ, JOSE IRAN)"]
    B_DIVISIONAL_FX_NOROESTE --> 6_ASSOCIATE_VARELA_REYES_CLAUDIA_IVETTE["6. ASSOCIATE (VARELA REYES, CLAUDIA IVETTE)"]
    B_DIVISIONAL_FX_NOROESTE --> 6_ASSOCIATE_VERDUGO_NAVARRO_ARMANDO["6. ASSOCIATE (VERDUGO NAVARRO, ARMANDO)"]
    B_DIVISIONAL_FX_NOROESTE --> 7_ANALYST_POLANCO_ORTIZ_ANA_PALOMA["7. ANALYST (POLANCO ORTIZ, ANA PALOMA)"]
    6_ASSOCIATE_CASTRO_CASTRO_MARCO_ANTONIO --> 7_ANALYST_POLANCO_ORTIZ_ANA_PALOMA
    6_ASSOCIATE_GARCIA_RAMIREZ_JOSE_IRAN --> 7_ANALYST_POLANCO_ORTIZ_ANA_PALOMA
    6_ASSOCIATE_VARELA_REYES_CLAUDIA_IVETTE --> 7_ANALYST_POLANCO_ORTIZ_ANA_PALOMA
    6_ASSOCIATE_VERDUGO_NAVARRO_ARMANDO --> 7_ANALYST_POLANCO_ORTIZ_ANA_PALOMA
    M --> B_DIVISIONAL_FX_OCCIDENTE["DIVISIONAL FX OCCIDENTE"]
    B_DIVISIONAL_FX_OCCIDENTE --> 6_ASSOCIATE_GUTIERREZ_CASSALES_MARTHA_CECILIA["6. ASSOCIATE (GUTIERREZ CASSALES, MARTHA CECILIA)"]
    B_DIVISIONAL_FX_OCCIDENTE --> 6_ASSOCIATE_JIMENEZ_HERNANDEZ_HECTOR_JAVIER["6. ASSOCIATE (JIMENEZ HERNANDEZ, HECTOR JAVIER)"]
    B_DIVISIONAL_FX_OCCIDENTE --> 6_ASSOCIATE_PEREZ_CAMPOS_JORGE_ALBERTO["6. ASSOCIATE (PEREZ CAMPOS, JORGE ALBERTO)"]
    M --> B_DIVISIONAL_FX_SUR["DIVISIONAL FX SUR"]
    B_DIVISIONAL_FX_SUR --> 6_ASSOCIATE_GONZALEZ_CASTAÑEDA_MIGUEL_ANGEL["6. ASSOCIATE (GONZALEZ CASTAÑEDA, MIGUEL ANGEL)"]
    B_DIVISIONAL_FX_SUR --> 7_ANALYST_OSEGUERA_CRAVIOTTO_SARAI["7. ANALYST (OSEGUERA CRAVIOTTO, SARAI)"]
    6_ASSOCIATE_GONZALEZ_CASTAÑEDA_MIGUEL_ANGEL --> 7_ANALYST_OSEGUERA_CRAVIOTTO_SARAI
    M --> B_DIVISIONAL_FX_SURESTE["DIVISIONAL FX SURESTE"]
    B_DIVISIONAL_FX_SURESTE --> 6_ASSOCIATE_SANCHEZ_HERNANDEZ_CARLOS_EDUARDO["6. ASSOCIATE (SANCHEZ HERNANDEZ, CARLOS EDUARDO)"]
    B_DIVISIONAL_FX_SURESTE --> 7_ANALYST_DOMINGUEZ_LOPEZ_RIVERA_JOSE_ESTEBAN["7. ANALYST (DOMINGUEZ LOPEZ RIVERA, JOSE ESTEBAN)"]
    6_ASSOCIATE_SANCHEZ_HERNANDEZ_CARLOS_EDUARDO --> 7_ANALYST_DOMINGUEZ_LOPEZ_RIVERA_JOSE_ESTEBAN
    M --> B_DIVISIONAL_NORESTE_BEySP["DIVISIONAL NORESTE BEySP"]
    M --> B_DIVISIONAL_NORTE_BEYSP["DIVISIONAL NORTE BEYSP"]
    B_DIVISIONAL_NORTE_BEYSP --> 6_ASSOCIATE_MORAILA_MILLAN_MARISOL["6. ASSOCIATE (MORAILA MILLAN, MARISOL)"]
    M --> B_DIVISIONAL_OCCIDENTE_BEYSP["DIVISIONAL OCCIDENTE BEYSP"]
    B_DIVISIONAL_OCCIDENTE_BEYSP --> 6_ASSOCIATE_VALDES_MEDINA_SAGRARIO_NALLELY["6. ASSOCIATE (VALDES MEDINA, SAGRARIO NALLELY)"]
    M --> B_DIVISIONAL_SUR_BEYSP["DIVISIONAL SUR BEYSP"]
    B_DIVISIONAL_SUR_BEYSP --> 6_ASSOCIATE_IZQUIERDO_PATIÑO_CYNTHIA_NALLELY["6. ASSOCIATE (IZQUIERDO PATIÑO, CYNTHIA NALLELY)"]
    M --> B_E-COMMERCE["E-COMMERCE"]
    M --> B_EJECUCION["EJECUCION"]
    B_EJECUCION --> 6_ASSOCIATE_ESPINOSA_GALETTO_MIGUEL_ANGEL["6. ASSOCIATE (ESPINOSA GALETTO, MIGUEL ANGEL)"]
    B_EJECUCION --> 6_ASSOCIATE_LARRIEU_MONTEMAYOR_JUAN_CARLOS["6. ASSOCIATE (LARRIEU MONTEMAYOR, JUAN CARLOS)"]
    B_EJECUCION --> 7_ANALYST_RODRIGUEZ_TELLEZ_BASILIO_RENE["7. ANALYST (RODRIGUEZ TELLEZ, BASILIO RENE)"]
    6_ASSOCIATE_ESPINOSA_GALETTO_MIGUEL_ANGEL --> 7_ANALYST_RODRIGUEZ_TELLEZ_BASILIO_RENE
    6_ASSOCIATE_LARRIEU_MONTEMAYOR_JUAN_CARLOS --> 7_ANALYST_RODRIGUEZ_TELLEZ_BASILIO_RENE
    M --> B_EM_LOCAL_RATES_MEXICO["EM LOCAL RATES MEXICO"]
    M --> B_EQUITY_MEXICO["EQUITY MEXICO"]
    B_EQUITY_MEXICO --> 6_ASSOCIATE_ANTIMO_BECERRA_ANA_JIMENA["6. ASSOCIATE (ANTIMO BECERRA, ANA JIMENA)"]
    B_EQUITY_MEXICO --> 7_ANALYST_BENITEZ_GONZALEZ_ALFREDO["7. ANALYST (BENITEZ GONZALEZ, ALFREDO)"]
    6_ASSOCIATE_ANTIMO_BECERRA_ANA_JIMENA --> 7_ANALYST_BENITEZ_GONZALEZ_ALFREDO
    M --> B_EQUITY_TRADING_MEXICO["EQUITY TRADING MEXICO"]
    B_EQUITY_TRADING_MEXICO --> 6_ASSOCIATE_HERMOSA_MONTES_DE_OCA_CHRISTIAN_RICARDO["6. ASSOCIATE (HERMOSA MONTES DE OCA, CHRISTIAN RICARDO)"]
    B_EQUITY_TRADING_MEXICO --> 7_ANALYST_GARZA_MORENO_PABLO["7. ANALYST (GARZA MORENO, PABLO)"]
    6_ASSOCIATE_HERMOSA_MONTES_DE_OCA_CHRISTIAN_RICARDO --> 7_ANALYST_GARZA_MORENO_PABLO
    M --> B_ESTRATEGIA_RESEARCH_MEXICO["ESTRATEGIA RESEARCH MEXICO"]
    B_ESTRATEGIA_RESEARCH_MEXICO --> 6_ASSOCIATE_SOLIS_LANDAVERDE_EDITH_CLAUDIA["6. ASSOCIATE (SOLIS LANDAVERDE, EDITH CLAUDIA)"]
    B_ESTRATEGIA_RESEARCH_MEXICO --> 7_ANALYST_BAUTISTA_VIVANCO_CRISTINA_INES["7. ANALYST (BAUTISTA VIVANCO, CRISTINA INES)"]
    6_ASSOCIATE_SOLIS_LANDAVERDE_EDITH_CLAUDIA --> 7_ANALYST_BAUTISTA_VIVANCO_CRISTINA_INES
    B_ESTRATEGIA_RESEARCH_MEXICO --> 7_ANALYST_GONZALEZ_ROBLEDO_ROBERTO["7. ANALYST (GONZALEZ ROBLEDO, ROBERTO)"]
    6_ASSOCIATE_SOLIS_LANDAVERDE_EDITH_CLAUDIA --> 7_ANALYST_GONZALEZ_ROBLEDO_ROBERTO
    B_ESTRATEGIA_RESEARCH_MEXICO --> 7_ANALYST_ZARATE_GARAY_YAIR_ANTONIO["7. ANALYST (ZARATE GARAY, YAIR ANTONIO)"]
    6_ASSOCIATE_SOLIS_LANDAVERDE_EDITH_CLAUDIA --> 7_ANALYST_ZARATE_GARAY_YAIR_ANTONIO
    M --> B_ESTRATEGIA_RESEARCH_MEXICO_1["ESTRATEGIA RESEARCH MEXICO 1"]
    B_ESTRATEGIA_RESEARCH_MEXICO_1 --> 6_ASSOCIATE_FLORES_ALVAREZ_SUSANA["6. ASSOCIATE (FLORES ALVAREZ, SUSANA)"]
    B_ESTRATEGIA_RESEARCH_MEXICO_1 --> 6_ASSOCIATE_ITURRIBARRIA_ARAUJO_MIGUEL_ANGEL["6. ASSOCIATE (ITURRIBARRIA ARAUJO, MIGUEL ANGEL)"]
    B_ESTRATEGIA_RESEARCH_MEXICO_1 --> 6_ASSOCIATE_REYES_LAGUNAS_MOISES_EMMANUEL["6. ASSOCIATE (REYES LAGUNAS, MOISES EMMANUEL)"]
    B_ESTRATEGIA_RESEARCH_MEXICO_1 --> 7_ANALYST_ALCARAZ_IRIBERRI_KITZIA["7. ANALYST (ALCARAZ IRIBERRI, KITZIA)"]
    6_ASSOCIATE_FLORES_ALVAREZ_SUSANA --> 7_ANALYST_ALCARAZ_IRIBERRI_KITZIA
    6_ASSOCIATE_ITURRIBARRIA_ARAUJO_MIGUEL_ANGEL --> 7_ANALYST_ALCARAZ_IRIBERRI_KITZIA
    6_ASSOCIATE_REYES_LAGUNAS_MOISES_EMMANUEL --> 7_ANALYST_ALCARAZ_IRIBERRI_KITZIA
    M --> B_ESTRATEGIA_RESEARCH_MEXICO_2["ESTRATEGIA RESEARCH MEXICO 2"]
    B_ESTRATEGIA_RESEARCH_MEXICO_2 --> 7_ANALYST_SERROS_MARTINEZ_DIANA_MELISSA["7. ANALYST (SERROS MARTINEZ, DIANA MELISSA)"]
    M --> B_Execution_Americas["Execution Americas"]
    B_Execution_Americas --> 6_ASSOCIATE_FUENTES_CASTAÑEDA_MARIO_ENRIQUE["6. ASSOCIATE (FUENTES CASTAÑEDA, MARIO ENRIQUE)"]
    B_Execution_Americas --> 6_ASSOCIATE_GARCIA_ROBLES_JULIO_ALFREDO["6. ASSOCIATE (GARCIA ROBLES, JULIO ALFREDO)"]
    M --> B_FX_and_RATES["FX & RATES"]
    B_FX_and_RATES --> 6_ASSOCIATE_RESENDIZ_BECERRA_LUIS_FERNANDO["6. ASSOCIATE (RESENDIZ BECERRA, LUIS FERNANDO)"]
    B_FX_and_RATES --> 7_ANALYST_ANAYA_CASTAÑEDA_MARIANA["7. ANALYST (ANAYA CASTAÑEDA, MARIANA)"]
    6_ASSOCIATE_RESENDIZ_BECERRA_LUIS_FERNANDO --> 7_ANALYST_ANAYA_CASTAÑEDA_MARIANA
    B_FX_and_RATES --> 7_ANALYST_GARCIA_GARCIA_MARGARITA_FRANCISCA["7. ANALYST (GARCIA GARCIA, MARGARITA FRANCISCA)"]
    6_ASSOCIATE_RESENDIZ_BECERRA_LUIS_FERNANDO --> 7_ANALYST_GARCIA_GARCIA_MARGARITA_FRANCISCA
    M --> B_FX_CORPORATE_SALES["FX CORPORATE SALES"]
    B_FX_CORPORATE_SALES --> 6_ASSOCIATE_MONTUFAR_DICHI_SAHARAID["6. ASSOCIATE (MONTUFAR DICHI, SAHARAID)"]
    B_FX_CORPORATE_SALES --> 6_ASSOCIATE_MORALES_RODRIGUEZ_PATRICIA_GESELE["6. ASSOCIATE (MORALES RODRIGUEZ, PATRICIA GESELE)"]
    B_FX_CORPORATE_SALES --> 6_ASSOCIATE_VELOZ_CARO_DEL_CASTILLO_MIGUEL_ANGEL["6. ASSOCIATE (VELOZ CARO DEL CASTILLO, MIGUEL ANGEL)"]
    B_FX_CORPORATE_SALES --> 7_ANALYST_MORALES_MANZO_AIDA_ARACELI["7. ANALYST (MORALES MANZO, AIDA ARACELI)"]
    6_ASSOCIATE_MONTUFAR_DICHI_SAHARAID --> 7_ANALYST_MORALES_MANZO_AIDA_ARACELI
    6_ASSOCIATE_MORALES_RODRIGUEZ_PATRICIA_GESELE --> 7_ANALYST_MORALES_MANZO_AIDA_ARACELI
    6_ASSOCIATE_VELOZ_CARO_DEL_CASTILLO_MIGUEL_ANGEL --> 7_ANALYST_MORALES_MANZO_AIDA_ARACELI
    M --> B_FX_STRATEGY["FX STRATEGY"]
    B_FX_STRATEGY --> 7_ANALYST_ESTRELLA_HERNANDEZ_JANET["7. ANALYST (ESTRELLA HERNANDEZ, JANET)"]
    M --> B_FX_TRADING["FX TRADING"]
    B_FX_TRADING --> 6_ASSOCIATE_ARMENTA_RODRIGUEZ_CARLOS_ENRIQUE["6. ASSOCIATE (ARMENTA RODRIGUEZ, CARLOS ENRIQUE)"]
    B_FX_TRADING --> 6_ASSOCIATE_AZANO_GONZALEZ_ENRIQUE_TADAO["6. ASSOCIATE (AZANO GONZALEZ, ENRIQUE TADAO)"]
    B_FX_TRADING --> 6_ASSOCIATE_PORRAS_ARANDA_JUAN_PABLO["6. ASSOCIATE (PORRAS ARANDA, JUAN PABLO)"]
    B_FX_TRADING --> 6_ASSOCIATE_ROJAS_SANCHEZ_IBHAR_ADOLFO["6. ASSOCIATE (ROJAS SANCHEZ, IBHAR ADOLFO)"]
    B_FX_TRADING --> 7_ANALYST_TORRES_PULIDO_AMANDA_IVONNE["7. ANALYST (TORRES PULIDO, AMANDA IVONNE)"]
    6_ASSOCIATE_ARMENTA_RODRIGUEZ_CARLOS_ENRIQUE --> 7_ANALYST_TORRES_PULIDO_AMANDA_IVONNE
    6_ASSOCIATE_AZANO_GONZALEZ_ENRIQUE_TADAO --> 7_ANALYST_TORRES_PULIDO_AMANDA_IVONNE
    6_ASSOCIATE_PORRAS_ARANDA_JUAN_PABLO --> 7_ANALYST_TORRES_PULIDO_AMANDA_IVONNE
    6_ASSOCIATE_ROJAS_SANCHEZ_IBHAR_ADOLFO --> 7_ANALYST_TORRES_PULIDO_AMANDA_IVONNE
    M --> B_GIN_BPyP_MÉXICO["GIN BPyP MÉXICO"]
    M --> B_GIN_EMPRESAS_MÉXICO["GIN EMPRESAS MÉXICO"]
    B_GIN_EMPRESAS_MÉXICO --> 6_ASSOCIATE_CONDE_ROMERO_SANDRA_ELENA["6. ASSOCIATE (CONDE ROMERO, SANDRA ELENA)"]
    B_GIN_EMPRESAS_MÉXICO --> 7_ANALYST_LECHUGA_SERRANO_LORENA_LUCIA["7. ANALYST (LECHUGA SERRANO, LORENA LUCIA)"]
    6_ASSOCIATE_CONDE_ROMERO_SANDRA_ELENA --> 7_ANALYST_LECHUGA_SERRANO_LORENA_LUCIA
    B_GIN_EMPRESAS_MÉXICO --> 7_ANALYST_MARQUEZ_GUERRERO_LUIS_ARMANDO["7. ANALYST (MARQUEZ GUERRERO, LUIS ARMANDO)"]
    6_ASSOCIATE_CONDE_ROMERO_SANDRA_ELENA --> 7_ANALYST_MARQUEZ_GUERRERO_LUIS_ARMANDO
    M --> B_GLOBAL_CORPORATE_SALES["GLOBAL CORPORATE SALES"]
    M --> B_GLOBAL_CREDIT["GLOBAL CREDIT"]
    M --> B_GLOBAL_EM_FLOW_SALES["GLOBAL EM FLOW SALES"]
    M --> B_GLOBAL_INTERNAL_NETWORKS["GLOBAL INTERNAL NETWORKS"]
    M --> B_GLOBAL_INVESTMENT_STRATEGY["GLOBAL INVESTMENT STRATEGY"]
    M --> B_GLOBAL_MACRO["GLOBAL MACRO"]
    M --> B_GLOBAL_MARKETS["GLOBAL MARKETS"]
    M --> B_GLOBAL_MARKETS_ECOMMERCE_SALES_I["GLOBAL MARKETS ECOMMERCE SALES I"]
    B_GLOBAL_MARKETS_ECOMMERCE_SALES_I --> 6_ASSOCIATE_GOMEZ_LASTRA_JOSE_MARIA["6. ASSOCIATE (GOMEZ LASTRA, JOSE MARIA)"]
    B_GLOBAL_MARKETS_ECOMMERCE_SALES_I --> 6_ASSOCIATE_JIMENEZ_DOMINGUEZ_LILIANA["6. ASSOCIATE (JIMENEZ DOMINGUEZ, LILIANA)"]
    M --> B_GLOBAL_STRUCTURING["GLOBAL STRUCTURING"]
    M --> B_GM_MEXICO["GM MEXICO"]
    M --> B_GM_SOUTH_AMERICA["GM SOUTH AMERICA"]
    M --> B_GM_SPAIN_I["GM SPAIN I"]
    B_GM_SPAIN_I --> 7_ANALYST_CERVANTES_MANNINO_GIULIANA_ALICIA["7. ANALYST (CERVANTES MANNINO, GIULIANA ALICIA)"]
    M --> B_GSS_CORPORATES_and_GIN["GSS CORPORATES & GIN"]
    B_GSS_CORPORATES_and_GIN --> 6_ASSOCIATE_TORRES_LANDA_GONZALEZ_CONSTANZA["6. ASSOCIATE (TORRES LANDA GONZALEZ, CONSTANZA)"]
    B_GSS_CORPORATES_and_GIN --> 6_ASSOCIATE_VILLA_BAHENA_BEATRIZ["6. ASSOCIATE (VILLA BAHENA, BEATRIZ)"]
    M --> B_GSS_INSTITUTIONAL_INVESTORS["GSS INSTITUTIONAL INVESTORS"]
    B_GSS_INSTITUTIONAL_INVESTORS --> 6_ASSOCIATE_MARTINEZ_QUEZADA_CARLOS_ARTURO["6. ASSOCIATE (MARTINEZ QUEZADA, CARLOS ARTURO)"]
    B_GSS_INSTITUTIONAL_INVESTORS --> 7_ANALYST_ANDRADE_PAZ_EDGAR_ALAN["7. ANALYST (ANDRADE PAZ, EDGAR ALAN)"]
    6_ASSOCIATE_MARTINEZ_QUEZADA_CARLOS_ARTURO --> 7_ANALYST_ANDRADE_PAZ_EDGAR_ALAN
    B_GSS_INSTITUTIONAL_INVESTORS --> 7_ANALYST_ZUCCOLOTTO_RODRIGUEZ_JOSE_OTHONIEL["7. ANALYST (ZUCCOLOTTO RODRIGUEZ, JOSE OTHONIEL)"]
    6_ASSOCIATE_MARTINEZ_QUEZADA_CARLOS_ARTURO --> 7_ANALYST_ZUCCOLOTTO_RODRIGUEZ_JOSE_OTHONIEL
    M --> B_GSS_MÉXICO["GSS MÉXICO"]
    M --> B_INVESTMENT_SOLUTIONS["INVESTMENT SOLUTIONS"]
    M --> B_INVESTORS_MÉXICO["INVESTORS MÉXICO"]
    B_INVESTORS_MÉXICO --> 6_ASSOCIATE_ALVAREZ_KURI_JUAN_PABLO["6. ASSOCIATE (ALVAREZ KURI, JUAN PABLO)"]
    B_INVESTORS_MÉXICO --> 7_ANALYST_AGUILAR_SANCHEZ_LAURA_BERENICE["7. ANALYST (AGUILAR SANCHEZ, LAURA BERENICE)"]
    6_ASSOCIATE_ALVAREZ_KURI_JUAN_PABLO --> 7_ANALYST_AGUILAR_SANCHEZ_LAURA_BERENICE
    M --> B_IR_VOLATILITIES["IR VOLATILITIES"]
    B_IR_VOLATILITIES --> 7_ANALYST_GONZALEZ_SANCHEZ_ANDREA["7. ANALYST (GONZALEZ SANCHEZ, ANDREA)"]
    M --> B_METRO,_GOBIERNO_and_CORPORATIVO["METRO, GOBIERNO & CORPORATIVO"]
    B_METRO,_GOBIERNO_and_CORPORATIVO --> 6_ASSOCIATE_GARCIA_RUIZ_GISELA_IRAIS["6. ASSOCIATE (GARCIA RUIZ, GISELA IRAIS)"]
    B_METRO,_GOBIERNO_and_CORPORATIVO --> 6_ASSOCIATE_KANG_MEJIA_SUYI["6. ASSOCIATE (KANG MEJIA, SUYI)"]
    B_METRO,_GOBIERNO_and_CORPORATIVO --> 6_ASSOCIATE_SANTOYO_VALLE_LAURA_PATRICIA["6. ASSOCIATE (SANTOYO VALLE, LAURA PATRICIA)"]
    M --> B_QBS_MEXICO_and_USA["QBS MEXICO & USA"]
    B_QBS_MEXICO_and_USA --> 6_ASSOCIATE_FIGUEROA_FERRER_ALEXEIS["6. ASSOCIATE (FIGUEROA FERRER, ALEXEIS)"]
    B_QBS_MEXICO_and_USA --> 6_ASSOCIATE_FLORES_HERRERA_JUAN_MANUEL["6. ASSOCIATE (FLORES HERRERA, JUAN MANUEL)"]
    B_QBS_MEXICO_and_USA --> 6_ASSOCIATE_MARTINEZ_WARNHOLTZ_BRUNO["6. ASSOCIATE (MARTINEZ WARNHOLTZ, BRUNO)"]
    B_QBS_MEXICO_and_USA --> 6_ASSOCIATE_RAMIREZ_CANO_JUAN_CARLOS["6. ASSOCIATE (RAMIREZ CANO, JUAN CARLOS)"]
    B_QBS_MEXICO_and_USA --> 6_ASSOCIATE_VAZQUEZ_LOPEZ_LUIS_IRAN["6. ASSOCIATE (VAZQUEZ LOPEZ, LUIS IRAN)"]
    B_QBS_MEXICO_and_USA --> 6_ASSOCIATE_ZAMUDIO_ALPIZAR_ARTURO["6. ASSOCIATE (ZAMUDIO ALPIZAR, ARTURO)"]
    M --> B_RATES_LONG_TERM["RATES LONG TERM"]
    B_RATES_LONG_TERM --> 6_ASSOCIATE_LOPEZ_CALDERON_RAQUEL["6. ASSOCIATE (LOPEZ CALDERON, RAQUEL)"]
    B_RATES_LONG_TERM --> 6_ASSOCIATE_OVEJAS_SANCHEZ_IÑAKI["6. ASSOCIATE (OVEJAS SANCHEZ, IÑAKI)"]
    B_RATES_LONG_TERM --> 7_ANALYST_HORTON_MOTA_MEGAN["7. ANALYST (HORTON MOTA, MEGAN)"]
    6_ASSOCIATE_LOPEZ_CALDERON_RAQUEL --> 7_ANALYST_HORTON_MOTA_MEGAN
    6_ASSOCIATE_OVEJAS_SANCHEZ_IÑAKI --> 7_ANALYST_HORTON_MOTA_MEGAN
    M --> B_RATES_SHORT_TERM_and_LINKERS["RATES SHORT TERM & LINKERS"]
    B_RATES_SHORT_TERM_and_LINKERS --> 6_ASSOCIATE_CORIA_GUERRERO_HECTOR_DANIEL["6. ASSOCIATE (CORIA GUERRERO, HECTOR DANIEL)"]
    B_RATES_SHORT_TERM_and_LINKERS --> 7_ANALYST_HERNANDEZ_CRUZ_JOSE_ALBERTO["7. ANALYST (HERNANDEZ CRUZ, JOSE ALBERTO)"]
    6_ASSOCIATE_CORIA_GUERRERO_HECTOR_DANIEL --> 7_ANALYST_HERNANDEZ_CRUZ_JOSE_ALBERTO
    M --> B_REDES_MEXICO_1["REDES MEXICO 1"]
    B_REDES_MEXICO_1 --> 6_ASSOCIATE_BORGES_LIZAMA_ANA_LAURA["6. ASSOCIATE (BORGES LIZAMA, ANA LAURA)"]
    M --> B_RESEARCH_CREDIT_MEXICO["RESEARCH CREDIT MEXICO"]
    B_RESEARCH_CREDIT_MEXICO --> 7_ANALYST_PEÑA_DELGADO_ANDREA["7. ANALYST (PEÑA DELGADO, ANDREA)"]
    M --> B_RESEARCH_EQUITIES["RESEARCH EQUITIES"]
    M --> B_STRUCTURED_SALES_GIN["STRUCTURED SALES GIN"]
    B_STRUCTURED_SALES_GIN --> 7_ANALYST_MORON_GUERRERO_CAROLINA_SUE["7. ANALYST (MORON GUERRERO, CAROLINA SUE)"]
    B_STRUCTURED_SALES_GIN --> 7_ANALYST_ORTEGA_YAÑEZ_CAMILA_VALENTINA["7. ANALYST (ORTEGA YAÑEZ, CAMILA VALENTINA)"]
    M --> B_STRUCTURED_SALES_II["STRUCTURED SALES II"]
    B_STRUCTURED_SALES_II --> 6_ASSOCIATE_MARTINEZ_GARCIA_DE_ALBA_GABRIELA_ANAEL["6. ASSOCIATE (MARTINEZ GARCIA DE ALBA, GABRIELA ANAEL)"]
    M --> B_SYSTEMATICS_and_REVENUE_DISCOVER["SYSTEMATICS & REVENUE DISCOVER"]
    B_SYSTEMATICS_and_REVENUE_DISCOVER --> 6_ASSOCIATE_HERNANDEZ_LEON_JULIO_CESAR["6. ASSOCIATE (HERNANDEZ LEON, JULIO CESAR)"]
    B_SYSTEMATICS_and_REVENUE_DISCOVER --> 6_ASSOCIATE_RAMOS_ALVAREZ_SAMUEL_ALBERTO["6. ASSOCIATE (RAMOS ALVAREZ, SAMUEL ALBERTO)"]
    B_SYSTEMATICS_and_REVENUE_DISCOVER --> 6_ASSOCIATE_SOTO_VAZQUEZ_ENRIQUE["6. ASSOCIATE (SOTO VAZQUEZ, ENRIQUE)"]
    B_SYSTEMATICS_and_REVENUE_DISCOVER --> 7_ANALYST_AGUILAR_CAZARES_RODRIGO_ALBERTO["7. ANALYST (AGUILAR CAZARES, RODRIGO ALBERTO)"]
    6_ASSOCIATE_HERNANDEZ_LEON_JULIO_CESAR --> 7_ANALYST_AGUILAR_CAZARES_RODRIGO_ALBERTO
    6_ASSOCIATE_RAMOS_ALVAREZ_SAMUEL_ALBERTO --> 7_ANALYST_AGUILAR_CAZARES_RODRIGO_ALBERTO
    6_ASSOCIATE_SOTO_VAZQUEZ_ENRIQUE --> 7_ANALYST_AGUILAR_CAZARES_RODRIGO_ALBERTO
    M --> B_TRADER_CVA["TRADER CVA"]
    B_TRADER_CVA --> 6_ASSOCIATE_GOMEZ_CASTELLANOS_ANDREA_ISABEL["6. ASSOCIATE (GOMEZ CASTELLANOS, ANDREA ISABEL)"]
    B_TRADER_CVA --> 7_ANALYST_CASTRO_ARANDAY_DANIELA["7. ANALYST (CASTRO ARANDAY, DANIELA)"]
    6_ASSOCIATE_GOMEZ_CASTELLANOS_ANDREA_ISABEL --> 7_ANALYST_CASTRO_ARANDAY_DANIELA
    B_TRADER_CVA --> 7_ANALYST_GARCIA_ALDACO_MELISSA["7. ANALYST (GARCIA ALDACO, MELISSA)"]
    6_ASSOCIATE_GOMEZ_CASTELLANOS_ANDREA_ISABEL --> 7_ANALYST_GARCIA_ALDACO_MELISSA
    M --> B_VEHICLES["VEHICLES"]
    B_VEHICLES --> 6_ASSOCIATE_DIVES_RANGEL_ADRIAN["6. ASSOCIATE (DIVES RANGEL, ADRIAN)"]
    M --> B_VENTAS_FX_I["VENTAS FX I"]
    B_VENTAS_FX_I --> 6_ASSOCIATE_CASTILLO_AGUILAR_MIGUEL_ANGEL["6. ASSOCIATE (CASTILLO AGUILAR, MIGUEL ANGEL)"]
    B_VENTAS_FX_I --> 6_ASSOCIATE_TARAZON_LOPEZ_EDUARDO["6. ASSOCIATE (TARAZON LOPEZ, EDUARDO)"]
    B_VENTAS_FX_I --> 6_ASSOCIATE_TOSTADO_LARA_JOSE_ABRAHAM["6. ASSOCIATE (TOSTADO LARA, JOSE ABRAHAM)"]
    B_VENTAS_FX_I --> 6_ASSOCIATE_VILLALPANDO_HALGRAVES_ENRIQUE["6. ASSOCIATE (VILLALPANDO HALGRAVES, ENRIQUE)"]
    M --> B_VENTAS_FX_I_1["VENTAS FX I 1"]
    B_VENTAS_FX_I_1 --> 6_ASSOCIATE_GARCIA_OROZCO_MANUEL["6. ASSOCIATE (GARCIA OROZCO, MANUEL)"]
    B_VENTAS_FX_I_1 --> 6_ASSOCIATE_OLIVAS_MANCILLA_EDGAR["6. ASSOCIATE (OLIVAS MANCILLA, EDGAR)"]
    B_VENTAS_FX_I_1 --> 7_ANALYST_FIERRO_NES_ILSE_YALIL["7. ANALYST (FIERRO NES, ILSE YALIL)"]
    6_ASSOCIATE_GARCIA_OROZCO_MANUEL --> 7_ANALYST_FIERRO_NES_ILSE_YALIL
    6_ASSOCIATE_OLIVAS_MANCILLA_EDGAR --> 7_ANALYST_FIERRO_NES_ILSE_YALIL
    B_VENTAS_FX_I_1 --> 7_ANALYST_LASCURAIN_LOZA_LAURA_EVELYN["7. ANALYST (LASCURAIN LOZA, LAURA EVELYN)"]
    6_ASSOCIATE_GARCIA_OROZCO_MANUEL --> 7_ANALYST_LASCURAIN_LOZA_LAURA_EVELYN
    6_ASSOCIATE_OLIVAS_MANCILLA_EDGAR --> 7_ANALYST_LASCURAIN_LOZA_LAURA_EVELYN


```
