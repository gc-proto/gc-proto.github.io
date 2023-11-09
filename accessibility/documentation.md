---
layout: without-h1
pageclass: cnt-wdth-lmtd
altLangPage: /accessibilite/documentation.html
breadcrumbs:
- title: Canada.ca design system
  link: https://www.canada.ca/en/government/about/design-system.html
- title: Accessible Canada Act templates
  link: https://test.canada.ca/accessibility/
css:
- https://design.canada.ca/css/split-h1.css
- https://design.canada.ca/css/custom.css
- https://use.fontawesome.com/releases/v5.15.4/css/all.css
dateModified: 2023-11-08
description: Documentation for the templates for an institution’s Accessibility plan and reports, and a feedback mechanism.
lang: en
title: Documentation for Accessible Canada Act templates
---
<h1 property="name" id="wb-cont" dir="ltr"><span class="stacked"><span>Documentation for Accessible Canada Act templates</span>: <span>Canada.ca design system</span></span></h1>
<section>
  <p>Government departments, agencies and Crown corporations are required to publish an accessibility plan, a feedback process and a feedback mechanism on their websites. They are also required to publish annual progress reports.</p>
  <p>The following templates are designed to help departmental web teams implement these requirements in a consistent way within the overall design for Canada.ca.</p>
  <h2>On this page</h2>
  <ul>
    <li><a href="#context">Context</a></li>
    <li><a href="#approach">Recommended approach</a></li>
    <li><a href="#next">Next steps</a></li>
    <li><a href="#annex">Annex</a></li>
  </ul>
</section>
<section>
  <h2 id="context">Context</h2>
  <h3>4 key design patterns</h3>
  <p>4 patterns that impact institutions on Canada.ca:</p>
  <ul>
    <li>Accessibility plans</li>
    <li>Progress reports</li>
    <li>Feedback process descriptions</li>
    <li>Feedback mechanisms</li>
  </ul>
  <p>These are derived from the requirements under the Accessible Canada Act and Regulations.</p>
  <ul>
    <li><a href="https://www.canada.ca/en/employment-social-development/programs/accessible-canada-regulations-guidance.html">Guidance on the Accessible Canada Regulations</a></li>
  </ul>
  <p class="mrgn-tp-lg"><strong>Publishing deadlines</strong>:</p>
  <ul>
    <li>December 31, 2022: institutional plans, feedback mechanisms, feedback process descripitons</li>
    <li>december 31, 2023: institutional progress reports</li>
  </ul>
  
  <h3>What are accessibility plans?</h3>
  <p>A document that outlines an institution's plan regarding the accessibility of all its programs, products, and services. Takes a total view of accessibility, from online to in real life (IRL), both public-facing and internal.</p>
  <p>The accessibility plan is the first deliverable in a 3-year planning and reporting cycle.</p>
 <h3>What are accessibility progress reports?</h3>
 <p>An annual document that describes an institution's progress on the implementation of their accessibility plans. In preparing their progress reports, institutions are required to consult persons with disabilities, as well as take the feedback they have received into consideration.</p>
  <h3>What is the accessibility feedback process description?</h3>
  <p>A published description of how your institutional feedback process works. It must be published alongside your accessibility plan.</p>
  <h3>What is the accessibility feedback mechanism?</h3>
  <p>A means for the users of an institution's programs and services to provide feedback about any aspect of the accessibility of its programs and services.</p>
  <p>The feedback mechanism must be always available, as feedback processes are meant to be ongoing.</p>
  <p>An online form is only one aspect of the feedback mechanism, as people must be able to give feedback by a variety of means.</p>
</section>
<section>
  <h2 id="approach">Recommended approach</h2>
  <p>The following working examples represent the recommended approach - not mandatory templates.</p>
  <ul>
    <li>Starting point - adjust as needed for your situation</li>
    <li>Designed for simplicity and with a focus on top user tasks like providing feedback, reviewing the plan, and understanding the process</li>
    <li>Built with standard WET code elements to maximize WCAG conformance</li>
  </ul>
