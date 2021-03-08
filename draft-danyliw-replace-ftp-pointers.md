---
title: Updating References to the IETF FTP Service
abbrev: Updating References to the IETF FTP Service
docname: draft-danyliw-replace-ftp-pointers-00
updates: 2077, 2418, 2648, 2954, 2955, 3020, 3083, 3201, 3202, 3295, 3684, 3962, 3970, 4036, 4131, 4251, 4323, 4546, 4547, 4639, 4682, 5098, 5428, 6756, 7241
category: std

ipr: trust200902
area: General
workgroup: Network Working Group
keyword: Internet-Draft

stand_alone: yes
pi:
  rfcedstyle: yes
  toc: yes
  tocindent: yes
  sortrefs: yes
  symrefs: yes
  comments: yes
  inline: yes
  docmapping: yes

author:
 -
    ins: "R. Danyliw"
    name: "Roman Danyliw"
    organization: "Software Engineering Institute"
    email: rdd@cert.org

normative:
  RFC2119:
  RFC2077:
  RFC2418:
  RFC2648:
  RFC2954:
  RFC2955:
  RFC3020:
  RFC3083:
  RFC3201:
  RFC3202:
  RFC3295:
  RFC3684:
  RFC3962:
  RFC3970:
  RFC4036:
  RFC4131:
  RFC4251:
  RFC4323:
  RFC4546:
  RFC4547:
  RFC4639:
  RFC4682:
  RFC5098:
  RFC5428:
  RFC6756:
  RFC7241:

informative:
   FTP-RETIREMENT:
     target: "https://mailarchive.ietf.org/arch/msg/ietf/vi-8bFqlgBFjB2jJ1SIAGHiNRdg/"
     title: "Retirement of the IETF FTP Service"
     date: 2021-03-03

   FTP-RETIREMENT-PLAN:
     target: "https://www.ietf.org/media/documents/Revised-Retiring-IETF-FTP-Service-2021-03.pdf"
     title: "(Revised Plan) Retiring the IETF FTP Service"
     date: 2021-03-03
   
--- abstract

The IETF FTP service running at ftp.ietf.org, ops.ietf.org and ietf.org will be retired.  A number of published RFCs in the IETF and IAB streams include URIs that reference this FTP service.  To ensure that the materials referenced using the IETF FTP service can still be found, this document updates the FTP-based references in these affected documents with HTTPS URIs. 

--- middle

# Introduction {#intro}

In CY2021Q1, after community consultation, it was decided to retire the IETF FTP service running at ftp.ietf.org, ops.ietf.org and ietf.org {{FTP-RETIREMENT}}.  Appendix B of {{FTP-RETIREMENT-PLAN}} identified 30 RFCs published in the IETF and IAB streams between 1997-2006 that had at least one explicit or inline reference to a URI pointing to the IETF FTP service.   To ensure that the materials referenced using the IETF FTP service can still be found, this document formally updates the subset (25) of these documents, which have not been updated by other documents, with HTTPS URIs to the same materials.  

{{updates}} enumerates each of the affected RFCs and provides replacement text.

# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}} when, and only when, they appear in all capitals, as shown here.

The original text from an RFC to be updated will be quotes with "OLD" and the replacement text will be quoted with "NEW".

# Updated References {#updates}

This document updates the following RFCs.

{{RFC2077}} {{RFC2418}} {{RFC2648}} {{RFC2954}} {{RFC2955}} {{RFC3020}} {{RFC3083}} {{RFC3201}} {{RFC3202}} {{RFC3295}} {{RFC3684}} {{RFC3962}} {{RFC3970}} {{RFC4036}} {{RFC4131}} {{RFC4251}} {{RFC4323}} {{RFC4546}} {{RFC4547}} {{RFC4639}} {{RFC4682}} {{RFC5098}} {{RFC5428}}

Additionally, with permission of the IAB stream editor, {{RFC6756}} and {{RFC7241}} are also updated.

## RFC2077

Section 3 of {{RFC2077}} is updated as follows:

OLD:

Copies of RFCs are available on:

                      ftp://ftp.isi.edu/in-notes/

