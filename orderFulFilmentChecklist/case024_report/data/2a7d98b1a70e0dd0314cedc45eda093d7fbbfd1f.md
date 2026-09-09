# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: orderFulFilmentChecklist\case-024.spec.ts >> test
- Location: tests\orderFulFilmentChecklist\case-024.spec.ts:11:5

# Error details

```
Error: locator.click: Error: strict mode violation: getByRole('option', { name: /DTDC|Surface|Express/i }).or(getByRole('option').first()) resolved to 2 elements:
    1) <li tabindex="0" role="option" aria-selected="false" class="MuiButtonBase-root MuiMenuItem-root MuiMenuItem-gutters MuiMenuItem-root MuiMenuItem-gutters css-bx4g4w">…</li> aka getByRole('option').filter({ hasText: /^$/ })
    2) <li tabindex="-1" role="option" aria-selected="false" data-value="Blue Dart Surface" class="MuiButtonBase-root MuiMenuItem-root MuiMenuItem-gutters MuiMenuItem-root MuiMenuItem-gutters css-bx4g4w">…</li> aka getByRole('option', { name: 'Blue Dart Surface' })

Call log:
  - waiting for getByRole('option', { name: /DTDC|Surface|Express/i }).or(getByRole('option').first())

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e3]:
    - generic [ref=e4]:
      - generic [ref=e10]: MENU
      - list [ref=e12]:
        - link [ref=e13] [cursor=pointer]:
          - /url: /oft/dashboard
          - generic [ref=e16]: Dashboard
      - generic [ref=e18]: PAGES
      - list [ref=e20]:
        - button [ref=e22] [cursor=pointer]:
          - generic [ref=e25]: Order Intents
        - button [ref=e30] [cursor=pointer]:
          - generic [ref=e34]: Order OFT Confirmation Status
        - button [ref=e39] [cursor=pointer]:
          - generic [ref=e42]: Order Warehouse Status
        - generic [ref=e46]:
          - button [ref=e47] [cursor=pointer]:
            - generic [ref=e51]: Order Packing Status
          - list [ref=e58]:
            - link [ref=e59] [cursor=pointer]:
              - /url: /oft/order-recieved-for-packing
              - generic [ref=e63]: Order Received For Packing
            - link [ref=e65] [cursor=pointer]:
              - /url: /oft/order-packed
              - generic [ref=e69]: Order Packed
        - generic [ref=e71]:
          - button [ref=e72] [cursor=pointer]:
            - generic [ref=e75]: Order Ready To Ship Status
          - list [ref=e82]:
            - link [ref=e83] [cursor=pointer]:
              - /url: /oft/local-order-ready-to-ship
              - generic [ref=e86]: Local Order Ready To Ship
            - link [ref=e88] [cursor=pointer]:
              - /url: /oft/out-station-order-ready-to-ship
              - generic [ref=e91]: Out Station order Ready To Ship
            - link [ref=e93] [cursor=pointer]:
              - /url: /oft/local-order-pending-for-manifest-print
              - generic [ref=e97]: Local Order Pending For Manifest Print
            - link [ref=e99] [cursor=pointer]:
              - /url: /oft/out-station-order-pending-for-manifest-print
              - generic [ref=e103]: Out-Station Order Pending For Manifest Print
        - button [ref=e106] [cursor=pointer]:
          - generic [ref=e109]: Order Shipped Status
        - button [ref=e114] [cursor=pointer]:
          - generic [ref=e118]: Orders Delivered
        - link [ref=e122] [cursor=pointer]:
          - /url: /oft/payment-failed-orders
          - generic [ref=e125]: Payment Failed Orders
        - link [ref=e127] [cursor=pointer]:
          - /url: /oft/payment-after-cancellation-orders
          - generic [ref=e130]: Payment After Cancellation Orders
      - paragraph [ref=e133]: © 2026 DealsDray
    - generic [ref=e134]:
      - banner [ref=e135]:
        - generic [ref=e136]:
          - generic [ref=e137]:
            - button [ref=e138] [cursor=pointer]
            - separator [ref=e142]
            - paragraph [ref=e143]: OFT PANEL
          - generic [ref=e144]:
            - button [ref=e145] [cursor=pointer]: Revalidate Cache
            - checkbox [ref=e154] [cursor=pointer]
            - paragraph [ref=e157]: OFT Alex
            - button [ref=e158] [cursor=pointer]:
              - generic [ref=e159]: O
      - main [ref=e160]:
        - generic [ref=e161]:
          - generic [ref=e162]:
            - generic [ref=e167]:
              - heading [level=6] [ref=e168]: Out-Station Orders Ready To Ship
              - text: OFT Panel / Out-Station Orders Ready To Ship
            - generic [ref=e170]:
              - textbox [ref=e174]:
                - /placeholder: Search
                - text: U2709000067
              - img [ref=e176] [cursor=pointer]
              - group
          - generic [ref=e178]:
            - generic [ref=e179]:
              - generic [ref=e180]: Logistics
              - generic [ref=e181]:
                - combobox [ref=e182] [cursor=pointer]: SHIPROCKET AGGRIGATOR
                - textbox: SHIPROCKET AGGRIGATOR
                - group:
                  - generic: Logistics
            - generic [ref=e183]:
              - generic [ref=e184]: Select Courier
              - generic [ref=e185]:
                - combobox [expanded] [ref=e186] [cursor=pointer]
                - textbox
                - group:
                  - generic: Select Courier
            - button [disabled]: SEARCH
            - button [disabled]: REQUEST MANIFEST
          - generic [ref=e190]:
            - text: "Filters active — search:"
            - strong [ref=e191]: "\"U2709000067\""
            - text: •
            - strong [ref=e192]: "1"
            - text: result
          - generic [ref=e193]:
            - table [ref=e195]:
              - rowgroup [ref=e196]:
                - row [ref=e197]:
                  - columnheader [ref=e198]: RECORD NO
                  - columnheader [ref=e199]: INTENT NO
                  - columnheader [ref=e200]: ORDER VALUE
                  - columnheader [ref=e201]: BUYER DETAILS
                  - columnheader [ref=e202]: ORDER PROCESS DATE
                  - columnheader [ref=e203]: COURIER DETAILS
                  - columnheader [ref=e204]: OFT REMARK
                  - columnheader [ref=e205]: RM REMARK
                  - columnheader [ref=e206]: SHIP TO
                  - columnheader [ref=e207]: ACTION
              - rowgroup [ref=e208]:
                - row [ref=e209]:
                  - cell [ref=e210]: "1"
                  - cell [ref=e211]:
                    - generic [ref=e212] [cursor=pointer]: U2709000067
                    - generic [ref=e213]: ORDER READY TO SHIP
                  - cell [ref=e214]:
                    - paragraph [ref=e215]: ₹8,890
                    - generic [ref=e216]: Send to dealsdray RM (prepaid:via courier)
                    - generic [ref=e217]: Ready To Ship
                    - generic [ref=e218]: "Delivery Mode: Send to dealsdray RM (prepaid:via courier)"
                    - generic [ref=e219]: "Preferred Logistics: SHIPROCKET AGGRIGATOR"
                    - generic [ref=e220]: "Courier Name: -"
                  - cell [ref=e221]:
                    - generic [ref=e222]:
                      - paragraph [ref=e223]: NAIK MOBILES
                      - generic [ref=e224]: BENGALURU URBAN / KARNATAKA
                  - cell [ref=e225]:
                    - generic [ref=e226]:
                      - generic [ref=e227]: "AWBN/RTS Date: 09/09/2026, 10:15:38 am"
                      - generic [ref=e233]: "Order Packed Date: 09/09/2026, 10:15:29 am"
                      - generic [ref=e239]: "Order Received For Packing: 09/09/2026, 10:15:23 am"
                      - generic [ref=e245]: "Order Sent For Packing: 09/09/2026, 10:15:12 am"
                      - generic [ref=e251]: "WH.H Pickup Printing Date: 09/09/2026, 10:15:07 am"
                      - generic [ref=e257]: "OFT-FINAL Order Confirmation Date: 09/09/2026, 10:14:42 am"
                      - generic [ref=e263]: "ACT Order Confirmation Date: 09/09/2026, 10:14:34 am"
                      - generic [ref=e269]: "RM-Confirmation Date: 09/09/2026, 10:14:27 am"
                      - generic [ref=e275]: "Order Assigned Date: 09/09/2026, 10:14:13 am"
                      - generic [ref=e281]: "Order Date: 09/09/2026, 10:13:31 am"
                  - cell [ref=e286]:
                    - generic [ref=e287]: "AWBN: -"
                    - generic [ref=e288]: "ORDER TYPE: PREPAID"
                    - generic [ref=e289]: "ETD: -"
                  - cell [ref=e290]:
                    - paragraph [ref=e291]: Send for confirmation
                    - text: OFT Alex
                  - cell [ref=e292]:
                    - paragraph [ref=e293]: Confirmed
                    - text: RM Alex
                  - cell [ref=e294]:
                    - paragraph [ref=e295]: rm+3025.alex.john@gmail.com
                  - cell [ref=e296]:
                    - button [ref=e297] [cursor=pointer]: View Details
            - generic [ref=e299]:
              - paragraph [ref=e300]: "Rows per page:"
              - generic [ref=e301]:
                - combobox [ref=e302] [cursor=pointer]: "25"
                - textbox: "25"
              - paragraph [ref=e303]: 1–1 of 1
              - generic [ref=e304]:
                - button [disabled]
                - button [disabled]
      - contentinfo [ref=e305]: 2026 © DealsDray.
  - listbox "Select Courier" [ref=e308]:
    - option [active] [ref=e309] [cursor=pointer]
    - option "Blue Dart Surface" [ref=e310] [cursor=pointer]
```

