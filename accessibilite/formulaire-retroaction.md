---
altLangPage: /accessibility/feedback-form.html
breadcrumbs: false
dateModified: 2022-11-29
description: "Fournissez une rétroaction sur le plan d’accessibilité de [nom de l’institution], les obstacles que vous avez rencontrés ou toute question liée à l’accessibilité."
layout: form
nomenu: true
noReportProblem: true
nositesearch: true
share: false
title: "Formulaire de rétroaction sur l’accessibilité"
---
<h1 property="name" id="wb-cont" dir="ltr">Formulaire de rétroaction sur l’accessibilité</h1>
<div class="row mrgn-tp-lg">
  <div class="col-md-8">
    <p>Fournissez une rétroaction sur le plan d’accessibilité de [nom de l’institution], les obstacles que vous avez rencontrés ou toute question liée à l’accessibilité.</p>
    <p>Vous pouvez consulter le <a href="processus-retroaction.html">processus de rétroaction</a> sur l’accessibilité pour découvrir d’autres façons de fournir une rétroaction et comment nous utilisons votre rétroaction.</p>
    <details class="mrgn-tp-lg">
      <summary>Avis de confidentialité</summary>
      <div class="row mrgn-tp-lg">
        <div class="col-md-12">
          <p>[inclure la déclaration de confidentialité de votre institution]</p>
          <h2>[Modèle de clause de confidentialité]</h2>
          <p>La collecte de renseignements personnels est autorisée par l’article 7(1)(a) et l’article 70 de la <em>Loi sur l’accessibilité du Canada</em>. Ces renseignements personnels sont recueillis par le [bureau ou coordonnateur de l’accessibilité] pour se conformer à la <em>Loi sur l’accessibilité du Canada</em> en créant un mécanisme de collecte des commentaires et en étant en mesure de répondre à la personne concernée et de reconnaître que ses commentaires ont été recueillis et comment ils ont été traités.</p>
          <p>La collecte et l’utilisation de ces informations personnelles sont conformes à <em>la Loi sur la protection des renseignements personnels</em>. Ce mécanisme est utilisé pour recueillir des commentaires internes et externes sur notre plan d’accessibilité, les futurs rapports d’avancement, ainsi que l’accessibilité et les obstacles à l’accessibilité dans le cadre du travail effectué dans chaque service.</p>
          <p>Les renseignements personnels recueillis sont décrits dans le fichier de renseignements personnels POU 938 - Activités de sensibilisation et seront conservés pendant 7 ans. En vertu de la <em>Loi sur la protection des renseignements personnels</em>, vous avez le droit d’accéder à vos renseignements personnels et de les corriger. Pour exercer l’un ou l’autre de ces droits, communiquez avec le coordonnateur de l’AIPRP de [nom de l’institution]. Si vous n’êtes pas satisfait de la réponse de [nom de l’institution] à vos préoccupations en matière de protection des renseignements personnels, vous pouvez communiquer avec le Commissariat à la protection de la vie privée du Canada.</p>
          <h2 class="h3">Coordonnées</h2>
          <ul class="mrgn-tp-lg">
            <li>Coordonnateur de l’AIPRP de [nom de l’institution]</li>
            <li><a href="https://www.priv.gc.ca/fr/">Commissariat à la protection de la vie privée du Canada</a></li>
          </ul>
          <h2 class="h3">References</h2>
          <ul class="mrgn-tp-lg">
            <li><a href="https://www.laws-lois.justice.gc.ca/fra/lois/a-0.6/">Loi canadienne sur l’accessibilité</a>
              <ul>
                <li><a href="https://www.laws-lois.justice.gc.ca/fra/lois/a-0.6/page-1.html#h-1139882">Article 7(1)(a)</a></li>
                <li><a href="https://www.laws-lois.justice.gc.ca/fra/lois/a-0.6/page-5.html#h-1140478">Article 70</a></li>
              </ul>
            </li>
            <li><a href="https://laws-lois.justice.gc.ca/ENG/ACTS/P-21/index.html">Loi sur la protection des renseignements personnels</a></li>
            <li><a href="https://www.canada.ca/fr/secretariat-conseil-tresor/services/acces-information-protection-reseignements-personnels/acces-information/renseignements-programmes-fonds-renseignements/fichiers-renseignements-personnels-ordinaires.html#pou938">Fichier de renseignements personnels POU 938 - Activités de sensibilisation</a></li>
          </ul>
        </div>
      </div>
    </details>
  </div>