</section>
<ul class="list-unstyled mrgn-tp-lg">
  <li>
    <details id="details-panel1">
      <summary class="bg-info">Information structure and navigation</summary>
      <h3>Recommended information architecture for institutional websites</h3>
      <figure class="gc-complex-img" role="group"><img src="../assets/img/info-structure-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Diagram of recommended website structure. First row on top: Institutional landing page (ILP). Second row: Accessibility page. Third row at the bottom, 3 elements: Accessibility plan, Feedback mechanism, Description of feedback process</p>
          </details>
        </figcaption>
      </figure>
      <h4>Accessibility link from Institutional landing page (ILP)</h4>
      <p>Recommended link label is "Accessibility"</p>
      <figure class="gc-complex-img" role="group"><img src="../assets/img/accessibility-link-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of Agriculture and Agri-Food Canada's public facing website. Under 'About AAFC', you can find 4 links: About our department, Transparency, Accessibility, Job opportunities.</p>
          </details>
        </figcaption>
      </figure>
      <p class="mrgn-tp-lg"><span class="fas fa-universal-access mrgn-rght-md text-success fa-lg" aria-hidden="true"></span> Example drawn from <a href="https://agriculture.canada.ca/en">AAFC’s institutional landing page</a></p>
      <h3>Breadcrumb for accessibility products</h3>
      <figure class="gc-complex-img" role="group"><img src="../assets/img/breadcrumb-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of the Government of Canada's website. The breadcrumbs are: Canada.ca, Institution name, Accessibility at "Institution name"</p>
          </details>
        </figcaption>
      </figure>
      <h4>Design considerations</h4>
      <p>While DTO recommends creating an accessibility node in your institution’s information architecture, it may also make sense to cross-link from elsewhere on your sites, such as:</p>
      <ul>
        <li>Linking to the accessibility plan from a “Reports and plans” section</li>
        <li>Linking to the accessibility feedback form from your “Contact us” pages</li>
      </ul>
    </details>
  </li>
  <li>
    <details id="details-panel2">
      <summary class="bg-info">Institutional accessibility page</summary>
      <h3>Recommended template</h3>
      <figure class="gc-complex-img" role="group"><img src="../assets/img/accessibility-landing-page-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of the Government of Canada's website titled "Accessibility at Institution name". There is a green button named "Provide feedback", then 2 links: Accessibility Plan and Feedback process.</p>
          </details>
        </figcaption>
      </figure>
      <p class="mrgn-tp-lg"><span class="fas fa-universal-access mrgn-rght-md text-success fa-lg" aria-hidden="true"></span> <a href="accessibility.html">Working example - Institutional accessibility page</a></p>
      <h3>Design considerations</h3>
      <ul>
        <li>Likely top task will be giving feedback, so the page uses the Super-task button</li>
        <li>Additional doormats can be added as needed</li>
        <li>Other patterns can be used as well on this page (e.g. Most requested band, contextual features)</li>
        <li>Design will likely evolve as future requirements come online, e.g. accessibility statements required under the <a href="https://a11y.canada.ca/en/standards/">proposed ICT accessibility standard</a></li>
      </ul>
    </details>
  </li>
  <li>
    <details id="details-panel3">
      <summary class="bg-info">Accessibility plan</summary>
      <h3>Recommended template</h3>
      <figure class="gc-complex-img" role="group"> <img src="../assets/img/accessibility-plan-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of the Government of Canada's website titled "Accessibility plan at Institution name" with a link to a Sample Accessibility Plan Template. Under it there is a link titled "List of accessibility plans from other institutions".</p>
          </details>
        </figcaption>
      </figure>
      <p class="mrgn-tp-lg"><span class="fas fa-universal-access mrgn-rght-md text-success fa-lg" aria-hidden="true"></span> <a href="plan.html">Working example - Accessibility plan</a></p>
      <h3>Design considerations</h3>
      <p>Ensure the plan meets the requirements outlined in <a href="https://www.canada.ca/en/employment-social-development/programs/accessible-canada-regulations-guidance/accessibility-plans.html">Guidance on accessibility plans</a>:</p>
      <ul>
        <li>This guidance includes a content template for the plan itself</li>
      </ul>
      <p>People are encouraged to provide feedback on accessibility plans - ensure there is a link to the feedback process and/or feedback form from within the plan itself.</p>
      <p>To assist with findability, TBS maintains a central index for accessibility plans and reports on the <a href="https://open.canada.ca/">Open government site</a>:</p>
      <ul>
        <li>Include a link from your plan to the central index</li>
        <li>Submit a metadata record for your plan</li>
        <li>See annex for instructions</li>
      </ul>
      <p>According to the <a href="https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=27167">Procedures for publishing</a>, institutional accessibility plans are considered publications:</p>
      <ul>
        <li>Request an ISSN and submit a copy to publications.gc.ca</li>
        <li>See annex for instructions</li>
      </ul>
      <p>Institutions must notify the Accessibility Commissioner at the Canadian Human Rights Commission within 48 hours of publishing their accessibility plans:</p>
      <ul>
        <li>Send an email to Info.Com@chrc-ccdp.gc.ca or use the CHRC’s <a href="https://www.accessibilitychrc.ca/en/notifying-accessibility-commissioner">My Accessibility Portal</a> service</li>
        <li>Include a link or URL for the plan in the email you send</li>
      </ul>
    </details>
  </li>
   <li>
    <details id="details-panel4">
      <summary class="bg-info">Progress report</summary>
      <h3>Recommended template</h3>
      <figure class="gc-complex-img" role="group"> <img src="../assets/img/progress-report-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of the Government of Canada's website titled "202x accessibility progress report for Institution name" with a link to a Guidance on preparing accessibility progress reports. Under it there is are links titled "Provide feedback" and "List of accessibility plans from other institutions".</p>
          </details>
        </figcaption>
      </figure>
      <p class="mrgn-tp-lg"><span class="fas fa-universal-access mrgn-rght-md text-success fa-lg" aria-hidden="true"></span> <a href="progress-report.html">Working example - Accessibility progress report</a></p>
      <h3>Design considerations</h3>
      <p>Ensure the document meets the requirements outlined in <a href="https://www.canada.ca/en/employment-social-development/programs/accessible-canada-regulations-guidance/progress-reports.html">Guidance on accessibility progress reports</a>:</p>
      <ul>
        <li>This guidance includes instructions on required headings to structure the content of the report</li>
      </ul>
      <p>People are encouraged to provide feedback on progress reports - ensure there is a link to the feedback process and/or feedback form from within the document itself.</p>
      <p>To assist with findability, TBS maintains a central index for accessibility plans and reports on the <a href="https://open.canada.ca/">Open government site</a>:</p>
      <ul>
        <li>Include a link from your progress report to the central index</li>
        <li>Submit a metadata record for your progress report</li>
        <li>See annex for instructions</li>
      </ul>
      <p>According to the <a href="https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=27167">Procedures for publishing</a>, institutional progress reports are considered publications:</p>
      <ul>
        <li>Request an ISSN and submit a copy to publications.gc.ca</li>
        <li>See annex for instructions</li>
      </ul>
      <p>Institutions must notify the Accessibility Commissioner at the Canadian Human Rights Commission within 48 hours of publishing their progress reports:</p>
      <ul>
        <li>Send an email to Info.Com@chrc-ccdp.gc.ca or use the CHRC’s <a href="https://www.accessibilitychrc.ca/en/notifying-accessibility-commissioner">My Accessibility Portal</a> service</li>
        <li>Include a link or URL for the plan in the email you send</li>
      </ul>
    </details>
  </li>
  <li>
    <details id="details-panel5">
      <summary class="bg-info">Feedback form</summary>
      <h3>Recommended template – feedback form</h3>
      <figure class="gc-complex-img" role="group"> <img src="../assets/img/feedback-form-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of the Government of Canada's website titled "Accessibility feedback form". Example of question with radio buttons.</p>
          </details>
        </figcaption>
      </figure>
      <p class="mrgn-tp-lg"><span class="fas fa-universal-access mrgn-rght-md text-success fa-lg" aria-hidden="true"></span> <a href="feedback-form.html">Working example - Accessibility feedback form</a></p>
      <h4>Recommended template - acknowledgement page</h4>
      <figure class="gc-complex-img" role="group"> <img src="../assets/img/acknowledgement-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of the Government of Canada's website titled "Accessibility feedback form acknowledgement". Thank you for your feedback.</p>
          </details>
        </figcaption>
      </figure>
      <p class="mrgn-tp-lg"><span class="fas fa-universal-access mrgn-rght-md text-success fa-lg" aria-hidden="true"></span> <a href="feedback-acknowledgement.html">Working example - Acknowledgement page</a></p>
      <h3>Design considerations</h3>
      <p>You will need to hook the intake form up to something - a generic email, a ticketing system, etc. (remember to keep incoming feedback for 7 years!)</p>
      <ul>
        <li>AEM users - send a ticket to Principal Publisher to leverage the “file and forget” solution for hooking forms up to an email address</li>
      </ul>
      <p>People submitting feedback have the option to request a response - form design includes information on turnaround times in this scenario.</p>
      <p>Form has been designed to minimize the collection of personally identifiable information (PII):</p>
      <ul>
        <li>When the user specifically requests a response, it only asks for an email address</li>
        <li>Includes instructions for users to not include PII in the comment box</li>
      </ul>
      <p>When creating your own implementation, consult with your organization’s ATIP coordinator. </p>
    </details>
  </li>
  <li>
    <details id="details-panel6">
      <summary class="bg-info">Feedback process description</summary>
      <h3>Recommended template</h3>
      <figure class="gc-complex-img" role="group"> <img src="../assets/img/feedback-process-en.png" class="img-responsive mrgn-tp-lg" alt="A long description can be found after the image">
        <figcaption>
          <details class="small">
            <summary>Detailed description</summary>
            <p class="mrgn-tp-lg">Screenshot of the Government of Canada's website titled "Accessibility feedback process at institution name". Many links how to provide feedback.</p>
          </details>
        </figcaption>
      </figure>
      <p class="mrgn-tp-lg"><span class="fas fa-universal-access mrgn-rght-md text-success fa-lg" aria-hidden="true"></span> <a href="feedback-process.html">Working example - Accessibility feedback process description</a></p>
      <h4>Design considerations</h4>
      <p>Designed to focus on top-of-mind user needs, rather than providing an exhaustive description of back-office procedures.</p>
      <p>Ensure the underlying process meets the requirements outlined in Guidance on feedback processes:</p>
      <ul>
        <li>People must be able to provide feedback by a variety of means, including email, telephone, snail mail</li>
        <li>Feedback must be analyzed and reported on in future</li>
      </ul>
      <p>As with accessibility plans, institutions must notify the Accessibility Commissioner at the Canadian Human Rights Commission within 48 hours of publishing their process description.</p>
      <ul>
        <li>Send an email to Info.Com@chrc-ccdp.gc.ca or use the CHRC’s <a href="https://www.accessibilitychrc.ca/en/notifying-accessibility-commissioner">My Accessibility Portal</a> service</li>
        <li>Include a link or URL for the process description in the email you send</li>
      </ul>
    </details>
  </li>
