# 2020_brazil_elections
Data and analysis exploring 2020 Brazil elections.

## DATA

1. **despesas_2020_abridged.txt**

* ano ------------------------------- discrete
* cargo ----------------------------- qualit. ordinal
* turno ----------------------------- qualit. ordinal
* uf -------------------------------- qualit. nominal
* muni_code ------------------------- qualit. nominal
* muni ------------------------------ qualit. nominal
* cnpj_campanha --------------------- qualit. nominal
* numero_cand ----------------------- qualit. nominal
* nome_cand ------------------------- qualit. nominal
* cpf_cand -------------------------- qualit. nominal
* partido --------------------------- qualit. nominal
* cpf_cnpj_fornecedor --------------- qualit. nominal
* nome_fornecedor ------------------- qualit. nominal
* cod_origem_despesa ---------------- qualit. nominal
* desc_geral ------------------------ qualit. nominal
* desc_detalhe ---------------------- qualit. nominal
* valor ------------------------------ continuous

2. **prefeitos_2020_abridged.txt**

* ano_eleicao ----------------------- discrete
* num_turno ------------------------- qualit. ordinal
* sigla_uf -------------------------- qualit. nominal
* sigla_ue -------------------------- qualit. nominal
* numero_candidato ------------------ qualit. nominal
* cpf_candidato --------------------- qualit. nominal
* nome_urna_candidato --------------- qualit. nominal
* sigla_partido --------------------- qualit. nominal
* composicao_legenda ---------------- qualit. nominal
* num_titulo_eleitoral_candidato ---- qualit. nominal
* descricao_sexo -------------------- qualit. nominal
* descricao_grau_instrucao ---------- qualit. ordinal
* elected --------------------------- qualit. ordinal

3. **results_2020_abridged.txt**

* ano_eleicao ----------------------- discrete
* num_turno ------------------------- qualit. ordinal
* sigla_uf -------------------------- qualit. nominal
* muni_code ------------------------- qualit. nominal
* sigla_partido_hoje ---------------- qualit. nominal
* total_votes_race ------------------ discrete
* cand_votes ------------------------ discrete
* max_votes ------------------------- discrete
* runner_up -------------------------- discrete

