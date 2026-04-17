# Moving gears graduation hat
Print files for a gear-topped graduation hat powered by a 30RPM DC motor. See it in action on [YouTube](https://www.youtube.com/shorts/SgNcz4Yz9Ko).

<img width="400" alt="gear graduation hat" src="https://github.com/user-attachments/assets/20954f5b-8ce1-4869-8237-afe71edb1269" />


Read everything first! You may need to make modifications depending on what parts are available to you.

## Bill Of Materials

| Component               | Quantity | Link |
|-------------------------|----------|----------|
| N20 DC Motor, 30 RPM; ideally side-mounted shaft    | 1        | [Amazon](https://www.amazon.com/Hilitand-Brush-Geared-1218GE%E2%80%91N20-Reduction/dp/B08LL9Q7M4/ref=sxin_17_pa_sp_search_thematic_sspa?adgrpid=193135397666&content-id=amzn1.sym.cdeaf89b-0b83-4151-b82a-07a08dc40e89%3Aamzn1.sym.cdeaf89b-0b83-4151-b82a-07a08dc40e89&cv_ct_cx=n20+30+rpm&hvadid=798461285696&hvdev=c&hvexpln=0&hvlocphy=9021716&hvnetw=g&hvocijid=886110446030403631--&hvqmt=e&hvrand=886110446030403631&hvtargid=kwd-788924243933&hydadcr=7710_13881995_2490391&keywords=n20+30+rpm&mcid=6d7ab2600d3637e39a4d8e8a8ebba849&pd_rd_i=B08LL9Q7M4&pd_rd_r=f2e2b5e2-b931-439f-acf2-fdd7980e100e&pd_rd_w=A2gjA&pd_rd_wg=Kngwz&pf_rd_p=cdeaf89b-0b83-4151-b82a-07a08dc40e89&pf_rd_r=1FW4DC2ZXMP20T7SX57R&qid=1775916973&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sr=1-1-6e60e730-e094-43e9-99e8-1a4854cd27ff-spons&aref=YsYj3KCoaQ&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM&psc=1)         |
| Coin Cell Battery Holder with on/off switch              | 1        |  [DigiKey](https://www.digikey.com/en/products/detail/sparkfun-electronics/13883/6557334?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLljptGJtKQWKjXFMwuZEzO-1t&gclid=Cj0KCQjwkMjOBhC5ARIsADIdb3fPinj7iKJbFy7MTJQ7lED3OSOPmnUFa0wo-xU1tzyCKjTG6tS9rLUaAr0aEALw_wcB)        |
| Graduation hat       | 1  |          |
| M7 0.3mm thickness shims | 12 | 

#### Notes about materials
The gears generate just enough friction to occasionally lock the motor. It's strongly recommended to include 0.3mm shims under each gear. Note that standard washers (~1.3mm) are too thick. If you only have standard washers, you'll need to vertically scale the base so that the snap-fit gear shafts are taller. 

## Files to print

| Component               | Quantity |
|-------------------------|----------|
| [graduation hat gear mount](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/graduation%20hat%20gear%20mount.stl)    | 1        |
| [gear 1](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%201.stl)             | 1        |
| [gear 2](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%202.stl)       | 2  |
|[gear 3](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%203.stl) |2 |
|[gear 4](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%204.stl) |2 |
|[gear 5](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%205.stl) |2 |
|[gear 6](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%206.stl) |1 |
|[gear 6 with shaft](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%206%20with%20shaft.stl) |1 |
|[gear 7](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/gear%207.stl) |1 |
| optional: [block I gear base](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/block%20I%20gear%20base.stl) multi color print with [block I gold topper](https://github.com/shebuildsrobots/graduation_hat_gears/blob/main/block%20I%20gold%20topper.stl) sliced on top | 1 |

My original STEP file, should you want to make edits: `gears.step`

## Assembly guide

Add the shims to the base before snapping on the gears.

Punch a hole in the graduation hat where the motor (on the underside of the hat) will connect to gear 5 (on top of the hat).

<img width="727" height="781" alt="guide" src="https://github.com/user-attachments/assets/180f11cc-c3c5-4699-b055-794bd8f72cb1" />

Solder wires to the gearbox, if necessary, and solder the wires to your coin cell battery holder. Secure this unit with tape (or 3D print a mount) underneath the hat, with the shaft poking through the hole in your graduation hat.

Glue the motor mount base to your graduation hat, with the hole in the base mount centered over the hole in your hat.

Glue `gear 6 with shaft.stl` onto the shaft of your motor after the rest of the gear base and gears are assembled on top.

## Notes and Areas for Improvement
I left a hole in the center of the mount for your tassel, but there's really no place for the tassel to go where it won't disrupt the gears! If you redesign this to accomodate a tassel, you could put all of the mounts on stilts that attach to the hat so that all the gears are slightly raised and the tassel can go underneath.

To make your gear surfaces look nicer, turn on top layer ironing in your advanced slicer settings.