# Test source

```ts
  374 |     await page.getByRole('link', { name: 'Dashboard' }).click();
  375 |     await page.getByRole('link', { name: 'Processed Orders', exact: true }).click();
  376 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  377 |     await page.getByRole('columnheader', { name: 'ACTION' }).click();
  378 |     await page.getByRole('button', { name: 'View Details' }).click();
  379 | 
  380 |     // Print Proforma Invoice
  381 |     const page3Promise = page.waitForEvent('popup', { timeout: 5000 }).catch(() => null);
  382 |     await page.getByRole('button', { name: 'Print Proforma Invoice' }).click();
  383 |     const page3 = await page3Promise;
  384 |     if (page3 && !page3.isClosed()) { await page3.close().catch(() => {}); }
  385 | 
  386 |     await page.getByRole('heading', { name: 'REMARK LOGS' }).click();
  387 |     await screenshot('wh_processed_order_details');
  388 | 
  389 |     await page.getByRole('button', { name: 'Account' }).click();
  390 |     await page.getByRole('menuitem', { name: 'Sign out' }).click();
  391 | 
  392 |     // ── Packing login ────────────────────────────────────────────────────────
  393 |     await page.getByRole('textbox', { name: 'Email Address' }).fill('packing+3025.alex.john@gmail.com');
  394 |     await page.getByRole('textbox', { name: 'Password' }).fill('packing+3025.alex.john@gmail.com');
  395 |     await page.getByRole('button', { name: 'Sign In' }).click();
  396 | 
  397 |     await page.getByRole('link', { name: 'Ready To Pack Orders', exact: true }).click();
  398 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  399 |     await page.getByRole('columnheader', { name: 'ACTION' }).click();
  400 |     await screenshot('packing_ready_to_pack_list');
  401 | 
  402 |     await page.getByRole('button', { name: 'View Details' }).click();
  403 |     await screenshot('packing_ready_to_pack_details');
  404 | 
  405 |     await page.getByLabel('', { exact: true }).click();
  406 |     await page.getByRole('option', { name: 'Received' }).click();
  407 |     await screenshot('packing_received_selected');
  408 | 
  409 |     await page.getByRole('button', { name: 'SUBMIT' }).click();
  410 |     await page.getByRole('button', { name: 'OK' }).waitFor({ state: 'visible' });
  411 |     await screenshot('packing_received_submit_popup');
  412 |     await page.getByRole('button', { name: 'OK' }).click();
  413 | 
  414 |     await page.getByRole('link', { name: 'Dashboard' }).click();
  415 |     await page.getByRole('link', { name: 'Orders Received For Packing', exact: true }).click();
  416 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  417 |     await page.locator('tr').filter({ hasText: intentId }).getByRole('button', { name: 'View Details' }).first().click();
  418 |     await screenshot('packing_received_for_packing_details');
  419 | 
  420 |     // Fill dimension & invoice details
  421 |     const correctInvoice = generateRandomInvoiceNumber();
  422 |     await page.getByRole('textbox', { name: 'Invoice Number' }).fill(correctInvoice);
  423 |     await page.getByRole('textbox', { name: 'Weight (KG)' }).fill('1');
  424 |     await page.getByRole('textbox', { name: 'Width (CM)' }).fill('1');
  425 |     await page.getByRole('textbox', { name: 'Height (CM)' }).fill('1');
  426 |     await page.getByRole('textbox', { name: 'Length (CM)' }).fill('1');
  427 |     await page.getByLabel('', { exact: true }).click();
  428 |     await page.getByRole('option', { name: 'Ready To Ship' }).click();
  429 |     await screenshot('packing_form_filled_correct_invoice');
  430 |     await page.getByRole('button', { name: 'SUBMIT' }).click();
  431 |     await page.getByRole('button', { name: 'OK' }).waitFor({ state: 'visible' });
  432 |     await screenshot('packing_ready_to_ship_submit_popup');
  433 |     await page.getByRole('button', { name: 'OK' }).click();
  434 | 
  435 |     await page.getByRole('link', { name: 'Dashboard' }).click();
  436 |     await page.getByRole('link', { name: 'Orders Packed And Sent To OFT' }).click();
  437 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  438 |     await page.getByRole('columnheader', { name: 'ACTION' }).click();
  439 |     await page.locator('tr').filter({ hasText: intentId }).getByRole('button', { name: 'View Details' }).first().click();
  440 |     await page.getByRole('heading', { name: 'SHIPPING / BILLING ADDRESS' }).click();
  441 |     await screenshot('packing_final_details');
  442 |     await page.getByRole('button', { name: 'Account' }).click();
  443 |     await page.getByRole('menuitem', { name: 'Sign out' }).click();
  444 |     
  445 |     // ── OFT login (ShipRocket Delivery Flow) ─────────────────────────────────
  446 |     await page.getByRole('textbox', { name: 'Email Address' }).fill('oft+3025.alex.john@gmail.com');
  447 |     await page.getByRole('textbox', { name: 'Password' }).fill('oft+3025.alex.john@gmail.com');
  448 |     await page.getByRole('button', { name: 'Sign In' }).click();
  449 |     await page.getByRole('button', { name: 'Order Packing Status' }).click();
  450 |     await page.getByRole('link', { name: 'Order Packed', exact: true }).click();
  451 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  452 |     await page.locator('tr').filter({ hasText: intentId }).getByRole('button', { name: 'View Details' }).first().click();
  453 |     await screenshot('oft_order_packed_details');
  454 | 
  455 |     await page.getByRole('textbox', { name: 'Remark' }).fill('Confirmed');
  456 |     await screenshot('oft_process_remark_filled');
  457 | 
  458 |     await page.getByRole('button', { name: 'READY TO SHIP', exact: true }).click();
  459 |     await page.getByRole('button', { name: 'OK' }).waitFor({ state: 'visible' });
  460 |     await screenshot('oft_process_ready_to_ship_success');
  461 |     await page.getByRole('button', { name: 'OK' }).click();
  462 | 
  463 |     await page.getByRole('link', { name: 'Dashboard' }).click();
  464 |     await page.getByRole('button', { name: 'Order Ready To Ship Status', exact: true }).click();
  465 |     await page.getByRole('link', { name: 'Out Station order Ready To Ship', exact: true }).click();
  466 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  467 |     await page.getByRole('combobox', { name: 'Logistics' }).click();
  468 |     await page.getByRole('option', { name: /SHIPROCKET/i }).or(page.getByRole('option').first()).click();
  469 |     await page.waitForTimeout(1000);
  470 |     const selectCourierCombo = page.getByRole('combobox', { name: 'Select Courier' });
  471 |     await selectCourierCombo.waitFor({ state: 'visible', timeout: 15000 });
  472 |     await selectCourierCombo.click();
  473 |     await page.getByRole('option').first().waitFor({ state: 'visible', timeout: 10000 }).catch(() => { });
> 474 |     await page.getByRole('option', { name: /DTDC|Surface|Express/i }).or(page.getByRole('option').first()).click();
      |                                                                                                            ^ Error: locator.click: Error: strict mode violation: getByRole('option', { name: /DTDC|Surface|Express/i }).or(getByRole('option').first()) resolved to 2 elements:
  475 |     await page.getByRole('button', { name: 'SEARCH' }).click();
  476 |     await screenshot('oft_out_station_ready_to_ship_searched');
  477 | 
  478 |     await page.locator('tr').filter({ hasText: intentId }).getByRole('checkbox').check();
  479 |     await screenshot('oft_out_station_manifest_checked');
  480 | 
  481 |     await page.getByRole('button', { name: 'REQUEST MANIFEST' }).click();
  482 |     await page.getByRole('button', { name: 'OK' }).waitFor({ state: 'visible' });
  483 |     await screenshot('oft_out_station_request_manifest_success');
  484 |     await page.getByRole('button', { name: 'OK' }).click();
  485 | 
  486 |     await page.getByRole('button', { name: 'Account' }).click();
  487 |     await page.getByRole('menuitem', { name: 'Sign out' }).click();
  488 | 
  489 |     // ── OFTMGR login (Release Manifest) ──────────────────────────────────────
  490 |     await page.getByRole('textbox', { name: 'Email Address' }).fill('oftmgr+3025.alex.john@gmail.com');
  491 |     await page.getByRole('textbox', { name: 'Password' }).fill('oftmgr+3025.alex.john@gmail.com');
  492 |     await page.getByRole('button', { name: 'Sign In' }).click();
  493 | 
  494 |     await page.getByRole('link', { name: 'Manifest Requests', exact: true }).click();
  495 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  496 |     await screenshot('oftmgr_manifest_requests_list');
  497 | 
  498 |     const viewOrdersPromise = page.waitForEvent('popup', { timeout: 5000 }).catch(() => null);
  499 |     await page.getByRole('button', { name: 'View Orders' }).click();
  500 |     const viewOrdersPage = await viewOrdersPromise;
  501 |     await screenshot('oftmgr_manifest_orders_popup');
  502 |     const releaseBtn = viewOrdersPage.getByRole('button', { name: /RELEASE MANIFEST/i }).first();
  503 |     await releaseBtn.waitFor({ state: 'visible', timeout: 15000 });
  504 |     await releaseBtn.click({ force: true });
  505 | 
  506 |     const okReleaseBtn = viewOrdersPage.getByRole('button', { name: 'OK' }).or(viewOrdersPage.getByRole('button', { name: 'Ok' })).or(viewOrdersPage.getByRole('button', { name: /OK/i })).first();
  507 |     await okReleaseBtn.waitFor({ state: 'visible', timeout: 10000 }).catch(() => { });
  508 |     if (await okReleaseBtn.isVisible().catch(() => false)) {
  509 |         await okReleaseBtn.click().catch(() => { });
  510 |         await viewOrdersPage.locator('.MuiBackdrop-root, [role="dialog"]').first().waitFor({ state: 'detached', timeout: 10000 }).catch(() => { });
  511 |     }
  512 |     await page.waitForTimeout(1500);
  513 | 
  514 |     if (viewOrdersPage && !viewOrdersPage.isClosed()) {
  515 |         await viewOrdersPage.close().catch(() => { });
  516 |     }
  517 | 
  518 |     await page.getByRole('link', { name: 'Dashboard' }).click();
  519 |     await page.getByRole('link', { name: 'Manifest Released', exact: true }).click();
  520 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  521 |     await page.getByRole('columnheader', { name: 'ACTION' }).click();
  522 |     await screenshot('oftmgr_manifest_released_verified');
  523 | 
  524 |     await page.getByRole('button', { name: 'Account' }).click();
  525 |     await page.getByRole('menuitem', { name: 'Sign out' }).click();
  526 | 
  527 |     // ── OFT login (Print Manifest & Shipped) ──────────────────────────────────
  528 |     await page.getByRole('textbox', { name: 'Email Address' }).fill('oft+3025.alex.john@gmail.com');
  529 |     await page.getByRole('textbox', { name: 'Password' }).fill('oft+3025.alex.john@gmail.com');
  530 |     await page.getByRole('button', { name: 'Sign In' }).click();
  531 | 
  532 |     await page.getByRole('button', { name: 'Order Ready To Ship Status' }).click();
  533 |     await page.getByRole('link', { name: 'Out-Station Order Pending For Manifest Print', exact: true }).click();
  534 |     await page.getByRole('textbox', { name: 'Search' }).fill(intentId);
  535 |     await page.getByRole('combobox', { name: 'Logistics' }).click();
  536 |     await page.getByRole('option', { name: /SHIPROCKET/i }).or(page.getByRole('option').first()).click();
  537 |     await page.waitForTimeout(1000);
  538 |     const selectCourierCombo2 = page.getByRole('combobox', { name: 'Select Courier' });
  539 |     await selectCourierCombo2.waitFor({ state: 'visible', timeout: 15000 });
  540 |     await selectCourierCombo2.click();
  541 |     await page.getByRole('option').first().waitFor({ state: 'visible', timeout: 10000 }).catch(() => { });
  542 |     await page.getByRole('option', { name: /DTDC|Surface|Express/i }).or(page.getByRole('option').first()).click();
  543 |     await page.getByRole('button', { name: 'SEARCH' }).click();
  544 |     await screenshot('oft_print_manifest_searched');
  545 | 
  546 |     const matchRow2 = page.locator('tr').filter({ hasText: intentId }).first();
  547 |     await matchRow2.waitFor({ state: 'visible', timeout: 15000 });
  548 |     const chk2 = matchRow2.getByRole('checkbox').or(matchRow2.locator('.MuiCheckbox-root, input[type="checkbox"]')).first();
  549 |     await chk2.click({ force: true }).catch(() => { });
  550 |     const chkInput2 = matchRow2.locator('input[type="checkbox"]').first();
  551 |     if (await chkInput2.count() > 0) {
  552 |         await chkInput2.check({ force: true }).catch(() => { });
  553 |     }
  554 | 
  555 |     const printManifestBtn = page.getByRole('button', { name: 'PRINT MANIFEST' });
  556 |     if (await printManifestBtn.isDisabled().catch(() => false)) {
  557 |         await matchRow2.locator('td').first().click({ force: true }).catch(() => { });
  558 |         await chk2.click({ force: true }).catch(() => { });
  559 |     }
  560 | 
  561 |     const printManifestPromise = page.waitForEvent('popup', { timeout: 5000 }).catch(() => null);
  562 |     await printManifestBtn.click();
  563 |     const printManifestPage = await printManifestPromise;
  564 |     if (printManifestPage && !printManifestPage.isClosed()) {
  565 |         await printManifestPage.waitForLoadState('domcontentloaded').catch(() => { });
  566 |         await printManifestPage.waitForTimeout(1000);
  567 |         await printManifestPage.close().catch(() => { });
  568 |     }
  569 |     await page.bringToFront().catch(() => { });
  570 |     await page.waitForTimeout(2500);
  571 | 
  572 |     await page.getByRole('link', { name: 'Dashboard' }).click();
  573 |     await page.getByRole('button', { name: 'Order Shipped Status' }).click();
  574 |     await page.getByRole('link', { name: 'Out-Station Order Pickup Scheduled', exact: true }).click();
```