Copies of Internet-Drafts are available on:

                    ftp://ftp.ietf.org/internet-drafts/

NEW:

Copies of RFCs are available on:

                  https://www.rfc-editor.org/in-notes/

Copies of Internet-Drafts are available on:

                  https://www.ietf.org/id/


## RFC2418

Section 2.2 of {{RFC2418}} is updated as follows:

OLD:

Those archives are located at ftp://ftp.ietf.org/ietf-mail-archive.


NEW:

Those archives are located at https://www.ietf.org/ietf-ftp/ietf-mail-archive/ 

## RFC2648

Section 2 of {{RFC2648}} is updated as follows:

OLD:

The list of minutes maintained by the IETF for each working group and conference in the subtree pointed at by the URL ftp://ietf.org/ietf/ is
considered the definitive assignment of URNs for working group or birds of a feather minutes.

NEW:

The list of minutes maintained by the IETF for each working group and conference in the subtree pointed at by the URL https://www.ietf.org/how/meetings/proceedings/ is considered the definitive assignment of URNs for working group or birds of a feather minutes.

TODO: consider approach to Appendix A scripts

## RFC2954

The MIB in Section 3 of {{RFC2954}} is updated as follows:

OLD:

             Email Archive:
               ftp://ftp.ietf.org/ietf-mail-archive/frnetmib

NEW:

             Email Archive:
               https://www.ietf.org/ietf-ftp/ietf-mail-archive/frnetmib/


## RFC2955

The MIB in Section 4 of {{RFC2955}} is updated as follows:

OLD:

             Email Archive:
               ftp://ftp.ietf.org/ietf-mail-archive/frnetmib

NEW:

             Email Archive:
               https://www.ietf.org/ietf-ftp/ietf-mail-archive/frnetmib/

## RFC3020

The MIB in Section 3 of {{RFC3020}} is updated as follows:

OLD:

             Email Archive:
               ftp://ftp.ietf.org/ietf-mail-archive/frnetmib

NEW:

             Email Archive:
               https://www.ietf.org/ietf-ftp/ietf-mail-archive/frnetmib/

## RFC3083

The MIB in Section 4 of {{RFC3083}} is updated as follows:

OLD:

         Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

         Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/
           
## RFC3201

The MIB in Section 6 of {{RFC3201}} is updated as follows:

OLD:

    Email Archive: ftp://ftp.ietf.org/ietf-mail-archive/frnetmib

NEW:

    Email Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/frnetmib/

## RFC3202

The MIB in Section 7 of {{RFC3202}} is updated as follows:

OLD:

    Email Archive: ftp://ftp.ietf.org/ietf-mail-archive/frnetmib

NEW:

    Email Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/frnetmib/

## RFC3295

The MIB in Section 4 of {{RFC3295}} is updated as follows:

OLD:

               Email Archive:
               ftp://ftp.ietf.org/ietf-mail-archive/gsmp/

NEW:

               Email Archive:
               https://www.ietf.org/ietf-ftp/ietf-mail-archive/gsmp/

## RFC3684

The informative references in Section 14.2 of {{RFC3684}} are updated as follows:

OLD:

   \[7\]  Ogier, R., Message in IETF email archive for MANET,
        ftp://ftp.ietf.org/ietf-mail-archive/manet/2002-02.mail,
        February 2002.

NEW:

   \[7\]  Ogier, R., Message in IETF email archive for MANET,
       https://www.ietf.org/ietf-ftp/ietf-mail-archive/manet/2002-02.mail,
        February 2002.

OLD:

   \[9\]  Ogier, R., Message in IETF email archive for MANET,
        ftp://ftp.ietf.org/ietf-mail-archive/manet/2002-03.mail, March
        2002.

NEW:

   \[9\]  Ogier, R., Message in IETF email archive for MANET,
       https://www.ietf.org/ietf-ftp/ietf-mail-archive/manet/2002-02.mail, March 002.

## RFC3962

The informative reference of {{RFC3962}} is updated as follows:

OLD:

   \[LEACH\]    Leach, P., email to IETF Kerberos working group mailing
              list, 5 May 2003, ftp://ftp.ietf.org/ietf-mail-
              archive/krb-wg/2003-05.mail.