</div>
<div class="row mrgn-tp-lg">
  <div class="col-md-8">
    <div class="wb-frmvld">
      <form id="accessibility_feedback">
        <div class="wb-fieldflow gc-font-2019" data-wb-fieldflow='{"noForm": true, "renderas":"radio", "gcChckbxrdio":true}'>
          <p>1. Sur quoi souhaitez-vous fournir une rétroaction?</p>
          <ul>
            <li data-wb-fieldflow='{"action": "query", "name": "feedback_type", "value": "feedback_type1"}'>Obstacle à l’accessibilité</li>
            <li data-wb-fieldflow='{"action": "query", "name": "feedback_type", "value": "feedback_type2"}' >Plan sur l’accessibilité de [nom de l’institution]</li>
            <li data-wb-fieldflow='{"action": "query", "name": "feedback_type", "value": "feedback_type3"}' >Rapport d'étape sur l’accessibilité de [nom de l’institution]</li>
            <li data-wb-fieldflow='[
                                {"action": "toggle", "toggle": "#feedback_type_other", "live":true },
                                {"action": "query", "name": "feedback_type", "value": "feedback_type4" }
                               ]'>Autre élément</li>
          </ul>
        </div>
        <div id="feedback_type_other" class="hidden">
          <div class="form-group">
            <label for="feedback_type3_desc"><span class="field-name gc-font-2019">Décrivez l’élément sur lequel vous souhaitez fournir une rétroaction</span></label>
            <input class="form-control full-width input-lg" id="feedback_type3_desc" name="feedback_type3_desc" type="text" />
          </div>
        </div>
        <div class="wb-fieldflow gc-font-2019" data-wb-fieldflow='{"noForm": true, "noreqlabel": true, "renderas":"checkbox", "gcChckbxrdio":true}'>
          <p>2. Sélectionnez tous les domaines pertinents pour vos commentaires.</p>
          <ul>
            <li data-wb-fieldflow='{"action": "query", "name": "areas", "value": "areas4"}'>Environnement physique (poignée de porte, rampe, ascenseur, etc.)</li>
            <li data-wb-fieldflow='{"action": "query", "name": "areas", "value": "areas5"}'>Emploi (p. ex. processus de recrutement)</li>
            <li data-wb-fieldflow='{"action": "query", "name": "areas", "value": "areas6"}'>Technologie (sites Web, applications logicielles, etc.) </li>
            <li data-wb-fieldflow='{"action": "query", "name": "areas", "value": "areas7"}'>Attitude (préjugés, microagressions, aspect lié à ma santé mentale, etc.)</li>
            <li data-wb-fieldflow='{"action": "query", "name": "areas", "value": "areas8"}'>Information et communication (formulaires, langage simple, bilinguisme, etc.) </li>
            <li data-wb-fieldflow='{"action": "query", "name": "areas", "value": "areas9"}'>Exclusion systémique (des événements, des politiques, des procédures, etc.) </li>
            <li data-wb-fieldflow='{"action": "query", "name": "areas", "value": "areas10"}'>Approvisionnement (appel d’offres pour des contrats, etc.) </li>
            <li data-wb-fieldflow='[
                                {"action": "toggle", "toggle": "#area_other", "live": true},
                                {"action": "query", "name": "areas", "value": "areas11"}
                                ]'>Autre domaine</li>
          </ul>
        </div>
        <div id="area_other" class="hidden">
          <div class="form-group">
            <label for="areas_desc"><span class="field-name gc-font-2019">Décrivez le domaine sur lequel vous souhaitez fournir une rétroaction</span></label>
            <input class="form-control full-width input-lg" id="areas_desc" name="areas_desc" type="text" />
          </div>
        </div>
        <div class="form-group mrgn-tp-lg">
          <label for="description" class="required"><span class="field-name gc-font-2019">3. Décrivez le problème et fournissez des commentaires. <strong class="required">(obligatoire)</strong></span></label>
          <p>N’incluez pas de renseignements qui pourraient identifier une personne.</p>
          <textarea class="form-control required full-width" rows="10" id="description"></textarea>
        </div>
        <div class="mrgn-tp-lg">
          <div class="wb-fieldflow gc-font-2019" data-wb-fieldflow='{"noForm": true, "renderas":"radio", "gcChckbxrdio":true}'>
            <p>4.  Souhaitez-vous que nous communiquions avec vous au sujet de votre rétroaction?</p>
            <ul>
              <li data-wb-fieldflow='{"action": "query", "name": "feedback_type", "value": "feedback_type1"}'>Non</li>
              <li data-wb-fieldflow='[
                                {"action": "toggle", "toggle": "#email_request_other", "live":true },
                                {"action": "query", "name": "feedback_type", "value": "feedback_type3" }
                               ]'>Oui, je suis d’accord pour fournir mon adresse de courriel à des fins de contact uniquement</li>
            </ul>
          </div>
          <div id="email_request_other" class="hidden">
            <div class="form-group">
              <label for="email1"><span class="field-name gc-font-2019">Adresse de courriel</span> (votrenom@domaine.com)</label>
              <p>Votre adresse de courriel ne sera utilisée que pour communiquer avec vous. Elle ne sera pas transmise.</p>
              <div class="row">
                <div class="col-md-8">
                  <input class="form-control input-lg full-width" id="email1" name="email1" type="email" autocomplete="email" />
                </div>
              </div>
              <div class="clearfix"></div>
            </div>
          </div>
        </div>
      </form>
    </div>
    <div class="mrgn-tp-xl">
      <ul class="list-inline">
        <li>
          <input class="btn btn-primary btn-lg mrgn-bttm-md" type="submit" value="Soumettre la rétroaction">
        </li>
        <li><a href="afeedback-04-01-en.html" type="button" class="btn btn-link btn-lg">Annuler</a></li>
      </ul>
    </div>
  </div>
</div>
<div class="clearfix"></div>
