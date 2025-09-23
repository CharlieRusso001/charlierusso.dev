<!doctype html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <meta name="x-apple-disable-message-reformatting">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="format-detection" content="telephone=no, date=no, address=no, email=no">
  <title>New Project Inquiry</title>
  <style>
    /* Base resets */
    html, body { margin:0 !important; padding:0 !important; height:100% !important; width:100% !important; }
    body { -webkit-text-size-adjust:100%; text-size-adjust:100%; background:#000; }
    table, td { border-collapse:collapse; mso-table-lspace:0pt; mso-table-rspace:0pt; }
    img { border:0; line-height:100%; vertical-align:middle; -ms-interpolation-mode:bicubic; }
    a { text-decoration:none; }
    /* Mobile tweaks */
    @media screen and (max-width:480px){
      .wrap{ width:100% !important; }
      .p-32{ padding:20px 14px !important; }
      .p-24{ padding:18px 14px !important; }
      .p-16{ padding:12px !important; }
      .fz-40{ font-size:28px !important; line-height:1.2 !important; }
      .fz-20{ font-size:16px !important; }
      .fz-18{ font-size:16px !important; }
      .fz-16{ font-size:15px !important; }
      .btn{ padding:12px 18px !important; display:block !important; }
    }
    @media (prefers-color-scheme: dark) {
      a { color:#00ff41; }
    }
  </style>
  <!--[if mso]>
    <style>
      .monospace { font-family: Consolas, "Courier New", Courier, monospace !important; }
    </style>
  <![endif]-->
</head>

<body style="margin:0; padding:0; background:#000;">
  <!-- Preheader (hidden in inbox preview) -->
  <div style="display:none; max-height:0; overflow:hidden; font-size:1px; line-height:1px; color:#000; opacity:0;">
    New project inquiry received from {{from_name}} — {{project_category}} project with {{project_budget}} budget
  </div>

  <!-- Full-width background -->
  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" bgcolor="#000" style="background:#000;">
    <tr>
      <td align="center" style="padding:0;">

        <!--[if mso]>
        <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="600"><tr><td>
        <![endif]-->

        <!-- Fluid container (hybrid) -->
        <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" class="wrap" style="max-width:600px; width:100%;">

          <!-- Header bar -->
          <tr>
            <td align="center" class="p-32 monospace" bgcolor="#00ff41" style="padding:32px 16px; background:#00ff41; color:#000; font-family:Consolas,Menlo,'Courier New',Courier,monospace; mso-line-height-rule:exactly; line-height:1.25;">
              <div class="fz-40" style="font-size:40px; font-weight:800; line-height:1; margin:0; color:#000;">PROJECT INQUIRY</div>
              <div class="fz-20" style="font-size:20px; margin-top:8px; color:#000;">Russo Technical Development Services</div>
            </td>
          </tr>

          <!-- Main green-outline panel -->
          <tr>
            <td class="p-24 monospace" bgcolor="#0b0b0b" style="padding:24px; background:#0b0b0b; border:1px solid #00ff41; font-family:Consolas,Menlo,'Courier New',Courier,monospace;">

              <div class="fz-18" style="color:#00ff41; font-size:18px; margin:0 0 16px 0; line-height:1.3; mso-line-height-rule:exactly;">&gt; Client Information</div>

              <!-- Sub box -->
              <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%">
                <tr>
                  <td class="p-16" bgcolor="#051b0d" style="padding:16px; border:1px solid #1aff66; background:#051b0d;">
                    <p class="fz-16" style="margin:0 0 8px 0; color:#84ffb0; font-size:16px; line-height:1.5; mso-line-height-rule:exactly;">
                      <strong style="color:#00ff41;">Name:</strong> {{from_name}}
                    </p>
                    <p class="fz-16" style="margin:0 0 8px 0; color:#84ffb0; font-size:16px; line-height:1.5; mso-line-height-rule:exactly;">
                      <strong style="color:#00ff41;">Email:</strong> <a href="mailto:{{from_email}}" style="color:#84ffb0; text-decoration:underline;">{{from_email}}</a>
                    </p>
                    <p class="fz-16" style="margin:0 0 8px 0; color:#84ffb0; font-size:16px; line-height:1.5; mso-line-height-rule:exactly;">
                      <strong style="color:#00ff41;">Phone:</strong> {{phone}}
                    </p>
                    <p class="fz-16" style="margin:0; color:#84ffb0; font-size:16px; line-height:1.5; mso-line-height-rule:exactly;">
                      <strong style="color:#00ff41;">Website:</strong> {{existing_website}}
                    </p>
                  </td>
                </tr>
              </table>

              <div class="fz-18" style="color:#00ff41; font-size:18px; margin:16px 0; line-height:1.3; mso-line-height-rule:exactly;">&gt; Project Details</div>

              <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%">
                <tr>
                  <td class="p-16" bgcolor="#051b0d" style="padding:16px; border:1px solid #1aff66; background:#051b0d; color:#84ffb0; font-size:16px; line-height:1.5; mso-line-height-rule:exactly;">
                    <p class="fz-16" style="margin:0 0 8px 0;"><strong style="color:#00ff41;">Budget:</strong> {{project_budget}}</p>
                    <p class="fz-16" style="margin:0 0 8px 0;"><strong style="color:#00ff41;">Category:</strong> {{project_category}}</p>
                    <p class="fz-16" style="margin:0 0 8px 0;"><strong style="color:#00ff41;">Description:</strong></p>
                    <div style="background:#000; border:1px solid #00ff41; padding:12px; color:#d7ffe1; font-family:Consolas,Menlo,'Courier New',Courier,monospace; line-height:1.45; mso-line-height-rule:exactly; word-wrap:break-word;">
                      {{project_description}}
                    </div>
                  </td>
                </tr>
              </table>

              <!-- Submitted line -->
              <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="margin-top:16px;">
                <tr>
                  <td align="center" class="p-16" bgcolor="#0d2a12" style="padding:12px; border:1px solid #00ff41; background:#0d2a12;">
                    <div style="color:#00ff41; font-size:12px; line-height:1.4; mso-line-height-rule:exactly;">
                      <strong>Submitted:</strong> {{timestamp}}
                    </div>
                  </td>
                </tr>
              </table>

            </td>
          </tr>

          <!-- Footer bar -->
          <tr>
            <td align="center" class="p-24 monospace" bgcolor="#00ff41" style="padding:24px 16px; background:#00ff41; color:#000; font-family:Consolas,Menlo,'Courier New',Courier,monospace; line-height:1.4; mso-line-height-rule:exactly;">
              <div style="margin:0 0 12px 0; font-weight:600; color:#000;">
                Ready to discuss your project? I will be with you shortly. Please reply with any extra info.
              </div>

              <!-- Reply button -->
              <!--[if mso]>
              <v:roundrect xmlns:v="urn:schemas-microsoft-com:vml" href="mailto:{{from_email}}?subject=Re: Project Inquiry - {{project_category}}" style="height:44px;v-text-anchor:middle;width:200px;" arcsize="10%" strokecolor="#000000" fillcolor="#000000">
                <w:anchorlock/>
                <center style="color:#00ff41;font-family:Consolas,Menlo,'Courier New',Courier,monospace;font-size:14px;font-weight:700;letter-spacing:1px;">REPLY</center>
              </v:roundrect>
              <![endif]-->
              <!--[if !mso]><!-- -->
              <a class="btn" href="mailto:{{from_email}}?subject=Re: Project Inquiry - {{project_category}}"
                 style="display:inline-block; padding:12px 24px; background:#000; color:#00ff41; border:2px solid #000; font-weight:700; letter-spacing:1px;">
                REPLY
              </a>
              <!--<![endif]-->

              <div class="fz-16" style="margin:16px 0 8px 0; font-size:12px; color:#000;"><strong>Contact Information:</strong></div>
              <div style="color:#000;"><strong>Email:</strong> <a href="mailto:russoc2023@fau.edu" style="color:#000; text-decoration:underline;">russoc2023@fau.edu</a></div>
              <div style="margin-top:4px; font-size:11px; color:#000;">Technical Development Services | Fullstack Development | Prototype Manufacturing</div>
            </td>
          </tr>

        </table>

        <!--[if mso]>
        </td></tr></table>
        <![endif]-->

      </td>
    </tr>
  </table>

  <!-- Landmark for screen readers (optional) -->
  <div role="article" aria-roledescription="email" aria-label="New Project Inquiry" style="display:none;"></div>
</body>
</html>