NEW:

   \[LEACH\]    Leach, P., email to IETF Kerberos working group mailing
              list, 5 May 2003,  https://www.ietf.org/ietf-ftp/ietf-mail-   
              archive/krb-wg/2003-05.mail.

## RFC3970

The MIB in Section 5 of {{RFC3970}} is updated as follows:

OLD:

     Archive:          ftp://ops.ietf.org/pub/lists

NEW:

     Archive: 
     https://www.ietf.org/ietf-ftp/concluded-wg-ietf-mail-archive/tewg/

## RFC4036

The MIB in Section 4 of {{RFC4036}} is updated as follows:

OLD:

            Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

            Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC4131

The MIB in Section 3 of {{RFC4131}} is updated as follows:

OLD:

           Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn.

NEW:

          Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/.

## RFC4251

The informative reference of {{RFC4251}} is updated as follows:

OLD:

   \[DAI\]              Dai, W., "An attack against SSH2 protocol", Email
                      to the SECSH Working Group ietf-ssh@netbsd.org
                      ftp:// ftp.ietf.org/ietf-mail-archive/secsh/2002-
                      02.mail, Feb 2002.

NEW:

   \[DAI\]              Dai, W., "An attack against SSH2 protocol", Email
                      to the SECSH Working Group ietf-ssh@netbsd.org
                      https://www.ietf.org/ietf-ftp/ietf-mail-archive/
                      secsh/2002-02.mail, Feb 2002.

## RFC4323

The MIB in Section 5 of {{RFC4323}} is updated as follows:

OLD:

        Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

        Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC4546

The MIB in Section 5 of {{RFC4546}} is updated as follows:

OLD:

             Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

             Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC4547

The MIB in Section 4 of {{RFC4547}} is updated as follows:

OLD:

                Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

                Archive: 
                https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC4639

The MIB in Section 4 of {{RFC4639}} is updated as follows:

OLD:

                Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

                Archive: 
                https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC4682

The MIB in Section 4 of {{RFC4682}} is updated as follows:

OLD:

            Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

            Archive: 
            https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC5098

The MIB in Section 5 of {{RFC5098}} is updated as follows:

OLD:

         Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

         Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC5428

The MIB in Section 5 of {{RFC5428}} is updated as follows:

OLD:

            Archive: ftp://ftp.ietf.org/ietf-mail-archive/ipcdn

NEW:

            Archive: https://www.ietf.org/ietf-ftp/ietf-mail-archive/ipcdn/

## RFC6756

Section 2.8.1 of {{RFC6756}} is updated as follows:

OLD:

   Current list and status of all IETF RFCs:
      ftp://ftp.ietf.org/rfc/rfc-index.txt


   Current list and description of all IETF Internet-Drafts:
      ftp://ftp.ietf.org/internet-drafts/1id-abstracts.txt

NEW:

   Current list and status of all IETF RFCs:
      https://www.rfc-editor.org/rfc/rfc-index.txt


   Current list and description of all IETF Internet-Drafts:
      https://www.ietf.org/id/1id-abstracts.txt

## RFC7241

Section B.2 of {{RFC7241}} is updated as follows:

OLD:

   Current list and description of all IETF Internet-Drafts:
   \<ftp://ftp.ietf.org/internet-drafts/1id-abstracts.txt\>

NEW:

   Current list and description of all IETF Internet-Drafts:
   \<https://www.ietf.org/id/1id-abstracts.txt\>

## Generic Guidance

If any other RFC not explicitly mentioned in an earlier section contains a reference of the form, "ftp://ftp.ietf.org/\<path\>", this reference MUST be replaced with a URI of the form, "https://www.ietf.org/ietf-ftp/\<path\>".

# Security Considerations {#seccons}

This document presents no new security consideration beyond those described in the updated documents. 


# IANA Considerations {#iana}

This document has no IANA actions.

--- back

# Acknowledgments
{:numbered="false"}

Thank you to Robert Sparks, Glen Barney, Henrik Levkowetz and Russ Housley on the IETF Tools Team for the operations and maintenance information which informed the community discussion with resulted in {{FTP-RETIREMENT}}.

Additionally, thank you to XXX for their contributions and valuable feedback.


