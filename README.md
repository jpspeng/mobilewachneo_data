# Deidentified dataset for "Associations between text communication engagement and maternal-neonatal outcomes in the Mobile WACh NEO Trial"

The deidentified dataset for the manuscript "Associations between text communication engagement and maternal-neonatal outcomes in the Mobile WACh NEO Trial" (Peng et al., 2025, submitted to *PLOS Digital Health*) is included in this Github repo. 

Here is a basic description of the dataset: 

#### General

| Variable       | Description                                            |
| -------------- | ------------------------------------------------------ |
| `Study.ID`     | Anonymized participant ID (numeric, randomly assigned) |
| `site`         | Study site (`Site 1` to `Site 6`)                      |
| `intervention` | Intervention group assignment                          |

#### Demographics & Baseline

| Variable       | Description                                   |
| -------------- | --------------------------------------------- |
| `en_age`       | Age at enrollment                             |
| `age_group`    | Age category (e.g. 14–19, 20–24, etc.)        |
| `en_education` | Completed secondary education (yes/no)        |
| `en_employ`    | Currently employed (yes/no)                   |
| `en_marital`   | Married or living with partner (yes/no)       |
| `en_crowd`     | Household crowding (≥3 per room)              |
| `language`     | Preferred language (English, Swahili, or Luo) |
| `sc_read`      | Can read SMS independently (yes/no)           |
| `sc_write`     | Can write SMS independently (yes/no)          |
| `oh_primigrav` | First pregnancy (yes/no)                      |
| `c_section`    | Delivered via C-section (yes/no)              |

#### Psychosocial Measures

| Variable              | Description                                  |
| --------------------- | -------------------------------------------- |
| `dp_ind`              | Depression indicator at endpoint             |
| `dp_ind_bl`           | Depression indicator at baseline             |
| `dp_score`            | Depression score at endpoint                 |
| `dp_score_bl`         | Depression score at baseline                 |
| `ss_meanscore_100`    | Social support score (scaled to 100)         |
| `ss_meanscore`        | Raw social support score (endpoint)          |
| `ss_meanscore_change` | Change in social support score from baseline |
| `se_sumscore`         | Self-efficacy score at endpoint              |
| `se_sumscore_bl`      | Self-efficacy score at baseline              |
| `se_sumscore_change`  | Change in self-efficacy score from baseline  |
| `ip_any`              | Any IPV reported at endpoint                 |
| `ip_any_bl`           | Any IPV reported at baseline                 |

#### Health Knowledge

| Variable           | Description                             |
| ------------------ | --------------------------------------- |
| `nds_score`        | Danger sign knowledge score at endpoint |
| `nds_score_bl`     | Danger sign knowledge score at baseline |
| `nds_score_change` | Change in knowledge score from baseline |

#### 💬 Messaging Engagement

| Variable                        | Description                                    |
| ------------------------------- | ---------------------------------------------- |
| `in_messages*`                  | Incoming messages from participant             |
| `out_messages*`                 | Outgoing messages to participant               |
| `auto_messages*`                | Automated messages                             |
| `nonauto_messages*`             | Combined participant + nurse messages          |
| `*_norm`                        | Normalized by number of weeks                  |
| `*_length`, `*_length_norm`     | Total characters (raw and normalized)          |
| `*_pre_delivery`, `*_pre_2week` | Restricted to pre-delivery or pre–2-week visit |

#### Outcomes

| Variable                | Description                               |
| ----------------------- | ----------------------------------------- |
| `neonat_death_fb`       | Neonatal death reported at follow-up      |
| `early_neonat_death_fb` | Early neonatal death (within 7 days)      |
| `stillbirth_fb`         | Stillbirth reported at follow-up          |
| `stillbirth_sb`         | Stillbirth identified via screening logic |
| `inf_hosp_fb`           | Any infant hospitalization                |
| `hosp_at_del`           | Infant hospitalized at delivery           |
| `hosp_post_del`         | Infant hospitalized after discharge       |
| `bf_initiatebf`         | Breastfeeding initiated within 1 hour     |
| `bf_otherfood`          | Infant given other food or drink          |
| `dr_appthermcare_ind`   | Appropriate thermal care                  |
| `dr_appcordcare_ind`    | Appropriate cord care                     |
| `kmc_home_wk2`          | KMC at home in first 2 weeks              |
| `kmc_ind_wk2`           | KMC at home ≥10 days in first 2 weeks     |
| `death_age_fb`          | Age at death (in days)                    |
| `nnd_discharge_fb`      | Died before hospital discharge            |
| `admit1_del_fb`         | Admitted during delivery                  |
| `admit2_fb`             | Admitted after delivery                   |

#### Clinical

| Variable      | Description                          |
| ------------- | ------------------------------------ |
| `ega_del_gs`  | Gestational age at delivery (weeks)  |
| `birthweight` | Birthweight (grams)                  |
| `preterm_gs`  | Preterm (<37 weeks GA)               |
| `dr_deltype`  | Delivery type (vaginal or C-section) |

#### Messaging Track Flags

| Variable           | Description                                   |
| ------------------ | --------------------------------------------- |
| `ever_depression`  | Ever received depression track messages       |
| `ever_first_time`  | Ever received first-time mother track         |
| `ever_pre_term`    | Ever received preterm birth track             |
| `ever_infant_loss` | Ever received infant loss track               |
| `only_general`     | Only received general (non-targeted) messages |
| `baseline_track`   | Track assigned at baseline                    |
| `delivery_track`   | Track assigned at delivery                    |
| `wk2_track`        | Track assigned at week 2                      |
| `wk6_track`        | Track assigned at week 6                      |

