/* --- FONT & TEXT UPGRADE --- */
body {
  font-family: 'Barlow', Arial, sans-serif;
  font-weight: 400;
  line-height: 1.7;
  letter-spacing: 0.01em;
  font-size: 18px;
  background: var(--navy);
}
.section-title {
  font-family: 'Barlow Condensed', Arial, sans-serif;
  font-weight: 800;
  font-size: clamp(38px, 6vw, 62px);
  margin-bottom: 28px;
  line-height: 1.1;
}
.section-eyebrow {
  font-family: 'Barlow Condensed', Arial, sans-serif;
  font-weight: 600;
  font-size: 14px;
  letter-spacing: .12em;
}
.section-desc {
  font-weight: 500;
  font-size: 1.08em;
  margin-bottom: 16px;
}

/* --- SPACING & ARRANGEMENT IMPROVEMENTS --- */
section {
  margin-top: 64px;
  margin-bottom: 64px;
}
.section-header, .section-title {
  margin-bottom: 40px;
  margin-top: 24px;
}
.services-section, .why-section, .process-section, .tech-section, .contact-section {
  padding-top: 110px;
  padding-bottom: 90px;
}
.services-grid,
.why-inner,
.process-steps,
.tech-inner {
  gap: 38px !important;
}

.hero-desc {
  margin-bottom: 24px;
  padding-top: 12px;
}

/* --- CARD & BUTTON POLISH --- */
.service-card {
  border-radius: 16px;
  box-shadow: 0 6px 26px 0 rgba(44,60,90,0.085);
  margin: 0 8px;
}
.btn-hero, .btn-ghost {
  font-size: 17px;
  padding: 18px 44px;
  border-radius: 56px;
  font-weight: 700;
  letter-spacing: 0.12em;
}

/* --- MOBILE/RESPONSIVE POLISH --- */
@media (max-width: 900px) {
  .section-header,
  .section-title { margin-bottom: 28px; }
  .services-section,
  .why-section,
  .process-section,
  .tech-section,
  .contact-section { padding: 38px 8px; }
  .services-grid { gap: 18px !important; }
}
