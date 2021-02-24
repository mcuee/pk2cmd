pk2cmd
======

Command line porgramming tool for Pickit2 and Pickit3 with scripting firmware


Notice
------

**THE CODE IN THIS REPOSITORY IS NOT FREE SOFTWARE**; it is distributed
under a highly restrictive, non-free license (see below). **Do not copy,
branch, or fork this repository** unless you have agreed to this
license.

Origin
------

Code in this repository is from:

*   `pk2cmdv1.20LinuxMacSource.tar.gz` as published by Microchip (basis)
*   `PICkit2_PK2CMD_WIN32_SourceV1-21_RC1.zip` as published by Microchip
    (only changes to the non-Windows-specific files from the basis
    archive)
*   Pickit3 support implementation is based on the 
    [PICkit3 Programmer Application Source v3.10 ](http://ww1.microchip.com/downloads/en/DeviceDoc/PICkit3%20Programmer%20Application%20v3.10.zip)
*   [The updated device definition file](https://github.com/martonmiklos/pk2cmd/blob/master/pk2cmd/PK2DeviceFile.dat)
    was borrowed from [Anobium's PICkitPlus device database repository.](https://github.com/Anobium/PICKitPlus)

With the exception of inconsequential formatting and filesystem changes,
the contents of this repository consist only of the code listed above.

License Agreement with Microchip Technology
===========================================

The code in this repository, as well as any copies, branches, and forks
thereof, is subject to the terms of the following license from Microchip
Technology.

IMPORTANT: YOU MUST ACCEPT THE TERMS AND CONDITIONS OF THIS LICENSE
AGREEMENT TO RECEIVE A LICENSE FOR THE ACCOMPANYING SOFTWARE. TO ACCEPT
THE TERMS OF THIS LICENSE, OPEN THIS PACKAGE AND PROCEED WITH THE
DOWNLOAD OR USE OF THE SOFTWARE. IF YOU DO NOT ACCEPT THESE LICENSE
TERMS, DO NOT OPEN THIS PACKAGE, DOWNLOAD, OR USE THIS SOFTWARE.

PICkit™ 2 PK2CMD SOFTWARE LICENSE
---------------------------------

This License Agreement (Agreement) is a contract between You (as an
individual or as a representative of your employer) and Microchip
Technology Incorporated ("Company") for the PICkit™ 2 PK2CMD software
(including source code) accompanying this Agreement (the "Software"). In
consideration for access to the Software, You agree to be bound by this
Agreement.

1.  LICENSE GRANT. Subject to all of the terms and conditions of this
    Agreement, Company grants You a non-exclusive, non-sublicensable,
    non-transferable license to use the Software with Company products,
    modify the Software for use with Company products, and market, sell
    or otherwise distribute:

(a) Your end application that integrates Software and Company products
    ("Licensee Product"); or

(b) Your modifications to the Software provided that the modified
    Software has the following copyright and disclaimer notice
    prominently posted in a location where end users will see it (e.g.,
    installation program, program headers, About Box, etc.):

"Copyright © 2005-2009 Microchip Technology Inc. All rights reserved.
This version of the PICkit™ 2 PK2CMD Software has been modified by
[INSERT YOUR NAME, DATE OF SOFTWARE MODIFICATION HERE]. You may use,
copy, modify and distribute the Software for use with Microchip products
only. If you distribute the Software or its derivatives, the Software
must have this copyright and disclaimer notice prominently posted in a
location where end users will see it (e.g., installation program,
program headers, About Box, etc.). To the maximum extent permitted by
law, this Software is distributed "AS IS" and WITHOUT ANY WARRANTY
INCLUDING BUT NOT LIMITED TO ANY IMPLIED WARRANTY OF MERCHANTABILITY,
FITNESS FOR PARTICULAR PURPOSE, or NON-INFRINGEMENT. IN NO EVENT WILL
MICROCHIP OR ITS LICENSORS BE LIABLE FOR ANY INCIDENTAL, SPECIAL,
INDIRECT OR CONSEQUENTIAL DAMAGES OF ANY KIND ARISING FROM OR RELATED TO
THE USE, MODIFICATION OR DISTRIBUTION OF THIS SOFTWARE OR ITS
DERIVATIVES."

You may not copy or reproduce all or any portion of Software, except to
the extent that such activity is specifically allowed by this Agreement
or expressly permitted by applicable law notwithstanding the foregoing
limitations.

All copies of the Software created by You or for You, including
derivatives, must include the copyright, trademark and other proprietary
notices as they appear on the original or, in the event You modified the
Software, the notice listed above. You may not remove or alter any
identifying screen that is produced by the Software.

2.  OWNERSHIP AND TITLE. Software is licensed pursuant to the Agreement,
    not sold. All right, title and interest, including intellectual
    property rights, in and to Software, derivatives thereof,
    implementation of the Software in microcontrollers, and hardware and
    software implementations of Software or derivatives shall remain in
    Company. You will not obtain ownership rights to derivatives of
    Software, and by accepting the terms of this Agreement assign any
    such rights to Company that You do receive. Except as specifically
    stated in the Agreement, you are granted no other rights, express or
    implied, to the Software, derivatives thereof, or other Company
    intellectual property such as trade secrets, patents, copyrights,
    and trademarks.

3.  CONFIDENTIALITY. You agree not to disclose Software to any third
    party, except as permitted by this Agreement. To the extent that
    Software becomes part of the public domain, is independently
    developed, or obtained free from any obligation of confidentiality
    then the obligation of confidentiality under this Agreement shall
    not apply.

4.  COPYRIGHT. The Software is protected by U.S. copyright laws and
    international copyright treaties, as well as other intellectual
    property laws and treaties.

5.  TERMINATION OF AGREEMENT. Without prejudice to any other rights,
    Company may terminate this Agreement if You fail to comply with the
    terms and conditions of this Agreement. Upon termination, You shall
    immediately: (a) stop using and distributing the Software and
    derivatives thereof; (b) destroy all copies of the Software and
    derivatives in your possession; and (c) remove Software from any of
    Your tangible media and from systems on which the Software exists.
    Termination of this License shall not affect the right of any end
    user or consumer to use Licensee Product or modified Software;
    provided that such product or modified Software was purchased or
    distributed prior to the termination of this License.

6.  DANGEROUS APPLICATIONS. You acknowledge that Software has not been
    designed to be fault tolerant. You warrant that You will not use
    Software or derivatives in a dangerous, hazardous, or life
    supporting application where the failure of such application could
    lead directly to death, personal injury, or environmental damage.

7.  INDEMNITY. You will indemnify and hold Company and its licensor(s),
    its related companies and its suppliers, harmless for, from and
    against, any claims, costs (including attorney's fees), damages or
    liabilities, including without limitation product liability claims,
    arising out of: (a) Your use, modification and distribution of the
    Software and its derivatives; or (b) violation of this Agreement.
    COMPANY AND ITS LICENSOR(S) ASSUME NO RESPONSIBILITY FOR, NOR
    INDEMNIFY YOU AGAINST, ANY PATENT, COPYRIGHT OR OTHER INTELLECTUAL
    PROPERTY CLAIMS BROUGHT AGAINST YOU RELATING TO THE SOFTWARE.

8.  NO WARRANTY. TO THE MAXIMUM EXTENT PERMITTED BY LAW, COMPANY AND ITS
    LICENSOR PROVIDE SOFTWARE "AS IS" AND EXPRESSLY DISCLAIM ANY
    WARRANTY OF ANY KIND, WHETHER EXPRESS OR IMPLIED, INCLUDING BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
    PARTICULAR PURPOSE, OR NON-INFRINGEMENT. YOU ASSUME THE ENTIRE RISK
    ARISING OUT OF USE OR PERFORMANCE OF SOFTWARE, AS WELL AS ANY
    DERIVATIVES OF THE SOFTWARE MADE FOR YOU OR ON YOUR BEHALF. COMPANY
    AND ITS LICENSOR(S) ASSUME NO RESPONSIBILITY FOR THE ACCURACY OR
    ERRORS OR OMISSIONS OF SOFTWARE AND DO NOT WARRANT THE FOLLOWING:
    (A) THE FUNCTIONS CONTAINED IN SOFTWARE WILL MEET YOUR REQUIREMENTS;
    (B) THE OPERATION OF SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE;
        OR (C) ANY DEFECTS IN SOFTWARE WILL BE CORRECTED.

9.  LIMITATION OF LIABILITY. COMPANY AND ITS LICENSOR TOTAL AGGREGATE
    LIABILITY IN CONTRACT, WARRANTY, TORT (INCLUDING NEGLIGENCE OR
    BREACH OF STATUTORY DUTY), STRICT LIABILITY, INDEMNITY,
    CONTRIBUTION, OR OTHERWISE, SHALL NOT EXCEED THE LICENSE FEE YOU
    PAID FOR THE SOFTWARE. IN NO EVENT SHALL COMPANY AND ITS LICENSOR BE
    LIABLE FOR ANY INCIDENTAL, SPECIAL, INDIRECT OR CONSEQUENTIAL
    DAMAGES, LOST PROFITS OR LOST DATA, HARM TO YOUR EQUIPMENT, COST OF
    PROCUREMENT OF SUBSTITUTE GOODS, TECHNOLOGY OR SERVICES, ANY CLAIMS
    BY THIRD PARTIES (INCLUDING BUT NOT LIMITED TO ANY DEFENSE THEREOF),
    ANY CLAIMS FOR INDEMNITY OR CONTRIBUTION, OR OTHER SIMILAR COSTS. If
    any remedy is determined to have failed of its essential purpose,
    all limitations of liability and exclusion of damages set forth in
    the limited warranty shall remain in effect.

10. SURVIVAL. Sections 2-15 shall survive termination of this Agreement.

11. CHOICE OF LAW; VENUE; LIMITATIONS ON CLAIMS. You agree that this
    Agreement and any conflicts regarding Software, shall be construed,
    interpreted and governed by the laws, and subject to the exclusive
    jurisdiction of the state or territory in the Company Terms and
    Conditions of Sale ("T&Cs"). In the event that the T&Cs do not apply
    or the choice of law or jurisdiction are not indicated therein, then
    this Agreement shall be construed, interpreted and governed by the
    laws, and subject to the exclusive jurisdiction of the State of
    Arizona, U.S.A. without regard to any conflict of laws principles.
    You agree that regardless of any law to the contrary, any cause of
    action related to or arising out of this Agreement or Software must
    be filed within one year after such cause of action arose, or be
    considered waived.

12. EXPORT COMPLIANCE. You will not export or re-export Software,
    technical data, direct products thereof or any other items which
    would violate any applicable export control laws and regulations
    including, but not limited to, those of the United States and the
    United Kingdom. You agree that it is Your responsibility to obtain
    copies of and to familiarize yourself fully with these laws and
    regulations to avoid violation.

13. ASSIGNMENT. Neither this agreement nor any rights, licenses or
    obligations hereunder, may be assigned by You without the Company's
    prior written approval.

14. ENTIRE AGREEMENT: MODIFICATIONS AND WAIVER. This Agreement
    constitutes the entire agreement of the parties with respect to the
    subject matter of this Agreement, and merges and supersedes all
    communications relating to this subject matter, whether written or
    oral. Except as expressly set forth in this Agreement, no
    modification of this Agreement will be effective unless made in
    writing signed by Company. No failure or delay by Company or its
    licensor(s) to assert any rights or remedies arising from a breach
    of this Agreement shall be construed as a waiver or a continuing
    waiver of such rights and remedies, nor shall failure or delay to
    assert a breach be deemed to waive that or any other breach. If any
    part of this Agreement is found by a court of competent jurisdiction
    to be invalid, unlawful or unenforceable then such part shall be
    severed from the remainder of this Agreement and replaced with a
    valid provision that comes closest to the intention underlying the
    invalid provision.

Copyright © 2005-2009, Microchip Technology Inc. All rights reserved.