</ul>
<section>
  <h2 id="next">Next steps - Maturing the working examples</h2>
  <p>These working examples are a first step:</p>
  <ul>
    <li>DTO continues to monitor and iterate, based on data and evidence</li>
    <li>As departments and agencies implement, provide comments and feedback to dto.btn@tbs-sct.gc.ca</li>
    <li>Once matured, these working examples will be integrated to the pattern and template library</li>
  </ul>
</section>
<section>
  <h2 id="annex">Annex - Publishing plans and reports</h2>
  <h3>Procedures for publishing under the Policy on Communications and Federal Identity</h3>
  <p>Since institutional accessibility plans and progress reports are considered official publications of the Government of Canada, PDF versions of these documents need to be included in the <a href="https://publications.gc.ca/site/eng/home.html">catalogue at publications.gc.ca</a>.</p>
  <p>Follow these steps:</p>
  <ol>
    <li>Obtain an ISSN from Library and Archives Canada:<br>
      <a href="https://library-archives.canada.ca/eng/services/publishers/issn/Pages/issn.aspx">International Standard Serial Numbers (ISSN)</a></li>
    <li>Obtain a GC catalogue number from PSPC:<br>
      <a href="https://publications.gc.ca/site/eng/services/applyForISBN.html">Catalogue numbers - Government of Canada Publications</a></li>
    <li>Put both numbers in your document, as per PSPC guidance on copyright pages:<br>
      <a href="https://publications.gc.ca/site/eng/services/formatCopyPage.html">Formatting the copyright page</a></li>
    <li>Submit to PSPC for posting on publications.gc.ca via email:<br>
      publications.acquisitions@pwgsc.gc.ca</li>
  </ol>
  <p><strong>Tip</strong>: given the subject matter of accessibility plans and progress reports, <a href="https://helpx.adobe.com/acrobat/using/creating-accessible-pdfs.html">prepare an accessible PDF</a>.</p>
  <h3>Create a metadata record on open.canada.ca</h3>
  <p>To ensure your institutional accessibility plans and progress reports are included in the central index on open.canada.ca, you need to submit a metadata record:</p>
  <ol>
    <li>Create a <a href="http://registry.open.canada.ca/">registry account</a>: select <strong>Request an Account</strong>.  It can take up to 24 hours for the account to be activated.</li>
    <li>Once your account has been created, you will be able to create your record by populating the required metadata.<br>
      <strong>Note</strong>: you will require your institution’s IMSO approval for releasing a record.  Once approval is given, you will not require an additional approval for future updates.  We do not require you to provide the approval to us.</li>
    <li>Select <strong>Create Open Information Asset</strong> on the registry landing page.</li>
    <li>Select <strong>Institutional Accessibility Plans</strong> from the dropdown and complete the metadata fields.<br>
      This form allows you to describe each resource assigned to a dataset or asset.</li>
  </ol>
  <p>Once completed, your record will be placed in the Open Government Registry publishing queue for review and publication within 24 hours.</p>
  <p>Please contact your institution’s open government representative should you have additional questions about how to publish records to the registry.</p>
</section>
