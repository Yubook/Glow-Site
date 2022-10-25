.w-layout-grid {
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto auto;
  grid-template-rows: auto auto;
  grid-row-gap: 16px;
  grid-column-gap: 16px;
}

.w-commerce-commercecartwrapper {
  display: inline-block;
  position: relative;
}

.w-commerce-commercecartopenlink {
  background-color: #3898ec;
  border-bottom-left-radius: 0px;
  border-bottom-right-radius: 0px;
  border-top-left-radius: 0px;
  border-top-right-radius: 0px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-left: 15px;
  padding-right: 15px;
  text-decoration: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecartopenlinkcount {
  display: inline-block;
  height: 18px;
  min-width: 18px;
  margin-left: 8px;
  padding-right: 6px;
  padding-left: 6px;
  border-bottom-left-radius: 9px;
  border-bottom-right-radius: 9px;
  border-top-left-radius: 9px;
  border-top-right-radius: 9px;
  background-color: #fff;
  color: #3898ec;
  font-size: 11px;
  line-height: 18px;
  font-weight: 700;
  text-align: center;
}

.w-commerce-commercecartcontainerwrapper {
  position: fixed;
  left: 0px;
  top: 0px;
  right: 0px;
  bottom: 0px;
  z-index: 1001;
  background-color: rgba(0, 0, 0, 0.8);
}

.w-commerce-commercecartcontainerwrapper--cartType-modal {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.w-commerce-commercecartcontainerwrapper--cartType-leftSidebar {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
}

.w-commerce-commercecartcontainerwrapper--cartType-rightSidebar {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: end;
  -webkit-justify-content: flex-end;
  -ms-flex-pack: end;
  justify-content: flex-end;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
}

.w-commerce-commercecartcontainerwrapper--cartType-leftDropdown {
  position: absolute;
  top: 100%;
  left: 0px;
  right: auto;
  bottom: auto;
  background-color: transparent;
}

.w-commerce-commercecartcontainerwrapper--cartType-rightDropdown {
  position: absolute;
  left: auto;
  top: 100%;
  right: 0px;
  bottom: auto;
  background-color: transparent;
}

.w-commerce-commercecartcontainer {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  max-width: 480px;
  min-width: 320px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  overflow: auto;
  background-color: #fff;
  box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.25);
}

.w-commerce-commercecartheader {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-top: 16px;
  padding-bottom: 16px;
  padding-left: 24px;
  padding-right: 24px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-flex: 0;
  -webkit-flex-grow: 0;
  -ms-flex-positive: 0;
  flex-grow: 0;
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
  border-bottom-width: 1px;
  border-bottom-style: solid;
  border-bottom-color: #e6e6e6;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.w-commerce-commercecartheading {
  margin-top: 0px;
  margin-bottom: 0px;
  padding-left: 0px;
  padding-right: 0px;
}

.w-commerce-commercecartcloselink {
  width: 16px;
  height: 16px;
}

.w-commerce-commercecartformwrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-basis: 0%;
  -ms-flex-preferred-size: 0%;
  flex-basis: 0%;
}

.w-commerce-commercecartform {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-basis: 0%;
  -ms-flex-preferred-size: 0%;
  flex-basis: 0%;
}

.w-commerce-commercecartlist {
  overflow: auto;
  padding-top: 12px;
  padding-bottom: 12px;
  padding-left: 24px;
  padding-right: 24px;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-basis: 0%;
  -ms-flex-preferred-size: 0%;
  flex-basis: 0%;
  -webkit-overflow-scrolling: touch;
}

.w-commerce-commercecartitem {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-top: 12px;
  padding-bottom: 12px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.w-commerce-commercecartitemimage {
  width: 60px;
  height: 0%;
}

.w-commerce-commercecartiteminfo {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: 16px;
  margin-left: 16px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-basis: 0%;
  -ms-flex-preferred-size: 0%;
  flex-basis: 0%;
}

.w-commerce-commercecartoptionlist {
  text-decoration: none;
  padding-left: 0px;
  margin-bottom: 0px;
  list-style-type: none;
}

.w-commerce-commercecartquantity {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 10px;
  padding-top: 8px;
  padding-right: 6px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 60px;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecartquantity::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecartquantity:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecartquantity::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecartquantity::placeholder {
  color: #999;
}

.w-commerce-commercecartquantity:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecartfooter {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-top: 16px;
  padding-bottom: 24px;
  padding-left: 24px;
  padding-right: 24px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 0;
  -webkit-flex-grow: 0;
  -ms-flex-positive: 0;
  flex-grow: 0;
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #e6e6e6;
}

.w-commerce-commercecartlineitem {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 16px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: baseline;
  -webkit-align-items: baseline;
  -ms-flex-align: baseline;
  align-items: baseline;
  -webkit-box-flex: 0;
  -webkit-flex-grow: 0;
  -ms-flex-positive: 0;
  flex-grow: 0;
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
}

.w-commerce-commercecartordervalue {
  font-weight: 700;
}

.w-commerce-commercecartapplepaybutton {
  background-color: #000;
  border-bottom-left-radius: 2px;
  border-bottom-right-radius: 2px;
  border-top-left-radius: 2px;
  border-top-right-radius: 2px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 0px;
  padding-bottom: 0px;
  padding-left: 0px;
  padding-right: 0px;
  text-decoration: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  margin-bottom: 8px;
  height: 38px;
  min-height: 30px;
}

.w-commerce-commercecartapplepayicon {
  width: 100%;
  height: 50%;
  min-height: 20px;
}

.w-commerce-commercecartquickcheckoutbutton {
  background-color: #000;
  border-bottom-left-radius: 2px;
  border-bottom-right-radius: 2px;
  border-top-left-radius: 2px;
  border-top-right-radius: 2px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 0px;
  padding-bottom: 0px;
  padding-left: 15px;
  padding-right: 15px;
  text-decoration: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  margin-bottom: 8px;
  height: 38px;
}

.w-commerce-commercequickcheckoutgoogleicon {
  display: block;
  margin-right: 8px;
}

.w-commerce-commercequickcheckoutmicrosofticon {
  display: block;
  margin-right: 8px;
}

.w-commerce-commercecartcheckoutbutton {
  background-color: #3898ec;
  border-bottom-left-radius: 2px;
  border-bottom-right-radius: 2px;
  border-top-left-radius: 2px;
  border-top-right-radius: 2px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-left: 15px;
  padding-right: 15px;
  text-decoration: none;
  display: block;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  text-align: center;
}

.w-commerce-commercecartemptystate {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-top: 100px;
  padding-bottom: 100px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-basis: 0%;
  -ms-flex-preferred-size: 0%;
  flex-basis: 0%;
}

.w-commerce-commercecarterrorstate {
  margin-top: 0px;
  margin-right: 24px;
  margin-bottom: 24px;
  margin-left: 24px;
  padding-top: 10px;
  padding-right: 10px;
  padding-bottom: 10px;
  padding-left: 10px;
  -webkit-box-flex: 0;
  -webkit-flex-grow: 0;
  -ms-flex-positive: 0;
  flex-grow: 0;
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
  background-color: #ffdede;
}

.w-pagination-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}

.w-pagination-previous {
  display: block;
  color: #333;
  font-size: 14px;
  margin-left: 10px;
  margin-right: 10px;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #fafafa;
  border-top-width: 1px;
  border-right-width: 1px;
  border-bottom-width: 1px;
  border-left-width: 1px;
  border-top-color: #ccc;
  border-right-color: #ccc;
  border-bottom-color: #ccc;
  border-left-color: #ccc;
  border-top-style: solid;
  border-right-style: solid;
  border-bottom-style: solid;
  border-left-style: solid;
  border-top-right-radius: 2px;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}

.w-pagination-next {
  display: block;
  color: #333;
  font-size: 14px;
  margin-left: 10px;
  margin-right: 10px;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #fafafa;
  border-top-width: 1px;
  border-right-width: 1px;
  border-bottom-width: 1px;
  border-left-width: 1px;
  border-top-color: #ccc;
  border-right-color: #ccc;
  border-bottom-color: #ccc;
  border-left-color: #ccc;
  border-top-style: solid;
  border-right-style: solid;
  border-bottom-style: solid;
  border-left-style: solid;
  border-top-right-radius: 2px;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}

.w-commerce-commercecheckoutformcontainer {
  width: 100%;
  min-height: 100vh;
  padding-top: 20px;
  padding-bottom: 20px;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #f5f5f5;
}

.w-commerce-commercelayoutcontainer {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}

.w-commerce-commercelayoutmain {
  -webkit-flex-basis: 800px;
  -ms-flex-preferred-size: 800px;
  flex-basis: 800px;
  -webkit-box-flex: 0;
  -webkit-flex-grow: 0;
  -ms-flex-positive: 0;
  flex-grow: 0;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  margin-right: 20px;
}

.w-commerce-commercecheckoutcustomerinfowrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutblockheader {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: baseline;
  -webkit-align-items: baseline;
  -ms-flex-align: baseline;
  align-items: baseline;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-right: 20px;
  padding-left: 20px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #e6e6e6;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #e6e6e6;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #e6e6e6;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #e6e6e6;
  background-color: #fff;
}

.w-commerce-commercecheckoutblockcontent {
  padding-top: 20px;
  padding-bottom: 20px;
  padding-right: 20px;
  padding-left: 20px;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #e6e6e6;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #e6e6e6;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #e6e6e6;
  background-color: #fff;
}

.w-commerce-commercecheckoutlabel {
  margin-bottom: 8px;
}

.w-commerce-commercecheckoutemailinput {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 0px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutemailinput::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutemailinput:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutemailinput::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutemailinput::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutemailinput:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutshippingaddresswrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutshippingfullname {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutshippingfullname::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingfullname:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingfullname::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingfullname::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingfullname:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutshippingstreetaddress {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutshippingstreetaddress::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddress:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddress::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddress::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddress:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutshippingstreetaddressoptional {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutshippingstreetaddressoptional::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddressoptional:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddressoptional::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddressoptional::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstreetaddressoptional:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutrow {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: -8px;
  margin-left: -8px;
}

.w-commerce-commercecheckoutcolumn {
  padding-right: 8px;
  padding-left: 8px;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-basis: 0%;
  -ms-flex-preferred-size: 0%;
  flex-basis: 0%;
}

.w-commerce-commercecheckoutshippingcity {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutshippingcity::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcity:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcity::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcity::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcity:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutshippingstateprovince {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutshippingstateprovince::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstateprovince:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstateprovince::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstateprovince::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingstateprovince:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutshippingzippostalcode {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutshippingzippostalcode::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingzippostalcode:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingzippostalcode::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingzippostalcode::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingzippostalcode:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutshippingcountryselector {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 0px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutshippingcountryselector::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcountryselector:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcountryselector::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcountryselector::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutshippingcountryselector:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutshippingmethodswrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutshippingmethodslist {
  border-left-color: #e6e6e6;
  border-left-width: 1px;
  border-left-style: solid;
  border-right-color: #e6e6e6;
  border-right-width: 1px;
  border-right-style: solid;
}

.w-commerce-commercecheckoutshippingmethoditem {
  padding-top: 16px;
  padding-bottom: 16px;
  padding-right: 16px;
  padding-left: 16px;
  font-weight: 400;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  border-bottom-color: #e6e6e6;
  border-bottom-width: 1px;
  border-bottom-style: solid;
  margin-bottom: 0px;
  background-color: #fff;
  -webkit-box-align: baseline;
  -webkit-align-items: baseline;
  -ms-flex-align: baseline;
  align-items: baseline;
}

.w-commerce-commercecheckoutshippingmethoddescriptionblock {
  margin-left: 12px;
  margin-right: 12px;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
}

.w-commerce-commerceboldtextblock {
  font-weight: 700;
}

.w-commerce-commercecheckoutshippingmethodsemptystate {
  text-align: center;
  padding-left: 16px;
  padding-right: 16px;
  padding-top: 64px;
  padding-bottom: 64px;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #e6e6e6;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #e6e6e6;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #e6e6e6;
  background-color: #fff;
}

.w-commerce-commercecheckoutpaymentinfowrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutcardnumber {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  cursor: text;
}

.w-commerce-commercecheckoutcardnumber::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardnumber:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardnumber::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardnumber::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardnumber:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutcardnumber.-wfp-focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutcardexpirationdate {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  cursor: text;
}

.w-commerce-commercecheckoutcardexpirationdate::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardexpirationdate:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardexpirationdate::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardexpirationdate::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardexpirationdate:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutcardexpirationdate.-wfp-focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutcardsecuritycode {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  cursor: text;
}

.w-commerce-commercecheckoutcardsecuritycode::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardsecuritycode:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardsecuritycode::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardsecuritycode::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutcardsecuritycode:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutcardsecuritycode.-wfp-focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutbillingaddresstogglewrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
}

.w-commerce-commercecheckoutbillingaddresstogglecheckbox {
  margin-top: 4px;
}

.w-commerce-commercecheckoutbillingaddresstogglelabel {
  font-weight: 400;
  margin-left: 8px;
}

.w-commerce-commercecheckoutbillingaddresswrapper {
  margin-top: 16px;
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutbillingfullname {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutbillingfullname::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingfullname:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingfullname::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingfullname::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingfullname:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutbillingstreetaddress {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutbillingstreetaddress::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddress:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddress::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddress::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddress:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutbillingstreetaddressoptional {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutbillingstreetaddressoptional::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddressoptional:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddressoptional::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddressoptional::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstreetaddressoptional:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutbillingcity {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutbillingcity::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcity:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcity::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcity::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcity:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutbillingstateprovince {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutbillingstateprovince::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstateprovince:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstateprovince::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstateprovince::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingstateprovince:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutbillingzippostalcode {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 16px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutbillingzippostalcode::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingzippostalcode:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingzippostalcode::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingzippostalcode::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingzippostalcode:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutbillingcountryselector {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 0px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commercecheckoutbillingcountryselector::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcountryselector:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcountryselector::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcountryselector::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutbillingcountryselector:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutorderitemswrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutsummaryblockheader {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: baseline;
  -webkit-align-items: baseline;
  -ms-flex-align: baseline;
  align-items: baseline;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-right: 20px;
  padding-left: 20px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #e6e6e6;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #e6e6e6;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #e6e6e6;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #e6e6e6;
  background-color: #fff;
}

.w-commerce-commercecheckoutorderitemslist {
  margin-bottom: -20px;
}

.w-commerce-commercecheckoutorderitem {
  margin-bottom: 20px;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.w-commerce-commercecheckoutorderitemdescriptionwrapper {
  margin-left: 16px;
  margin-right: 16px;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
}

.w-commerce-commercecheckoutorderitemoptionlist {
  text-decoration: none;
  padding-left: 0px;
  margin-bottom: 0px;
  list-style-type: none;
}

.w-commerce-commercelayoutsidebar {
  -webkit-flex-basis: 320px;
  -ms-flex-preferred-size: 320px;
  flex-basis: 320px;
  -webkit-box-flex: 0;
  -webkit-flex-grow: 0;
  -ms-flex-positive: 0;
  flex-grow: 0;
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  position: -webkit-sticky;
  position: sticky;
  top: 20px;
}

.w-commerce-commercecheckoutordersummarywrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutsummarylineitem {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  margin-bottom: 8px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.w-commerce-commercecheckoutordersummaryextraitemslistitem {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  margin-bottom: 8px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.w-commerce-commercecheckoutsummarytotal {
  font-weight: 700;
}

.w-commerce-commercecheckoutdiscounts {
  background-color: #fff;
  border-bottom-color: #e6e6e6;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-left-color: #e6e6e6;
  border-left-style: solid;
  border-left-width: 1px;
  border-right-color: #e6e6e6;
  border-right-style: solid;
  border-right-width: 1px;
  border-top-color: #e6e6e6;
  border-top-style: solid;
  border-top-width: 1px;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  padding-bottom: 20px;
  padding-left: 20px;
  padding-right: 20px;
  padding-top: 20px;
}

.w-commerce-commercecheckoutdiscountslabel {
  margin-bottom: 8px;
  -webkit-flex-basis: 100%;
  -ms-flex-preferred-size: 100%;
  flex-basis: 100%;
}

.w-commerce-commercecheckoutdiscountsinput {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 0px;
  padding-top: 8px;
  padding-right: 12px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: auto;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-basis: 0%;
  -ms-flex-preferred-size: 0%;
  flex-basis: 0%;
  min-width: 0px;
}

.w-commerce-commercecheckoutdiscountsinput::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutdiscountsinput:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutdiscountsinput::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commercecheckoutdiscountsinput::placeholder {
  color: #999;
}

.w-commerce-commercecheckoutdiscountsinput:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commercecheckoutdiscountsbutton {
  background-color: #3898ec;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-left: 15px;
  padding-right: 15px;
  text-decoration: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  margin-left: 8px;
  -webkit-flex-shrink: 0;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  -webkit-box-flex: 0;
  -webkit-flex-grow: 0;
  -ms-flex-positive: 0;
  flex-grow: 0;
  height: 38px;
}

.w-commerce-commercecheckoutplaceorderbutton {
  background-color: #3898ec;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-left: 15px;
  padding-right: 15px;
  text-decoration: none;
  display: block;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  margin-bottom: 20px;
  text-align: center;
}

.w-commerce-commercecheckouterrorstate {
  margin-top: 16px;
  margin-bottom: 16px;
  padding-top: 10px;
  padding-right: 16px;
  padding-bottom: 10px;
  padding-left: 16px;
  background-color: #ffdede;
}

.w-commerce-commerceaddtocartform {
  margin-top: 0px;
  margin-right: 0px;
  margin-bottom: 15px;
  margin-left: 0px;
}

.w-commerce-commerceaddtocartoptionpillgroup {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 10px;
}

.w-commerce-commerceaddtocartoptionpill {
  margin-right: 10px;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 15px;
  padding-right: 15px;
  border-top-width: 1px;
  border-bottom-width: 1px;
  border-left-width: 1px;
  border-right-width: 1px;
  border-top-color: #000;
  border-bottom-color: #000;
  border-left-color: #000;
  border-right-color: #000;
  border-top-style: solid;
  border-bottom-style: solid;
  border-left-style: solid;
  border-right-style: solid;
  color: #000;
  background-color: #fff;
  cursor: pointer;
}

.w-commerce-commerceaddtocartoptionpill.w--ecommerce-pill-selected {
  color: #fff;
  background-color: #000;
}

.w-commerce-commerceaddtocartoptionpill.w--ecommerce-pill-disabled {
  color: #666;
  background-color: #e6e6e6;
  border-top-color: #e6e6e6;
  border-bottom-color: #e6e6e6;
  border-left-color: #e6e6e6;
  border-right-color: #e6e6e6;
  cursor: not-allowed;
  outline-style: none;
}

.w-commerce-commerceaddtocartquantityinput {
  background-color: #fafafa;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #ddd;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #ddd;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #ddd;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #ddd;
  border-bottom-left-radius: 3px;
  border-bottom-right-radius: 3px;
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
  display: block;
  height: 38px;
  line-height: 20px;
  margin-bottom: 10px;
  padding-top: 8px;
  padding-right: 6px;
  padding-bottom: 8px;
  padding-left: 12px;
  width: 60px;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commerceaddtocartquantityinput::-webkit-input-placeholder {
  color: #999;
}

.w-commerce-commerceaddtocartquantityinput:-ms-input-placeholder {
  color: #999;
}

.w-commerce-commerceaddtocartquantityinput::-ms-input-placeholder {
  color: #999;
}

.w-commerce-commerceaddtocartquantityinput::placeholder {
  color: #999;
}

.w-commerce-commerceaddtocartquantityinput:focus {
  border-top-color: #3898ec;
  border-right-color: #3898ec;
  border-bottom-color: #3898ec;
  border-left-color: #3898ec;
  outline-style: none;
}

.w-commerce-commerceaddtocartbutton {
  background-color: #3898ec;
  border-bottom-left-radius: 0px;
  border-bottom-right-radius: 0px;
  border-top-left-radius: 0px;
  border-top-right-radius: 0px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-left: 15px;
  padding-right: 15px;
  text-decoration: none;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

.w-commerce-commerceaddtocartbutton.w--ecommerce-add-to-cart-disabled {
  color: #666;
  background-color: #e6e6e6;
  border-top-color: #e6e6e6;
  border-bottom-color: #e6e6e6;
  border-left-color: #e6e6e6;
  border-right-color: #e6e6e6;
  cursor: not-allowed;
  outline-style: none;
}

.w-commerce-commercebuynowbutton {
  background-color: #3898ec;
  border-bottom-left-radius: 0px;
  border-bottom-right-radius: 0px;
  border-top-left-radius: 0px;
  border-top-right-radius: 0px;
  border-bottom-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
  border-top-width: 0px;
  color: #fff;
  cursor: pointer;
  padding-top: 9px;
  padding-bottom: 9px;
  padding-left: 15px;
  padding-right: 15px;
  text-decoration: none;
  display: inline-block;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  margin-top: 10px;
}

.w-commerce-commercebuynowbutton.w--ecommerce-buy-now-disabled {
  color: #666;
  background-color: #e6e6e6;
  border-top-color: #e6e6e6;
  border-bottom-color: #e6e6e6;
  border-left-color: #e6e6e6;
  border-right-color: #e6e6e6;
  cursor: not-allowed;
  outline-style: none;
}

.w-commerce-commerceaddtocartoutofstock {
  margin-top: 10px;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 10px;
  padding-right: 10px;
  background-color: #ddd;
}

.w-commerce-commerceaddtocarterror {
  margin-top: 10px;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 10px;
  padding-right: 10px;
  background-color: #ffdede;
}

.w-commerce-commerceorderconfirmationcontainer {
  width: 100%;
  min-height: 100vh;
  padding-top: 20px;
  padding-bottom: 20px;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #f5f5f5;
}

.w-commerce-commercecheckoutcustomerinfosummarywrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutsummaryitem {
  margin-bottom: 8px;
}

.w-commerce-commercecheckoutsummarylabel {
  margin-bottom: 8px;
}

.w-commerce-commercecheckoutsummaryflexboxdiv {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
}

.w-commerce-commercecheckoutsummarytextspacingondiv {
  margin-right: 0.33em;
}

.w-commerce-commercecheckoutshippingsummarywrapper {
  margin-bottom: 20px;
}

.w-commerce-commercecheckoutpaymentsummarywrapper {
  margin-bottom: 20px;
}

.w-commerce-commercepaypalcheckoutformcontainer {
  width: 100%;
  min-height: 100vh;
  padding-top: 20px;
  padding-bottom: 20px;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #f5f5f5;
}

.w-commerce-commercepaypalcheckouterrorstate {
  margin-top: 16px;
  margin-bottom: 16px;
  padding-top: 10px;
  padding-right: 16px;
  padding-bottom: 10px;
  padding-left: 16px;
  background-color: #ffdede;
}

@media screen and (max-width: 767px) {
  .w-commerce-commercelayoutcontainer {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .w-commerce-commercelayoutmain {
    margin-right: 0px;
    -webkit-flex-basis: auto;
    -ms-flex-preferred-size: auto;
    flex-basis: auto;
  }

  .w-commerce-commercelayoutsidebar {
    -webkit-flex-basis: auto;
    -ms-flex-preferred-size: auto;
    flex-basis: auto;
  }
}

@media screen and (max-width: 479px) {
  .w-commerce-commercecartcontainerwrapper--cartType-modal {
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .w-commerce-commercecartcontainerwrapper--cartType-leftDropdown {
    position: fixed;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .w-commerce-commercecartcontainerwrapper--cartType-rightDropdown {
    position: fixed;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .w-commerce-commercecartquantity {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutemailinput {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutshippingfullname {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutshippingstreetaddress {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutshippingstreetaddressoptional {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutrow {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .w-commerce-commercecheckoutshippingcity {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutshippingstateprovince {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutshippingzippostalcode {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutshippingcountryselector {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutcardnumber {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutcardexpirationdate {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutcardsecuritycode {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutbillingfullname {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutbillingstreetaddress {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutbillingstreetaddressoptional {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutbillingcity {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutbillingstateprovince {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutbillingzippostalcode {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutbillingcountryselector {
    font-size: 16px;
  }

  .w-commerce-commercecheckoutdiscountsinput {
    font-size: 16px;
  }

  .w-commerce-commerceaddtocartquantityinput {
    font-size: 16px;
  }
}

body {
  font-family: 'Plus Jakarta Display', sans-serif;
  color: #73729c;
  font-size: 18px;
  line-height: 1.667em;
}

h1 {
  margin-top: 0px;
  margin-bottom: 20px;
  color: #201e62;
  font-size: 58px;
  line-height: 1.138em;
  font-weight: 700;
}

h2 {
  margin-top: 0px;
  margin-bottom: 16px;
  color: #201e62;
  font-size: 38px;
  line-height: 1.342em;
  font-weight: 700;
}

h3 {
  margin-top: 0px;
  margin-bottom: 20px;
  color: #201e62;
  font-size: 24px;
  line-height: 1.375em;
  font-weight: 700;
}

h4 {
  margin-top: 0px;
  margin-bottom: 16px;
  color: #201e62;
  font-size: 20px;
  line-height: 1.4em;
  font-weight: 700;
  letter-spacing: 0.03em;
}

h5 {
  margin-bottom: 16px;
  color: #201e62;
  font-size: 18px;
  line-height: 1.222em;
  font-weight: 700;
  letter-spacing: 0.02em;
}

h6 {
  margin-bottom: 16px;
  color: #201e62;
  font-size: 16px;
  line-height: 1.375em;
  font-weight: 700;
}

p {
  margin-bottom: 0px;
}

a {
  -webkit-transition: color 350ms ease;
  transition: color 350ms ease;
  color: #4b80fb;
  text-decoration: underline;
}

a:hover {
  color: #fb6e67;
}

ul {
  margin-top: 0px;
  margin-bottom: 10px;
  padding-left: 40px;
}

ol {
  margin-top: 0px;
  margin-bottom: 10px;
  padding-left: 40px;
}

li {
  margin-bottom: 16px;
}

img {
  display: inline-block;
  max-width: 100%;
}

label {
  display: block;
  margin-bottom: 18px;
  color: #201e62;
  line-height: 1.111em;
  font-weight: 700;
  letter-spacing: 0.02em;
}

strong {
  color: #201e62;
  font-weight: 700;
}

blockquote {
  padding: 62px 74px;
  border-left: 0px solid #000;
  border-radius: 26px;
  background-color: #4b80fb;
  box-shadow: 0 4px 12px 0 rgba(8, 15, 52, 0.06);
  color: #fff;
  font-size: 24px;
  line-height: 1.375em;
  font-weight: 700;
  text-align: center;
}

figcaption {
  margin-top: 25px;
  text-align: center;
}

.mg-top-8px {
  margin-top: 8px;
}

.mg-bottom-8px {
  margin-bottom: 8px;
}

.mg-top-24px {
  margin-top: 24px;
}

.mg-top-32px {
  margin-top: 32px;
}

.mg-bottom-32px {
  margin-bottom: 32px;
}

.flex {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.text-center {
  text-align: center;
}

.color-white {
  color: #fff;
}

.bg-primary-1 {
  background-color: #fb6e67;
}

.bg-primary-2 {
  background-color: #4b80fb;
}

.bg-secondary-1 {
  background-color: #ebf1ff;
}

.bg-secondary-2 {
  background-color: #fff1f0;
}

.bg-neutral-800 {
  background-color: #201e62;
}

.bg-neutral-700 {
  background-color: #373b56;
}

.bg-neutral-600 {
  background-color: #73729c;
}

.bg-neutral-500 {
  background-color: #8f8fa3;
}

.bg-neutral-400 {
  background-color: #d9d9e8;
}

.bg-neutral-300 {
  background-color: #f2f1f6;
}

.bg-neutral-200 {
  background-color: #fafafd;
}

.bg-neutral-100 {
  background-color: #fff;
}

.styleguide-sidebar {
  position: -webkit-sticky;
  position: sticky;
  top: 32px;
  z-index: 2;
  height: 100%;
  min-height: 96vh;
  margin-right: 16px;
  -webkit-box-flex: 0;
  -webkit-flex: 0 14em;
  -ms-flex: 0 14em;
  flex: 0 14em;
}

.container-default {
  max-width: 1316px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

.styleguide-content {
  max-width: 100%;
  margin-left: 18px;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  border-radius: 24px;
  background-color: #fff;
  box-shadow: 0 8px 22px 0 rgba(35, 30, 97, 0.13);
}

.section-styleguide {
  padding-top: 86px;
  padding-bottom: 86px;
}

.styleguide-title {
  margin-top: 0px;
  color: #fff;
}

.styleguide-header {
  padding: 100px 68px;
  border-top-left-radius: 24px;
  border-top-right-radius: 24px;
  background-color: #4b80fb;
}

.sidebar-navigation {
  margin-bottom: 0px;
  padding-left: 0px;
  list-style-type: none;
}

.styleguide-icon-link {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 56px;
  height: 56px;
  margin-right: 16px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 18px;
  background-color: #fb6e67;
  -webkit-transition: background-color 250ms ease;
  transition: background-color 250ms ease;
}

.styelguide-sidebar-icon {
  width: 60%;
}

.styleguide-link {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding: 12px 20px;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 14px;
  -webkit-transition: background-color 350ms ease, color 350ms ease;
  transition: background-color 350ms ease, color 350ms ease;
  color: #73729c;
  text-decoration: none;
}

.styleguide-link:hover {
  background-color: #fff1f0;
  color: #fb6e67;
}

.styleguide-link.w--current {
  background-color: #fff1f0;
  -webkit-transition: color 300ms ease, background-color 300ms ease;
  transition: color 300ms ease, background-color 300ms ease;
  color: #fb6e67;
  font-weight: 700;
}

.styleguide-link-wrapper {
  margin-bottom: 8px;
}

.styleguide-sidebar-title {
  margin-bottom: 24px;
  padding-right: 20px;
  padding-bottom: 24px;
  padding-left: 20px;
  border-bottom: 1px solid #f2f1f6;
  color: #201e62;
  font-size: 22px;
  line-height: 24px;
}

.styleguide-sidebar-title.middle {
  margin-top: 24px;
  padding-top: 24px;
  border-top: 1px solid #f2f1f6;
}

.color-primary-grid {
  grid-column-gap: 24px;
  grid-row-gap: 24px;
  -ms-grid-columns: 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.color-container {
  border-radius: 16px;
  background-color: #fff;
  box-shadow: 0 8px 16px 0 rgba(17, 10, 99, 0.04), 0 12px 22px 0 rgba(128, 118, 247, 0.04);
}

.color-block {
  min-height: 120px;
  border-top-left-radius: 16px;
  border-top-right-radius: 16px;
}

.color-block.bg-primary-1 {
  background-color: #fb6e67;
}

.color-block.bg-neutral-100.bg-white {
  border-bottom: 1px solid #d9d9e8;
}

.color-content {
  padding: 22px 16px 24px;
}

.color-title {
  color: #201e62;
  font-size: 18px;
  line-height: 20px;
  font-weight: 700;
}

.color-hex {
  color: #8f8fa3;
  line-height: 20px;
}

.styleguide-subtitle {
  margin-top: 0px;
}

.styleguide-subtitle.rich-text {
  margin-top: 88px;
}

.color-content-wrapper {
  padding-bottom: 56px;
}

.color-content-wrapper.last {
  padding-bottom: 0px;
}

.color-secondary-grid {
  grid-column-gap: 24px;
  grid-row-gap: 24px;
  -ms-grid-columns: 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.color-neutral-grid {
  grid-column-gap: 24px;
  grid-row-gap: 24px;
  -ms-grid-columns: 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr;
}

.typography-container {
  padding-top: 54px;
  padding-bottom: 54px;
  border-bottom: 1px solid #f2f1f6;
}

.typography-container.last {
  padding-bottom: 0px;
  border-bottom-width: 0px;
}

.container-small-left {
  max-width: 620px;
  padding-right: 24px;
}

.typography-details {
  margin-top: 15px;
  color: #4b80fb;
}

.paragraph-large {
  font-size: 24px;
  line-height: 1.583em;
}

.styleguide-subheader {
  padding: 56px 68px;
  background-color: #fafafd;
}

.styleguide-content-wrapper {
  padding: 110px 68px;
}

.icons-grid {
  grid-column-gap: 24px;
  grid-row-gap: 24px;
  grid-template-columns: repeat(auto-fit, 80px);
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.buttons-grid {
  grid-column-gap: 24px;
  grid-row-gap: 56px;
  grid-template-columns: repeat(auto-fit, 250px);
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.button-primary {
  padding: 22px 42px;
  border-radius: 1000px;
  background-color: #fb6e67;
  box-shadow: 0 10px 18px 0 rgba(239, 113, 107, 0.15);
  -webkit-transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: transform 350ms ease, box-shadow 350ms ease;
  transition: transform 350ms ease, box-shadow 350ms ease, -webkit-transform 350ms ease;
  color: #fff;
  font-size: 17px;
  line-height: 1em;
  font-weight: 700;
  text-align: center;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.button-primary:hover {
  box-shadow: 0 15px 18px 0 rgba(239, 113, 107, 0.28);
  -webkit-transform: scale3d(1.03, 1.03, 1.01);
  transform: scale3d(1.03, 1.03, 1.01);
  color: #fff;
}

.button-primary.small {
  padding: 14px 32px;
  font-size: 16px;
  line-height: 18px;
}

.button-primary.large {
  padding: 20px 68px;
  font-size: 22px;
  line-height: 24px;
}

.button-primary.full-width {
  display: block;
  -webkit-align-self: stretch;
  -ms-flex-item-align: stretch;
  -ms-grid-row-align: stretch;
  align-self: stretch;
}

.button-primary.checkout {
  margin-top: 15px;
  margin-bottom: 0px;
}

.button-primary._2-buttons {
  margin-right: 24px;
}

.button-primary.footer-store {
  margin-right: 11px;
  margin-bottom: 20px;
  padding: 16px 31px;
}

.button-primary.home-hero {
  margin-right: 24px;
  margin-bottom: 20px;
}

.button-primary.header-button {
  margin-left: 32px;
  padding: 16px 32px;
  font-size: 16px;
}

.button-primary.add-to-cart {
  display: block;
  width: 100%;
  -webkit-align-self: stretch;
  -ms-flex-item-align: stretch;
  -ms-grid-row-align: stretch;
  align-self: stretch;
}

.button-primary.header-button-mobile {
  padding: 14px 32px;
  font-size: 16px;
  line-height: 18px;
}

.button-primary.blog-newsletter {
  position: absolute;
  right: 17px;
  padding: 19px 32px;
}

.button-primary.cart-empty {
  margin-top: 40px;
}

.button-secondary {
  padding: 22px 40px;
  border-radius: 1000px;
  background-color: #fff;
  box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.04), 0 6px 23px 0 rgba(32, 30, 98, 0.07);
  -webkit-transition: box-shadow 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
  transition: transform 350ms ease, box-shadow 350ms ease, color 350ms ease;
  transition: transform 350ms ease, box-shadow 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
  color: #201e62;
  font-size: 17px;
  line-height: 1em;
  text-align: center;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.button-secondary:hover {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.04), 0 16px 23px 0 rgba(32, 30, 98, 0.07);
  -webkit-transform: scale3d(1.03, 1.03, 1.01);
  transform: scale3d(1.03, 1.03, 1.01);
}

.button-secondary.small {
  padding: 14px 32px;
  font-size: 16px;
  line-height: 18px;
}

.button-secondary.large {
  padding: 20px 68px;
  font-size: 22px;
  line-height: 24px;
}

.button-secondary.discounts {
  height: auto;
  margin-left: 0px;
  padding-right: 16px;
  padding-bottom: 15px;
  padding-left: 16px;
  -webkit-box-flex: 0;
  -webkit-flex: 0 auto;
  -ms-flex: 0 auto;
  flex: 0 auto;
  border-width: 1px;
}

.button-secondary.home-hero {
  margin-bottom: 20px;
}

.button-secondary.blog-category {
  margin-top: 4px;
  margin-bottom: 4px;
  margin-left: 20px;
  padding: 14px 24px;
  box-shadow: 0 2px 7px 0 rgba(24, 20, 67, 0.08);
}

.button-secondary.blog-category.w--current {
  background-color: #fb6e67;
  box-shadow: none;
  color: #fff;
  font-weight: 700;
}

.button-secondary.blog-category.all {
  margin-top: 4px;
  margin-bottom: 4px;
}

.button-secondary.blog-category.all.w--current {
  background-color: #fb6e67;
  box-shadow: 0 0 0 0 rgba(24, 20, 67, 0.08);
  color: #fff;
  font-weight: 700;
}

.button-secondary.full-width {
  display: block;
  margin-top: 16px;
}

.styleguide-button-container {
  position: absolute;
  left: 0%;
  top: auto;
  right: 0%;
  bottom: 24px;
}

.cards-grid {
  -webkit-box-align: start;
  -webkit-align-items: start;
  -ms-flex-align: start;
  align-items: start;
  grid-column-gap: 24px;
  grid-row-gap: 40px;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.header {
  padding-top: 40px;
  padding-bottom: 40px;
  background-color: transparent;
}

.header-logo {
  width: 200px;
}

.header-logo.alternative-white {
  display: none;
}

.header-navigation {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 0px;
  padding-left: 0px;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  list-style-type: none;
}

.nav-item-wrapper {
  margin-right: 26px;
  margin-bottom: 0px;
}

.nav-item-wrapper.mobile {
  display: none;
}

.nav-link {
  -webkit-transition: color 350ms ease;
  transition: color 350ms ease;
  color: #201e62;
  text-decoration: none;
}

.nav-link:hover {
  color: #fb6e67;
}

.nav-link.contact-alternative {
  color: #fff;
}

.nav-link.contact-alternative:hover {
  color: #fb6e67;
}

.menu-button {
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.display-1 {
  font-size: 80px;
  line-height: 94px;
}

.display-2 {
  font-size: 68px;
  line-height: 76px;
}

.display-3 {
  font-size: 32px;
  line-height: 36px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.footer {
  overflow: hidden;
  padding-top: 80px;
  padding-bottom: 10px;
}

.footer-grid {
  position: relative;
  z-index: 1;
  margin-bottom: 107px;
  grid-column-gap: 20px;
  -ms-grid-columns: auto auto;
  grid-template-columns: auto auto;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.footer-logo-container {
  margin-bottom: 14px;
  -webkit-transition-property: -webkit-transform;
  transition-property: -webkit-transform;
  transition-property: transform;
  transition-property: transform, -webkit-transform;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.footer-logo-container:hover {
  -webkit-transform: scale3d(1.05, 1.05, 1.01);
  transform: scale3d(1.05, 1.05, 1.01);
}

.footer-logo {
  width: 213px;
}

.utility-page-hero {
  padding-top: 80px;
  padding-bottom: 80px;
  background-color: #4b80fb;
}

.section {
  padding-top: 200px;
  padding-bottom: 200px;
}

.section.checkout-hero {
  position: relative;
  overflow: hidden;
  padding-top: 80px;
  padding-bottom: 80px;
  background-color: #4b80fb;
}

.section.home-hero {
  position: relative;
  overflow: hidden;
  padding-top: 34px;
  padding-bottom: 0px;
}

.section.home-services {
  overflow: hidden;
  padding-top: 174px;
}

.section.cta-1 {
  padding-top: 0px;
  padding-bottom: 0px;
}

.section.cta-2 {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  padding-top: 0px;
  padding-bottom: 0px;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-image: -webkit-gradient(linear, left top, left bottom, color-stop(50%, #fafafd), color-stop(0, #fff));
  background-image: linear-gradient(180deg, #fafafd 50%, #fff 0);
}

.section.cta-2.bg-transparent {
  background-image: none;
}

.section.home-features {
  position: relative;
  overflow: hidden;
  padding-top: 60px;
}

.section.home-testimonials {
  overflow: hidden;
}

.section.home-mission {
  overflow: hidden;
}

.section.home-blog {
  overflow: hidden;
  background-color: #fafafd;
}

.section.about-hero {
  position: relative;
  overflow: hidden;
  padding-top: 75px;
  padding-bottom: 0px;
}

.section.story {
  overflow: hidden;
  padding-top: 161px;
  padding-bottom: 178px;
}

.section.mission {
  overflow: hidden;
  padding-top: 163px;
  padding-bottom: 135px;
  background-color: #fafafd;
}

.section.about-team {
  overflow: hidden;
  padding-bottom: 160px;
  background-color: #fafafd;
}

.section.values {
  overflow: hidden;
}

.section.blog {
  padding-top: 140px;
  padding-bottom: 140px;
  background-color: #fafafd;
}

.section.blog-hero {
  overflow: hidden;
  padding-top: 75px;
  padding-bottom: 140px;
}

.section.blog-post-articles {
  overflow: hidden;
  padding-top: 140px;
  padding-bottom: 140px;
  background-color: #fafafd;
}

.section.blog-post {
  overflow: hidden;
  padding-top: 50px;
  padding-bottom: 140px;
}

.section.team-members {
  overflow: hidden;
  padding-top: 75px;
  padding-bottom: 174px;
}

.section.more-doctors {
  padding-top: 140px;
  padding-bottom: 140px;
}

.section.team-page {
  position: relative;
  overflow: hidden;
  padding-top: 27px;
  padding-bottom: 140px;
}

.section.services {
  overflow: hidden;
  padding-top: 70px;
}

.section.packages {
  overflow: hidden;
  padding-top: 70px;
  padding-bottom: 100px;
}

.section.packages-faqs {
  overflow: hidden;
  padding-top: 100px;
  padding-bottom: 180px;
}

.section.packages-testimonials {
  overflow: hidden;
  padding-top: 140px;
  padding-bottom: 140px;
  background-color: #fafafd;
}

.section.plan {
  padding-top: 46px;
  padding-bottom: 140px;
}

.section.contact-faqs {
  overflow: hidden;
  padding-top: 140px;
  padding-bottom: 140px;
  background-color: #fafafd;
}

.section.contact {
  position: relative;
  overflow: hidden;
  padding-top: 62px;
  padding-bottom: 177px;
}

.section.packages-category {
  overflow: hidden;
  padding-top: 70px;
}

.section.blog-category {
  padding-top: 70px;
  padding-bottom: 140px;
  background-color: #fafafd;
}

.section.utility-page {
  padding-top: 70px;
}

.section.utility-page.changelog {
  padding-bottom: 140px;
}

.section.utility-page.short {
  padding-bottom: 120px;
}

.section.blog-newsletter {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-top: 0px;
  padding-bottom: 0px;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-image: -webkit-gradient(linear, left top, left bottom, color-stop(50%, #fafafd), color-stop(0, #fff));
  background-image: linear-gradient(180deg, #fafafd 50%, #fff 0);
}

.utility-page-wrap {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  min-height: 800px;
  padding: 60px 24px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #fafafd;
}

.utility-page-wrap.password {
  min-height: 640px;
}

.utility-page-content-password {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  max-width: 580px;
  padding: 72px 50px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  border-style: solid;
  border-width: 1px;
  border-color: #f2f1f6;
  border-radius: 26px;
  background-color: #fff;
  box-shadow: 0 36px 40px 0 rgba(36, 49, 160, 0.06);
  text-align: center;
}

.utility-page-form {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.input {
  height: 68px;
  margin-bottom: 0px;
  padding-right: 21px;
  padding-left: 21px;
  border-style: solid;
  border-width: 1px;
  border-color: #d9d9e8;
  border-radius: 50px;
  box-shadow: 0 2px 10px 0 rgba(15, 19, 51, 0.03);
  -webkit-transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease, color 350ms ease;
  transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease, color 350ms ease;
  color: #373b56;
  font-size: 18px;
  line-height: 1em;
  letter-spacing: 0.02em;
}

.input:hover {
  border-color: #fb6e67;
}

.input:focus {
  border-width: 2px;
  border-color: #fb6e67;
  box-shadow: 0 6px 16px 0 rgba(251, 110, 103, 0.11);
  color: #373b56;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.input.-wfp-focus {
  border-width: 2px;
  border-color: #fb6e67;
  box-shadow: 0 6px 16px 0 rgba(251, 110, 103, 0.11);
  color: #373b56;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.input::-webkit-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.input:-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.input::-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.input::placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.input.password {
  margin-bottom: 20px;
}

.input.checkout {
  height: 54px;
  margin-bottom: 16px;
  background-color: #fff;
}

.input.discounts {
  height: 54px;
  margin-bottom: 16px;
  -webkit-box-flex: 0;
  -webkit-flex: 0 auto;
  -ms-flex: 0 auto;
  flex: 0 auto;
  border-width: 1px;
  background-color: #fff;
}

.input.blog-newsletter {
  height: 82px;
  padding-right: 175px;
  padding-left: 27px;
}

.utility-page-content-404 {
  position: relative;
  z-index: 1;
}

.container-medium-761px {
  max-width: 761px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-medium-761px.changelog {
  margin-top: -120px;
}

.divider {
  width: 100%;
  height: 1px;
  background-color: #f2f1f6;
}

.divider.utility-pages {
  margin-top: 60px;
  margin-bottom: 60px;
}

.divider.card-testimonial {
  height: 1.5px;
  margin-top: 31px;
  margin-bottom: 28px;
  background-color: #d9d9e8;
}

.divider.card-service {
  height: 1.5px;
  margin-top: 18px;
  margin-bottom: 24px;
}

.divider.card-article-item {
  height: 1.5px;
  margin-top: 24px;
  margin-bottom: 24px;
}

.divider.cta-2 {
  position: absolute;
  background-color: #d9d9e8;
}

.divider.card-value {
  height: 1.5px;
  margin-top: 18px;
  margin-bottom: 18px;
}

.divider.card-article-featured {
  height: 1.5px;
  margin-top: 33px;
  margin-bottom: 20px;
}

.divider.card-service-page {
  height: 1.5px;
  margin-top: 18px;
  margin-bottom: 24px;
}

.divider.plan {
  margin-top: 75px;
  margin-bottom: 80px;
}

.paragraph.password {
  margin-bottom: 40px;
}

.paragraph._404 {
  max-width: 350px;
  margin-right: auto;
  margin-bottom: 40px;
  margin-left: auto;
}

.paragraph.home-hero {
  margin-bottom: 48px;
}

.paragraph.home-mission {
  margin-bottom: 40px;
}

.paragraph.footer-main-content {
  margin-bottom: 32px;
}

.paragraph.about-hero {
  max-width: 621px;
  margin-right: auto;
  margin-bottom: 40px;
  margin-left: auto;
  text-align: center;
}

.paragraph.card-blog-post-hero {
  margin-bottom: 40px;
}

.paragraph.card-team-page {
  margin-bottom: 32px;
}

.paragraph.packages {
  max-width: 540px;
  margin-right: auto;
  margin-left: auto;
}

.paragraph.faq-content {
  margin-left: 76px;
}

.paragraph.plan-description {
  max-width: 681px;
  margin-bottom: 37px;
}

.paragraph.card-get-plan {
  margin-bottom: 34px;
}

.paragraph.packages-category {
  max-width: 540px;
  margin-right: auto;
  margin-left: auto;
}

.paragraph.card-careers-perk {
  margin-bottom: 0px;
}

.paragraph.card-careers-team {
  margin-bottom: 25px;
  font-size: 16px;
}

.paragraph-small {
  font-size: 16px;
  line-height: 1.625em;
  letter-spacing: 0.02em;
}

.card {
  overflow: hidden;
  border-style: solid;
  border-width: 1px;
  border-color: #f2f1f6;
  border-radius: 26px;
  background-color: #fff;
  box-shadow: 0 35px 40px 0 rgba(36, 49, 160, 0.06);
}

.card.changelog {
  position: relative;
  overflow: visible;
  margin-bottom: 28px;
  padding: 60px 50px;
}

.card.checkout {
  margin-bottom: 40px;
}

.card.checkout.last {
  margin-bottom: 0px;
}

.card.checkout.order-summary {
  margin-bottom: 0px;
  border-bottom-width: 0px;
  border-bottom-left-radius: 0px;
  border-bottom-right-radius: 0px;
  box-shadow: none;
}

.card.testimonial {
  overflow: visible;
  max-width: 592px;
  margin-bottom: 61px;
  padding: 50px 48px 20px;
}

.card.testimonial.last {
  margin-bottom: 0px;
  -webkit-align-self: flex-end;
  -ms-flex-item-align: end;
  align-self: flex-end;
}

.card.service {
  display: block;
  padding: 48px 32px 56px;
  color: #73729c;
  text-decoration: none;
}

.card.article-item-card {
  position: relative;
  z-index: 1;
  max-width: 567px;
  margin-top: auto;
  margin-right: 20px;
  margin-left: 20px;
  padding: 40px 32px 32px;
}

.card.value {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding: 36px 52px 46px;
}

.card.team {
  height: 100%;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
  -webkit-transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease, -webkit-transform 350ms ease;
  color: #73729c;
  text-decoration: none;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.card.team:hover {
  box-shadow: 0 3px 10px 0 rgba(36, 49, 160, 0.06);
  -webkit-transform: scale3d(0.98, 0.98, 1.01);
  transform: scale3d(0.98, 0.98, 1.01);
  color: #73729c;
}

.card.article-featured {
  position: absolute;
  right: 38px;
  z-index: 1;
  max-width: 45%;
  padding: 54px 32px 36px;
}

.card.blog-post-hero {
  position: absolute;
  left: 0px;
  z-index: 2;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-width: 682px;
  padding: 76px 38px 76px 48px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}

.card.about-author {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-width: 740px;
  margin-top: 40px;
  margin-right: auto;
  margin-left: auto;
  padding: 58px 48px 49px;
  -webkit-transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease, -webkit-transform 350ms ease;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.card.about-author:hover {
  box-shadow: 0 3px 10px 0 rgba(36, 49, 160, 0.06);
  -webkit-transform: scale3d(0.98, 0.98, 0.01);
  transform: scale3d(0.98, 0.98, 0.01);
}

.card.team-page {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 85px;
  padding: 44px 52px;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.card.service-page {
  padding: 48px 32px 56px;
  color: #73729c;
  text-decoration: none;
}

.card.packages {
  position: relative;
  z-index: 1;
  padding: 71px 40px;
}

.card.faq-wrapper {
  margin-bottom: 24px;
  padding: 43px 32px;
  box-shadow: 0 3px 10px 0 rgba(86, 102, 126, 0.06);
  -webkit-transition: opacity 350ms ease;
  transition: opacity 350ms ease;
  cursor: pointer;
}

.card.faq-wrapper:hover {
  opacity: 0.7;
}

.card.faq-wrapper.last {
  margin-bottom: 0px;
}

.card.get-plan {
  position: -webkit-sticky;
  position: sticky;
  top: 10px;
  padding: 48px 32px 68px;
}

.card.get-plan-mobile {
  display: none;
  margin-top: 60px;
  padding: 48px 32px 68px;
}

.card.contact {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  min-height: 704px;
  padding: 64px 40px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.card.default {
  padding: 60px 40px;
}

.checkout-form {
  padding: 80px 0px 140px;
  background-color: #fafafd;
}

.checkout-block-header {
  padding: 30px 40px 20px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  border-width: 0px;
}

.checkout-block-content {
  padding: 10px 40px 40px;
  border-right-width: 0px;
  border-bottom-width: 0px;
  border-left-width: 0px;
}

.title.checkout {
  margin-right: 20px;
  margin-bottom: 0px;
}

.title.order-item {
  color: #201e62;
  font-size: 22px;
  font-weight: 700;
  text-decoration: none;
}

.title.order-item:hover {
  color: #fb6e67;
}

.title.checkout-hero {
  color: #fff;
}

.title.home-features {
  max-width: 461px;
}

.title.home-services-title {
  margin-bottom: 0px;
}

.title.cta-1 {
  position: relative;
  z-index: 1;
  max-width: 662px;
  margin-bottom: 40px;
  color: #201e62;
}

.title.testimonials {
  margin-bottom: 32px;
}

.title.cta-2 {
  position: relative;
  z-index: 1;
  max-width: 601px;
  margin-right: 40px;
  margin-bottom: 20px;
  color: #201e62;
}

.title.card-service {
  margin-bottom: 0px;
}

.title.footer-nav-title {
  margin-bottom: 32px;
  font-size: 14px;
  line-height: 1.143em;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.title.home-hero {
  color: #646368;
}

.title.card-value {
  margin-bottom: 0px;
}

.title.card-team {
  margin-bottom: 8px;
}

.title.about-team {
  margin-bottom: 0px;
}

.title.blog {
  margin-bottom: 0px;
}

.title.blog-post-articles {
  margin-bottom: 0px;
}

.title.card-blog-post-hero {
  margin-bottom: 16px;
  font-size: 38px;
  line-height: 1.342em;
}

.title.about-author-name {
  margin-bottom: 4px;
  font-size: 24px;
  line-height: 1.375em;
}

.title.more-doctors {
  margin-bottom: 0px;
}

.title.team-about {
  position: relative;
  z-index: 1;
  max-width: 740px;
  margin-right: auto;
  margin-bottom: 13px;
  margin-left: auto;
}

.title.card-team-page-name {
  margin-bottom: 6px;
  font-size: 38px;
  line-height: 1.111em;
}

.title.services {
  margin-bottom: 0px;
}

.title.card-service-page {
  margin-bottom: 0px;
}

.title.package-item {
  margin-bottom: 4px;
}

.title.faq {
  margin-bottom: 0px;
}

.title.plan {
  margin-right: 10px;
  margin-bottom: 0px;
  color: #201e62;
  font-size: 58px;
  line-height: 1.138em;
  font-weight: 700;
}

.title.card-get-plan {
  margin-right: 6px;
  margin-bottom: 0px;
  font-size: 24px;
  line-height: 1.375em;
}

.title.contact {
  margin-bottom: 16px;
}

.title.category {
  margin-right: 10px;
  margin-bottom: 0px;
  color: #201e62;
  font-size: 58px;
  line-height: 1.138em;
  font-weight: 700;
}

.title.cart-item-title {
  color: #201e62;
  font-size: 22px;
  font-weight: 700;
  text-decoration: none;
}

.title.cart-item-title:hover {
  color: #fb6e67;
}

.title.blog-newsletter {
  position: relative;
  z-index: 1;
  max-width: 601px;
  margin-right: 40px;
  margin-bottom: 20px;
  color: #fff;
}

.title.careers-hero {
  margin-bottom: 14px;
}

.title.card-careers-perk {
  margin-bottom: 3px;
}

.title.careers-perks {
  margin-bottom: 47px;
  text-align: center;
}

.title.careers-team {
  max-width: 691px;
  margin-right: auto;
  margin-bottom: 53px;
  margin-left: auto;
  text-align: center;
}

.title.card-careers-team {
  margin-bottom: 20px;
}

.title.neutral-100 {
  color: #fff;
}

.title.neutral-100.cta {
  margin-bottom: 41px;
}

.split-content.checkout-left {
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
}

.split-content.checkout-right {
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
}

.split-content.header-right {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 50%;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.split-content.header-left {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.split-content.home-hero-left {
  position: relative;
  z-index: 1;
  max-width: 45%;
  margin-right: 40px;
}

.split-content.home-features-left {
  max-width: 53%;
  margin-right: 40px;
}

.split-content.home-services-left {
  max-width: 432px;
}

.split-content.home-mission-right {
  position: relative;
  z-index: 1;
  max-width: 43%;
}

.split-content.testimonials-left {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  max-width: 48%;
  margin-right: 60px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}

.split-content.testimonials-right {
  position: relative;
  z-index: 1;
  max-width: 47%;
}

.split-content.story-left {
  position: relative;
  z-index: 1;
  max-width: 533px;
  margin-right: 40px;
}

.split-content.about-team-left {
  max-width: 518px;
}

.split-content.mission-right {
  position: relative;
  z-index: 1;
  max-width: 560px;
}

.split-content.services-left {
  max-width: 680px;
}

.split-content.plan-body {
  max-width: 728px;
  margin-right: 40px;
}

.split-content.plan-sidebar {
  max-width: 422px;
  font-weight: 400;
}

.split-content.contact-left {
  position: relative;
  z-index: 1;
  max-width: 637px;
  margin-right: 60px;
}

.split-content.contact-right {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-width: 41%;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}

.checkout-field-label {
  margin-top: 15px;
  margin-bottom: 10px;
}

.checkout-required-text {
  color: #fb6e67;
  font-size: 20px;
}

.checkout-billing-address-toggle {
  margin-top: 10px;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.checkout-checkbox-label {
  margin-bottom: 0px;
}

.checkout-checkbox {
  margin-top: 0px;
}

.order-item-list {
  margin-bottom: -40px;
}

.order-item {
  margin-bottom: 40px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.image-wrapper {
  overflow: hidden;
}

.image-wrapper.order-item-image {
  max-width: 80px;
  margin-right: 20px;
  margin-bottom: 15px;
  -webkit-align-self: flex-start;
  -ms-flex-item-align: start;
  align-self: flex-start;
  border-radius: 24px;
}

.image-wrapper.card-service {
  width: 100px;
  height: 100px;
  min-width: 100px;
  margin-bottom: 32px;
  border-radius: 24px;
}

.image-wrapper.article-item-image {
  margin-bottom: -101px;
  border-radius: 26px;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}

.image-wrapper.article-featured {
  max-width: 72%;
  min-height: 471px;
  -webkit-align-self: stretch;
  -ms-flex-item-align: stretch;
  -ms-grid-row-align: stretch;
  align-self: stretch;
  border-radius: 31px;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}

.image-wrapper.about-author {
  width: 145px;
  height: 145px;
  min-width: 145px;
  margin-right: 37px;
  border-radius: 1000px;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}

.image-wrapper.card-service-page {
  width: 100px;
  height: 100px;
  min-width: 100px;
  margin-bottom: 32px;
  border-radius: 24px;
}

.image-wrapper.package-item-icon {
  width: 98px;
  height: 98px;
  min-width: 98px;
  margin-bottom: 15px;
  border-radius: 26px;
}

.image-wrapper.cart-item-image {
  max-width: 80px;
  margin-right: 20px;
  margin-bottom: 15px;
  -webkit-align-self: flex-start;
  -ms-flex-item-align: start;
  align-self: flex-start;
  border-radius: 24px;
}

.image.order-item-image {
  width: auto;
  height: auto;
}

.image.home-hero {
  position: relative;
  z-index: 1;
  width: 57%;
  margin-right: -54px;
}

.image.home-features {
  position: relative;
  z-index: 2;
  display: block;
  margin-right: auto;
  margin-bottom: 45px;
  margin-left: auto;
}

.image.home-mission {
  position: relative;
  z-index: 1;
  width: 52%;
}

.image.card-testimonial-about {
  width: 104px;
  height: 104px;
  min-width: 104px;
  margin-right: 17px;
  border-radius: 1000px;
  box-shadow: 0 4px 18px 0 rgba(11, 52, 75, 0.11);
}

.image.card-testimonial-stars {
  margin-bottom: 5px;
  margin-left: -10px;
}

.image.home-feature-icon {
  width: 32px;
  height: 32px;
  min-width: 32px;
  margin-right: 14px;
  border-radius: 1000px;
  box-shadow: 4px 4px 13px 0 rgba(251, 110, 103, 0.14);
}

.image.footer-contact-icon {
  margin-right: 9px;
}

.image.about-hero {
  position: relative;
  z-index: 2;
}

.image.value {
  width: 92px;
  height: 92px;
  min-width: 92px;
  margin-right: 22px;
  border-radius: 32px;
}

.image.card-team {
  width: 100%;
}

.image.story {
  position: relative;
  z-index: 1;
  width: 63%;
  margin-right: -145px;
}

.image.mission {
  position: relative;
  z-index: 1;
  width: 64%;
  margin-right: 40px;
  margin-left: -184px;
}

.image.article-featured {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}

.image.blog-post-main-image {
  position: relative;
  z-index: 1;
  max-width: 83%;
  min-height: 591px;
  border-radius: 34px;
  -o-object-fit: cover;
  object-fit: cover;
}

.image.about-author {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}

.image.card-team-page {
  width: 330px;
  height: 330px;
  min-width: 330px;
  margin-right: 36px;
  border-radius: 40px;
}

.image.package-item-feature-icon {
  position: relative;
  top: 2px;
  width: 27px;
  height: 27px;
  min-width: 27px;
  margin-right: 9px;
  border-radius: 1000px;
  box-shadow: 0 5px 10px 0 rgba(251, 110, 103, 0.19);
}

.image.plan {
  width: 98px;
  height: 98px;
  min-width: 98px;
  margin-bottom: 27px;
  border-radius: 27px;
}

.image.plan-feature-icon {
  width: 32px;
  height: 32px;
  min-width: 32px;
  margin-right: 14px;
  border-radius: 1000px;
  box-shadow: 0 5px 10px 0 rgba(251, 110, 103, 0.19);
}

.image.card-get-plan-icon {
  width: 94px;
  height: 94px;
  min-width: 94px;
  margin-bottom: 32px;
  border-radius: 27px;
}

.image.contact {
  min-width: 571px;
}

.image.contact-link-icon {
  width: 36px;
  height: 36px;
  min-width: 36px;
  margin-right: 13px;
  border-radius: 1000px;
}

.image.styleguide-icon {
  width: 80px;
  height: 80px;
  min-width: 80px;
  border-radius: 24px;
}

.image._404 {
  margin-bottom: 20px;
}

.image.cart-item-image {
  width: auto;
  height: auto;
}

.image.careers-hero-1 {
  width: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}

.image.card-careers-perk-icon {
  width: 72px;
  min-height: 72px;
  min-width: 72px;
  margin-right: 25px;
  border-radius: 22px;
}

.image.card-careers-team {
  width: 100%;
  max-width: 304px;
  margin-right: 30px;
}

.image.cta {
  max-width: 38%;
  min-width: 364px;
  margin-top: -143px;
  margin-bottom: -184px;
}

.order-item-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: 16px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.order-item-content {
  margin-right: 0px;
  margin-left: 0px;
}

.order-item-price {
  color: #201e62;
  font-weight: 500;
}

.apple-pay {
  height: 63px;
  border-radius: 1000px;
}

.checkout-line-item {
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.order-summary-subtotal {
  color: #201e62;
  font-weight: 500;
}

.order-summary-total {
  color: #201e62;
  font-size: 20px;
}

.discounts {
  width: 100%;
  padding-right: 0px;
  padding-bottom: 0px;
  padding-left: 0px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  border-width: 0px;
}

.paypal {
  margin-bottom: 10px;
}

.checkout-hero-wrapper {
  position: relative;
  z-index: 1;
  max-width: 630px;
  margin-right: auto;
  margin-left: auto;
  color: #fff;
  text-align: center;
}

.header-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.cart-button {
  position: relative;
  margin-right: 22px;
  padding: 0px;
  background-color: transparent;
  color: #201e62;
}

.cart-button.alternative {
  color: #fff;
}

.cart-button.alternative:hover {
  color: #fb6e67;
}

.cart-quantity {
  position: absolute;
  right: -7px;
  bottom: -5px;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-left: 0px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 1000px;
  background-color: #fb6e67;
  color: #fff;
  font-size: 12px;
  line-height: 1.167em;
  font-weight: 500;
  letter-spacing: -0.02em;
}

.cart-container {
  max-width: 500px;
}

.bg-primary-3 {
  background-color: #ffb167;
}

.link-white {
  color: #fff;
}

.brand {
  margin-right: 31px;
  padding-left: 0px;
  -webkit-box-ordinal-group: 0;
  -webkit-order: -1;
  -ms-flex-order: -1;
  order: -1;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  -webkit-transition-property: -webkit-transform;
  transition-property: -webkit-transform;
  transition-property: transform;
  transition-property: transform, -webkit-transform;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.brand:hover {
  -webkit-transform: scale3d(1.05, 1.05, 1.01);
  transform: scale3d(1.05, 1.05, 1.01);
}

.home-hero-wrapper {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

._2-buttons.cta-1 {
  position: relative;
  z-index: 1;
}

._2-buttons.cta-2 {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 20px;
}

._2-buttons.home-hero {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.subtitle {
  margin-bottom: 12px;
  color: #fb6e67;
  line-height: 1.111em;
  font-weight: 500;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.content-top {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.content-top.home-services-content-top {
  position: relative;
  z-index: 1;
  margin-bottom: 33px;
}

.content-top.home-features {
  position: relative;
  z-index: 2;
  margin-bottom: 96px;
}

.content-top.about-team {
  position: relative;
  z-index: 1;
  margin-bottom: 48px;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
}

.content-top.blog {
  margin-bottom: 48px;
}

.content-top.blog-post-articles {
  position: relative;
  z-index: 1;
  margin-bottom: 28px;
}

.content-top.about-author {
  margin-bottom: 20px;
  padding-bottom: 18px;
  border-bottom: 1.5px solid #f2f1f6;
}

.content-top.more-doctors {
  position: relative;
  z-index: 1;
  margin-bottom: 43px;
}

.content-top.services {
  position: relative;
  z-index: 1;
  margin-bottom: 48px;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
}

.content-top.blog-category {
  margin-bottom: 18px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.flex-vc {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.flex-vc.home-services {
  position: relative;
  z-index: 1;
}

.flex-vc.home-features {
  position: relative;
  z-index: 2;
}

.home-mission-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.cta-1-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  padding: 78px 40px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 64px;
  background-color: #fff1f0;
  text-align: center;
}

.cta-2-wrapper {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  padding: 77px 64px 65px 48px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 28px;
  background-color: #fff1f0;
}

.container-small-596px {
  max-width: 596px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-small-596px.home-blog {
  position: relative;
  z-index: 1;
  margin-bottom: 35px;
  text-align: center;
}

.home-services-slider {
  z-index: 1;
  height: 100%;
  margin-bottom: 57px;
  background-color: transparent;
}

.testimonials-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.testimonials-title-wrapper {
  min-width: 480px;
  margin-top: 22px;
  margin-bottom: 102px;
}

.card-testimonial-about-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-left: -85px;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.card-testimonial-about-name {
  margin-bottom: 8px;
  color: #201e62;
  font-size: 16px;
  line-height: 1.125em;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.card-testimonial-about-since {
  color: #8f8fa3;
  line-height: 1.111em;
}

.home-services-mask {
  overflow: visible;
  max-width: 404px;
}

.slide-nav {
  display: none;
}

.home-features-grid {
  grid-row-gap: 20px;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.home-feature-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  color: #201e62;
  font-size: 20px;
  line-height: 1.2em;
}

.home-services-slide {
  margin-right: 28px;
}

.card-service-title-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-flex-wrap: wrap-reverse;
  -ms-flex-wrap: wrap-reverse;
  flex-wrap: wrap-reverse;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.card-service-number {
  color: #fb6e67;
  font-size: 24px;
  line-height: 1.125em;
  font-weight: 700;
}

.slider-right-arrow {
  top: -115px;
  bottom: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 72px;
  height: 72px;
  min-width: 72px;
  padding-left: 4px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 1000px;
  background-color: #fff;
  box-shadow: 0 4px 14px 0 rgba(24, 20, 67, 0.08);
  -webkit-transition: color 350ms ease, box-shadow 350ms ease, background-color 350ms ease, -webkit-transform 350ms ease;
  transition: color 350ms ease, box-shadow 350ms ease, background-color 350ms ease, -webkit-transform 350ms ease;
  transition: transform 350ms ease, color 350ms ease, box-shadow 350ms ease, background-color 350ms ease;
  transition: transform 350ms ease, color 350ms ease, box-shadow 350ms ease, background-color 350ms ease, -webkit-transform 350ms ease;
  font-family: 'Icons Hospital Template', sans-serif;
  color: #201e62;
  font-size: 26px;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.slider-right-arrow:hover {
  background-color: #fb6e67;
  box-shadow: 0 4px 24px 0 rgba(251, 110, 103, 0.37);
  -webkit-transform: scale3d(1.1, 1.1, 1.01);
  transform: scale3d(1.1, 1.1, 1.01);
  color: #fff;
}

.slider-left-arrow {
  left: auto;
  top: -115px;
  right: 98px;
  bottom: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 72px;
  height: 72px;
  min-width: 72px;
  padding-right: 4px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 1000px;
  background-color: #fff;
  box-shadow: 0 4px 14px 0 rgba(24, 20, 67, 0.08);
  -webkit-transition: color 350ms ease, box-shadow 350ms ease, background-color 350ms ease, -webkit-transform 350ms ease;
  transition: color 350ms ease, box-shadow 350ms ease, background-color 350ms ease, -webkit-transform 350ms ease;
  transition: transform 350ms ease, color 350ms ease, box-shadow 350ms ease, background-color 350ms ease;
  transition: transform 350ms ease, color 350ms ease, box-shadow 350ms ease, background-color 350ms ease, -webkit-transform 350ms ease;
  font-family: 'Icons Hospital Template', sans-serif;
  color: #201e62;
  font-size: 26px;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.slider-left-arrow:hover {
  background-color: #fb6e67;
  box-shadow: 0 4px 24px 0 rgba(251, 110, 103, 0.37);
  -webkit-transform: scale3d(1.1, 1.1, 1.01);
  transform: scale3d(1.1, 1.1, 1.01);
  color: #fff;
}

.bg {
  position: absolute;
}

.bg.home-hero {
  top: 0px;
  right: 0px;
  bottom: 13px;
  width: 50%;
  border-bottom-left-radius: 230px;
  background-color: #fcdfd7;
}

.bg.header-home-hero-wrapper-bg {
  top: 0px;
  right: 0px;
  bottom: 0px;
  width: 50%;
  background-color: #fcdfd7;
}

.bg.home-features {
  left: 0px;
  right: 0px;
  bottom: 0px;
  height: 621px;
  background-color: #fafafd;
}

.bg.about-hero {
  left: 0px;
  right: 0px;
  bottom: 0px;
  z-index: 1;
  height: 418px;
  border-top-right-radius: 132px;
  background-color: #4b80fb;
}

.bg.about-hero-outside {
  left: 0px;
  bottom: 0px;
  width: 50%;
  height: 418px;
  background-color: #fff;
}

.bg.team-page {
  left: 0px;
  right: 0px;
  bottom: 0px;
  height: 1077px;
  background-color: #fafafd;
}

.bg.contact {
  top: 0px;
  right: 0px;
  width: 46%;
  height: 540px;
  border-bottom-left-radius: 200px;
  background-color: #fb6e67;
}

.bg.header-contact-wrapper-bg {
  top: 0px;
  right: 0px;
  bottom: 0px;
  width: 46%;
  background-color: transparent;
}

.header-home-hero-wrapper {
  position: relative;
}

.section-blog-grid {
  position: relative;
  z-index: 1;
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  grid-column-gap: 37px;
  grid-row-gap: 48px;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.article-item-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100%;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  color: #73729c;
  text-decoration: none;
}

.article-item-wrapper:hover {
  color: #73729c;
}

.card-article-item-about-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.card-article-item-date {
  line-height: 1.111em;
}

.badge {
  padding: 12px 24px;
  border-radius: 1000px;
  background-color: #fb6e67;
  color: #fff;
  font-size: 16px;
  line-height: 1.25em;
  font-weight: 700;
  letter-spacing: -0.02em;
}

.badge.card-blog-post-hero {
  margin-bottom: 16px;
  -webkit-align-self: flex-start;
  -ms-flex-item-align: start;
  align-self: flex-start;
  -webkit-transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease, -webkit-transform 350ms ease;
  text-decoration: none;
}

.badge.card-blog-post-hero:hover {
  box-shadow: 0 9px 14px 0 rgba(239, 113, 107, 0.44);
  -webkit-transform: scale(1.03);
  -ms-transform: scale(1.03);
  transform: scale(1.03);
  color: #fff;
}

.footer-bottom-wrapper {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-top: 27px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-flex-wrap: wrap-reverse;
  -ms-flex-wrap: wrap-reverse;
  flex-wrap: wrap-reverse;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-top: 1px solid #d9d9e8;
}

.footer-main-content-wrapper {
  max-width: 392px;
}

.small-print {
  margin-right: 40px;
  margin-bottom: 20px;
  line-height: 1.5em;
}

.footer-social-media-grid {
  margin-bottom: 20px;
  grid-auto-columns: auto;
  grid-column-gap: 14px;
  grid-row-gap: 14px;
  -ms-grid-columns: auto auto auto auto auto auto auto;
  grid-template-columns: auto auto auto auto auto auto auto;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.footer-social-media-link {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  width: 32px;
  height: 32px;
  min-width: 32px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 1000px;
  background-color: #4b80fb;
  -webkit-transition: background-color 350ms ease;
  transition: background-color 350ms ease;
  font-family: 'Icons Hospital Template', sans-serif;
  color: #fff;
  font-size: 16px;
  text-decoration: none;
}

.footer-social-media-link:hover {
  background-color: #fb6e67;
  color: #fff;
}

.footer-social-media-link.icon-12px {
  font-size: 12px;
}

.footer-social-media-link.icon-14px {
  font-size: 14px;
}

.footer-social-media-link.icon-17px {
  font-size: 17px;
}

.footer-nav-content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  grid-auto-columns: 1fr;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto auto;
  grid-template-rows: auto auto;
}

.footer-nav-box {
  margin-right: 20px;
}

.footer-nav-box.last {
  margin-right: 0px;
}

.footer-nav-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  max-width: 790px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.footer-nav-link {
  display: inline-block;
  -webkit-transition: color 350ms ease, -webkit-transform 350ms ease;
  transition: color 350ms ease, -webkit-transform 350ms ease;
  transition: transform 350ms ease, color 350ms ease;
  transition: transform 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
  color: #73729c;
  line-height: 1.5em;
  text-decoration: none;
  white-space: nowrap;
}

.footer-nav-link:hover {
  -webkit-transform: translate(6px, 0px);
  -ms-transform: translate(6px, 0px);
  transform: translate(6px, 0px);
}

.footer-nav-link.w--current {
  color: #fb6e67;
  font-weight: 700;
}

.footer-nav-link.contact {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.footer-nav-link.contact:hover {
  -webkit-transform: translate3d(6px, 0px, 0.01px);
  transform: translate3d(6px, 0px, 0.01px);
}

.footer-nav-link.contact.address {
  max-width: 269px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  white-space: normal;
}

.footer-nav-link.contact.address:hover {
  background-color: transparent;
  -webkit-transform: none;
  -ms-transform: none;
  transform: none;
  color: #625d7e;
}

.footer-nav-links {
  margin-right: 23px;
  margin-bottom: 0px;
  padding-left: 0px;
  list-style-type: none;
}

.footer-nav-links.last {
  margin-right: 0px;
}

.footer-nav-link-item {
  margin-bottom: 20px;
}

.shape {
  position: absolute;
}

.shape.home-hero {
  left: -244px;
  width: 51%;
}

.shape.home-services-1 {
  left: -519px;
  top: -148px;
}

.shape.home-services-2 {
  top: 29px;
  right: -502px;
}

.shape.home-services-3 {
  top: -135px;
  right: -322px;
}

.shape.home-features-1 {
  left: -365px;
  top: 0px;
}

.shape.home-features-2 {
  right: -447px;
  bottom: -234px;
  z-index: 1;
}

.shape.home-mission {
  right: -484px;
}

.shape.cta-1 {
  left: -175px;
  top: -34px;
  width: 39%;
}

.shape.cta-2 {
  top: -318px;
  right: 395px;
}

.shape.cta-3 {
  top: -79px;
  right: -24px;
  width: 27%;
}

.shape.testimonial-1 {
  left: -216px;
  top: -151px;
}

.shape.testimonial-2 {
  left: 230px;
  top: 84px;
  width: 71%;
}

.shape.testimonial-3 {
  right: -294px;
  bottom: -222px;
}

.shape.home-blog-1 {
  left: -309px;
  top: -330px;
}

.shape.home-blog-2 {
  bottom: -375.7344px;
}

.shape.home-blog-3 {
  right: -215px;
  bottom: -167.7344px;
}

.shape._2-cta-1 {
  left: -119px;
  top: -146px;
}

.shape._2-cta-2 {
  left: 480px;
  bottom: -178.5px;
}

.shape._2-cta-3 {
  top: -100.5px;
  right: 101px;
}

.shape.footer-1 {
  left: -294px;
  top: 49px;
}

.shape.footer-2 {
  top: 7px;
  right: -215px;
}

.shape.about-hero-1 {
  left: -377.5px;
  top: -313px;
}

.shape.about-hero-2 {
  top: -559px;
  right: -429px;
}

.shape.story {
  left: -247px;
  top: -101.109px;
}

.shape.mission {
  top: -68.016px;
  right: -272px;
}

.shape.values-1 {
  left: -261px;
  bottom: -166px;
  width: 43%;
}

.shape.values-2 {
  left: 327px;
  bottom: 73px;
}

.shape.values-3 {
  top: -83px;
  right: -213px;
  width: 31%;
}

.shape.about-team-1 {
  left: -364px;
  bottom: -216px;
}

.shape.about-team-2 {
  top: -85px;
  right: -239px;
}

.shape.blog-hero-1 {
  left: -277px;
  top: -55px;
}

.shape.blog-hero-2 {
  right: -356px;
  bottom: -232px;
}

.shape.blog-post-articles-1 {
  left: -161px;
  bottom: -84px;
}

.shape.blog-post-articles-2 {
  top: -157px;
  right: -303px;
}

.shape.team-members-1 {
  left: -365px;
  top: -326px;
}

.shape.team-members-2 {
  top: -150px;
  right: -175px;
}

.shape.team-members-3 {
  right: -182px;
  bottom: -198px;
}

.shape.team-page-1 {
  left: -172px;
  top: 172px;
}

.shape.team-page-2 {
  top: -78px;
  right: -277px;
}

.shape.more-doctors {
  left: -281px;
  top: -169px;
}

.shape.services-1 {
  left: -170px;
  bottom: -152px;
}

.shape.services-2 {
  top: -63px;
  right: -307px;
}

.shape.packages-1 {
  left: -306px;
  top: -228px;
}

.shape.packages-2 {
  right: -119px;
  bottom: 103px;
}

.shape.faqs {
  top: -101px;
  right: -296px;
}

.shape.contact-1 {
  left: -438px;
  top: -44px;
}

.shape.contact-2 {
  right: -177px;
  bottom: -190px;
}

.shape.checkout-1 {
  left: -248px;
  bottom: -252px;
}

.shape.checkout-2 {
  left: 322px;
  top: -296px;
}

.shape.checkout-3 {
  right: 0px;
  bottom: -208px;
}

.shape.password-1 {
  top: 25px;
  right: 138px;
}

.shape.password-2 {
  left: 27px;
  bottom: -6px;
}

.shape.not-found-1 {
  left: -205px;
  top: 55px;
}

.shape.not-found-2 {
  right: -19px;
  bottom: 61px;
}

.shape.blog-newsletter-1 {
  left: -119px;
  top: -146px;
}

.shape.blog-newsletter-2 {
  left: 480px;
  bottom: -178.5px;
}

.shape.blog-newsletter-3 {
  top: -100.5px;
  right: 101px;
}

.shape.blog-post-1 {
  left: -303px;
  top: -78px;
}

.shape.blog-post-2 {
  top: -125.1719px;
  right: -267px;
}

.home-services-wrapper {
  position: relative;
}

.home-features-wrapper {
  position: relative;
}

.home-blog-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.footer-wrapper {
  position: relative;
}

.container-medium-926px {
  max-width: 926px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-medium-926px.about-hero {
  position: relative;
  z-index: 2;
  margin-bottom: 63px;
  text-align: center;
}

.about-hero-image-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
}

.story-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.values-title-wrapper {
  position: relative;
  z-index: 1;
  max-width: 447px;
  margin-bottom: 44px;
}

.values-grid {
  position: relative;
  z-index: 1;
  grid-column-gap: 28px;
  grid-row-gap: 32px;
}

.about-team-grid {
  position: relative;
  z-index: 1;
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  grid-column-gap: 28px;
  grid-row-gap: 44px;
  -ms-grid-columns: 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.card-team-content {
  padding: 24px 25px 42px;
}

.card-team-rol {
  margin-bottom: 9px;
  color: #fb6e67;
  font-size: 14px;
  line-height: 1.688em;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.mission-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.values-wrapper {
  position: relative;
}

.about-team-wrapper {
  position: relative;
}

.blog-hero-title-wrapper {
  position: relative;
  z-index: 1;
  margin-bottom: 50px;
  text-align: center;
}

.article-featured-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  color: #73729c;
  text-decoration: none;
}

.article-featured-wrapper:hover {
  color: #73729c;
}

.card-article-featured-about-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.blog-grid {
  position: relative;
  z-index: 1;
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  grid-column-gap: 37px;
  grid-row-gap: 48px;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.card-article-featured-date {
  line-height: 1.111em;
}

.blog-categories-grid {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  grid-auto-columns: 1fr;
  -ms-grid-columns: auto auto auto;
  grid-template-columns: auto auto auto;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.blog-categories-grid.blog-category {
  margin-bottom: 30px;
}

.blog-category-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.pagination-button {
  margin-top: 80px;
  padding: 22px 40px;
  border-radius: 1000px;
  background-color: #fff;
  box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.04), 0 6px 23px 0 rgba(32, 30, 98, 0.07);
  -webkit-transition: color 300ms ease, background-color 300ms ease;
  transition: color 300ms ease, background-color 300ms ease;
  color: #201e62;
  font-size: 17px;
  line-height: 1.176em;
  text-align: center;
}

.pagination-button:hover {
  background-color: #fb6e67;
  color: #fff;
}

.blog-hero-wrapper {
  position: relative;
}

.container-medium-992px {
  max-width: 992px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-medium-992px.blog-post {
  position: relative;
  z-index: 1;
}

.blog-post-hero-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  margin-bottom: 78px;
  -webkit-box-pack: end;
  -webkit-justify-content: flex-end;
  -ms-flex-pack: end;
  justify-content: flex-end;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.card-blog-post-hero-date {
  color: #201e62;
  line-height: 1.333em;
  font-weight: 700;
}

.rich-text h2 {
  max-width: 740px;
  margin-right: auto;
  margin-bottom: 18px;
  margin-left: auto;
}

.rich-text p {
  max-width: 740px;
  margin-right: auto;
  margin-bottom: 24px;
  margin-left: auto;
}

.rich-text ul {
  max-width: 740px;
  margin: 24px auto 56px;
}

.rich-text h3 {
  max-width: 740px;
  margin: 32px auto 16px;
}

.rich-text h4 {
  max-width: 740px;
  margin-top: 32px;
  margin-right: auto;
  margin-left: auto;
}

.rich-text ol {
  max-width: 740px;
  margin: 24px auto 56px;
}

.rich-text blockquote {
  max-width: 740px;
  margin: 64px auto 80px;
}

.rich-text h5 {
  max-width: 740px;
  margin-top: 32px;
  margin-right: auto;
  margin-left: auto;
}

.rich-text h6 {
  max-width: 740px;
  margin-top: 32px;
  margin-right: auto;
  margin-left: auto;
}

.rich-text img {
  border-radius: 32px;
}

.rich-text figure {
  margin-top: 40px;
  margin-bottom: 48px;
}

.rich-text.team-about {
  position: relative;
  z-index: 1;
}

.about-author-contact-grid {
  grid-column-gap: 10px;
  grid-row-gap: 10px;
  -ms-grid-columns: auto auto;
  grid-template-columns: auto auto;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.about-author-rol {
  font-size: 16px;
  line-height: 1.688em;
  letter-spacing: 0.07em;
  text-transform: uppercase;
}

.about-author-name-link-wrapper {
  text-decoration: none;
}

.about-author-name-link-wrapper:hover {
  color: #4b80fb;
}

.blog-post-articles-wrapper {
  position: relative;
}

.about-author-contact-link {
  overflow: hidden;
  width: 41px;
  height: 41px;
  min-width: 41px;
  border-radius: 1000px;
  box-shadow: 0 3px 14px 0 rgba(251, 110, 103, 0.21);
  -webkit-transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease, -webkit-transform 350ms ease;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.about-author-contact-link:hover {
  box-shadow: 0 10px 13px 0 rgba(251, 110, 103, 0.38);
  -webkit-transform: translate3d(0px, -8px, 0.01px);
  transform: translate3d(0px, -8px, 0.01px);
}

.container-medium-806px {
  max-width: 806px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-medium-806px.team-members {
  margin-bottom: 41px;
  text-align: center;
}

.team-grid {
  position: relative;
  z-index: 1;
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  grid-column-gap: 28px;
  grid-row-gap: 44px;
  -ms-grid-columns: 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.team-members-wrapper {
  position: relative;
}

.container-medium-975px {
  max-width: 975px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-medium-975px.team-page {
  position: relative;
  z-index: 1;
}

.card-team-page-rol {
  margin-bottom: 14px;
  color: #fb6e67;
  font-size: 21px;
  line-height: 1.286em;
  font-weight: 500;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.card-team-page-contact-grid {
  -webkit-box-pack: start;
  -webkit-justify-content: start;
  -ms-flex-pack: start;
  justify-content: start;
  grid-column-gap: 11px;
  grid-row-gap: 11px;
  grid-template-areas: "Area Area-2";
  -ms-grid-columns: auto;
  grid-template-columns: auto;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.card-team-page-contact-link {
  width: 44px;
  height: 44px;
  min-width: 44px;
  border-radius: 1000px;
  box-shadow: 0 2px 8px 0 rgba(251, 110, 103, 0.17);
  -webkit-transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, -webkit-transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease;
  transition: box-shadow 350ms ease, transform 350ms ease, -webkit-transform 350ms ease;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.card-team-page-contact-link:hover {
  box-shadow: 0 7px 8px 0 rgba(251, 110, 103, 0.33);
  -webkit-transform: translate3d(0px, -8px, 0.01px);
  transform: translate3d(0px, -8px, 0.01px);
}

.team-page-wrapper {
  position: relative;
}

.more-doctors-wrapper {
  position: relative;
}

.services-grid {
  position: relative;
  z-index: 1;
  grid-column-gap: 28px;
  grid-row-gap: 24px;
  grid-template-columns: repeat(auto-fit, 404px);
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.services-wrapper {
  position: relative;
}

.card-service-page-title-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-flex-wrap: wrap-reverse;
  -ms-flex-wrap: wrap-reverse;
  flex-wrap: wrap-reverse;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.card-service-page-number {
  color: #4b80fb;
  font-size: 24px;
  line-height: 1.125em;
  font-weight: 700;
}

.container-medium-692px {
  max-width: 692px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-medium-692px.packages {
  position: relative;
  z-index: 1;
  margin-bottom: 40px;
  text-align: center;
}

.container-medium-692px.plans-category {
  position: relative;
  z-index: 1;
  margin-bottom: 40px;
  text-align: center;
}

.packages-grid {
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  -ms-grid-columns: auto auto auto;
  grid-template-columns: auto auto auto;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.package-grid-item {
  padding-right: 40px;
  padding-left: 40px;
  border-right: 1.5px solid #f2f1f6;
  border-left: 1.5px solid #f2f1f6;
}

.package-grid-item:first-child {
  padding-left: 0px;
  border-right-width: 0px;
  border-left-width: 0px;
}

.package-grid-item:last-child {
  padding-right: 0px;
  border-right-width: 0px;
  border-left-width: 0px;
}

.package-item-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100%;
  max-width: 343px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}

.package-item-features-grid {
  margin-bottom: 63px;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.package-item-feature-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  color: #201e62;
}

.package-item-price {
  margin-bottom: 6px;
  color: #201e62;
  font-size: 30px;
  line-height: 1.067em;
  font-weight: 700;
}

.package-item-appointments-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 26px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.faqs-title-wrapper {
  position: relative;
  z-index: 1;
  margin-bottom: 40px;
  text-align: center;
}

.faqs-grid {
  position: relative;
  z-index: 1;
  grid-column-gap: 30px;
  grid-row-gap: 24px;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.faq-content-top {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.faq-icon-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 50px;
  height: 50px;
  min-width: 50px;
  margin-right: 25px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 1000px;
  background-color: #fff1f0;
}

.space.faq-content {
  height: 14px;
  min-height: 14px;
}

.faq-icon-1 {
  position: absolute;
  width: 19px;
  height: 3px;
  border-radius: 1000px;
  background-color: #fb6e67;
}

.faq-icon-2 {
  position: absolute;
  width: 3px;
  height: 19px;
  border-radius: 1000px;
  background-color: #fb6e67;
}

.card-packages-wrapper {
  position: relative;
}

.faqs-grid-wrapper {
  position: relative;
}

.package-item-main-content-bottom {
  margin-top: auto;
}

.package-item-content-top {
  margin-bottom: 24px;
}

.package-item-content-bottom {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

.plan-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.plan-title-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 16px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.plan-features-grid {
  grid-row-gap: 24px;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.plan-feature-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  color: #201e62;
  font-size: 20px;
  line-height: 1.2em;
}

.card-get-plan-price {
  color: #201e62;
  font-size: 30px;
  line-height: 1.067em;
  font-weight: 700;
}

.select {
  height: 68px;
  margin-bottom: 0px;
  padding-right: 0px;
  padding-left: 0px;
  border: 0px solid #000;
  background-color: transparent;
  -webkit-transition: color 350ms ease;
  transition: color 350ms ease;
  color: #8f8fa3;
  font-size: 18px;
  line-height: 1em;
  letter-spacing: 0.02em;
}

.select:focus {
  color: #373b56;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select::-webkit-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select:-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select::-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select::placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select.checkout {
  height: 54px;
}

.select-wrapper {
  overflow: hidden;
  height: 68px;
  margin-bottom: 0px;
  padding-right: 21px;
  padding-left: 21px;
  border-style: solid;
  border-width: 1px;
  border-color: #d9d9e8;
  border-radius: 50px;
  box-shadow: 0 2px 10px 0 rgba(15, 19, 51, 0.03);
  -webkit-transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease;
  transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease;
}

.select-wrapper:hover {
  border-color: #fb6e67;
}

.select-wrapper:focus {
  border-width: 2px;
  border-color: #fb6e67;
  box-shadow: 0 6px 16px 0 rgba(251, 110, 103, 0.11);
  color: #373b56;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select-wrapper::-webkit-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select-wrapper:-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select-wrapper::-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select-wrapper::placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.select-wrapper.checkout {
  height: 54px;
  margin-bottom: 16px;
}

.card-get-plan-option-list {
  margin-bottom: 16px;
}

.card-get-plan-default-state {
  margin-bottom: 0px;
}

.card-get-plan-title-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 16px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.card-get-plan-content-top {
  margin-bottom: 18px;
}

.contact-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.contact-form-block {
  margin-bottom: 0px;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

.contact-form {
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  grid-column-gap: 22px;
  grid-row-gap: 31px;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.text-area {
  max-height: 230px;
  max-width: 100%;
  min-height: 171px;
  min-width: 100%;
  margin-bottom: 0px;
  padding: 26px 21px;
  border-style: solid;
  border-width: 1px;
  border-color: #d9d9e8;
  border-radius: 12px;
  box-shadow: 0 2px 10px 0 rgba(15, 19, 51, 0.03);
  -webkit-transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease, color 350ms ease;
  transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease, color 350ms ease;
  color: #373b56;
  font-size: 18px;
  line-height: 1em;
  letter-spacing: 0.02em;
}

.text-area:hover {
  border-color: #fb6e67;
}

.text-area:focus {
  border-width: 2px;
  border-color: #fb6e67;
  box-shadow: 0 6px 16px 0 rgba(251, 110, 103, 0.11);
  color: #373b56;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.text-area::-webkit-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.text-area:-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.text-area::-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.text-area::placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.contact-title-wrapper {
  position: relative;
  z-index: 1;
  margin-bottom: 38px;
}

.contact-links-grid {
  margin-top: auto;
  justify-items: start;
  grid-row-gap: 28px;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto auto auto;
  grid-template-rows: auto auto auto;
}

.header-contact-wrapper {
  position: relative;
}

.contact-address-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.contact-link {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-transition: color 350ms ease, -webkit-transform 350ms ease;
  transition: color 350ms ease, -webkit-transform 350ms ease;
  transition: transform 350ms ease, color 350ms ease;
  transition: transform 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
  color: #73729c;
  text-decoration: none;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

.contact-link:hover {
  -webkit-transform: translate3d(6px, 0px, 0.01px);
  transform: translate3d(6px, 0px, 0.01px);
}

.contact-link-text {
  font-size: 24px;
  line-height: 1em;
}

.contact-links-grid-mobile {
  display: none;
  margin-top: auto;
  justify-items: start;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto auto auto;
  grid-template-rows: auto auto auto;
}

.category-title-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.category-title-wrapper.plans-category {
  margin-bottom: 20px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}

.category-title-wrapper.blog-category {
  margin-right: 20px;
  margin-bottom: 30px;
}

.changelog-version {
  margin-bottom: 18px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  font-size: 30px;
}

.rich-text-styleguide h2 {
  max-width: 740px;
  margin-right: auto;
  margin-bottom: 18px;
  margin-left: auto;
}

.rich-text-styleguide p {
  max-width: 740px;
  margin-right: auto;
  margin-bottom: 24px;
  margin-left: auto;
}

.rich-text-styleguide ul {
  max-width: 740px;
  margin: 24px auto 56px;
}

.rich-text-styleguide h3 {
  max-width: 740px;
  margin: 32px auto 16px;
}

.rich-text-styleguide h4 {
  max-width: 740px;
  margin-top: 32px;
  margin-right: auto;
  margin-left: auto;
}

.rich-text-styleguide ol {
  max-width: 740px;
  margin: 24px auto 56px;
}

.rich-text-styleguide blockquote {
  max-width: 740px;
  margin: 64px auto 80px;
}

.rich-text-styleguide h5 {
  max-width: 740px;
  margin-top: 32px;
  margin-right: auto;
  margin-left: auto;
}

.rich-text-styleguide h6 {
  max-width: 740px;
  margin-top: 32px;
  margin-right: auto;
  margin-left: auto;
}

.rich-text-styleguide img {
  border-radius: 32px;
}

.order-item-option-current {
  color: #201e62;
  font-weight: 500;
}

._404-content-wrapper {
  position: relative;
  z-index: 1;
  text-align: center;
}

.dropdown-arrow {
  position: relative;
  top: -3px;
  display: inline-block;
  font-family: 'Icons Hospital Template', sans-serif;
  font-size: 6px;
}

.header-dropdown {
  display: block;
}

.menu-grid-wrapper {
  padding: 45px 38px 35px;
  border-style: solid;
  border-width: 1px;
  border-color: #f2f1f6;
  border-radius: 26px;
  background-color: #fff;
  box-shadow: 0 36px 40px 0 rgba(36, 49, 160, 0.06);
}

.header-dropdown-toggle {
  top: 3px;
  display: block;
  padding: 0px;
  -webkit-transition: color 350ms ease;
  transition: color 350ms ease;
  color: #201e62;
  line-height: 1em;
}

.header-dropdown-toggle:hover {
  color: #fb6e67;
}

.header-dropdown-toggle.w--open {
  color: #fb6e67;
}

.mega-menu-title {
  margin-bottom: 32px;
  font-size: 14px;
  line-height: 1.143em;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.mega-menu-columns {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.mega-menu-column-2 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.menu-grid {
  display: -ms-grid;
  display: grid;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  justify-items: stretch;
  -webkit-box-align: start;
  -webkit-align-items: start;
  -ms-flex-align: start;
  align-items: start;
  grid-auto-flow: column;
  grid-auto-columns: 1fr;
  grid-column-gap: 40px;
  -ms-grid-columns: auto;
  grid-template-columns: auto;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.dropdown-list {
  left: -157px;
  padding-top: 20px;
  background-color: transparent;
}

.mega-menu-column-1 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: 20px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.mega-menu-link {
  margin-bottom: 15px;
  -webkit-transition: color 350ms ease, -webkit-transform 350ms ease;
  transition: color 350ms ease, -webkit-transform 350ms ease;
  transition: transform 350ms ease, color 350ms ease;
  transition: transform 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
  color: #73729c;
  line-height: 1.5em;
  text-decoration: none;
  white-space: nowrap;
}

.mega-menu-link:hover {
  -webkit-transform: translate(6px, 0px);
  -ms-transform: translate(6px, 0px);
  transform: translate(6px, 0px);
}

.mega-menu-link.last {
  margin-bottom: 0px;
}

.cart-item-quantity {
  display: none;
  margin-bottom: 0px;
  border-style: solid;
  border-width: 1px;
  border-color: #d9d9e8;
  border-radius: 50px;
  background-color: #fff;
  box-shadow: 0 2px 10px 0 rgba(15, 19, 51, 0.03);
  -webkit-transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease, color 350ms ease;
  transition: box-shadow 350ms ease, border-width 350ms ease, border-color 350ms ease, color 350ms ease;
  color: #373b56;
  font-size: 18px;
  line-height: 1em;
  letter-spacing: 0.02em;
}

.cart-item-quantity:hover {
  border-color: #fb6e67;
}

.cart-item-quantity:focus {
  border-width: 2px;
  border-color: #fb6e67;
  box-shadow: 0 6px 16px 0 rgba(251, 110, 103, 0.11);
  color: #373b56;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.cart-item-quantity::-webkit-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.cart-item-quantity:-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.cart-item-quantity::-ms-input-placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.cart-item-quantity::placeholder {
  color: #8f8fa3;
  font-size: 18px;
  letter-spacing: 0.02em;
}

.cart-wrapper {
  z-index: 9999;
  background-color: rgba(1, 1, 19, 0.8);
}

.cart-item-content {
  margin-right: 0px;
  margin-left: 0px;
}

.cart-item-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: 16px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.cart-item {
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.cart-item-price {
  color: #201e62;
  font-weight: 500;
}

.remove-button {
  font-size: 16px;
}

.cart-subtotal {
  color: #201e62;
  font-size: 20px;
}

.cart-footer {
  border-top-color: #f2f1f6;
}

.close-button {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.cart-header {
  border-bottom-color: #f2f1f6;
}

.cart-list {
  padding-top: 10px;
  padding-bottom: 10px;
}

.cart-line-item {
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}

.cart-button-icon {
  font-family: 'Icons Hospital Template', sans-serif;
  font-size: 24px;
}

.empty-state {
  position: relative;
  z-index: 1;
  margin-top: 40px;
  margin-bottom: 40px;
  padding: 80px 20px;
  border-style: solid;
  border-width: 1px;
  border-color: #f2f1f6;
  border-radius: 26px;
  background-color: #fff;
  box-shadow: 25px 25px 40px 0 rgba(36, 49, 160, 0.06);
  font-size: 22px;
  font-weight: 500;
  text-align: center;
}

.empty-state.small {
  margin-top: 10px;
  margin-bottom: 10px;
  padding-top: 20px;
  padding-bottom: 20px;
  border-radius: 20px;
  font-size: 18px;
}

.empty-state.plans {
  margin-top: 0px;
  margin-bottom: 0px;
  padding-right: 0px;
  padding-left: 0px;
  border-width: 0px;
  box-shadow: none;
}

.empty-state.cart {
  margin-top: 0px;
  margin-bottom: 0px;
  padding: 10px 60px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
  border-width: 0px;
  border-radius: 0px;
  box-shadow: none;
}

.collection-list-wrapper {
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

.success-message {
  margin-top: 20px;
  margin-bottom: 20px;
  padding: 40px 10px;
  border-radius: 20px;
  background-color: #4b80fb;
  color: #fff;
  font-weight: 500;
}

.success-message.newsletter {
  background-color: #fff;
  color: #201e62;
}

.error-message {
  margin-top: 20px;
  padding: 20px 10px;
  -webkit-align-self: stretch;
  -ms-flex-item-align: stretch;
  -ms-grid-row-align: stretch;
  align-self: stretch;
  border-radius: 20px;
  background-color: #fee2e1;
  color: #fb6e67;
  font-weight: 500;
  text-align: center;
}

.blog-newsletter-wrapper {
  position: relative;
  z-index: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  padding: 77px 64px 65px 48px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 28px;
  background-color: #fff1f0;
}

.blog-newsletter-form-block {
  position: relative;
  z-index: 1;
  width: 100%;
  max-width: 491px;
  margin-bottom: 0px;
}

.blog-newsletter-form {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.loader-main-wrapper {
  position: fixed;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 99999999999;
  display: none;
  overflow: hidden;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #fafafd;
}

.loader {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 60px;
  height: 60px;
  min-width: 60px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 1000px;
  background-color: #fff;
  background-image: -webkit-gradient(linear, left top, left bottom, color-stop(50%, #4b80fb), color-stop(0, #fff));
  background-image: linear-gradient(180deg, #4b80fb 50%, #fff 0);
  box-shadow: 0 -8px 20px 0 rgba(197, 200, 228, 0.4);
}

.loader-hollow {
  width: 40px;
  height: 40px;
  min-width: 40px;
  border-radius: 1000px;
  background-color: #fafafd;
  box-shadow: inset 0 -2px 11px 0 rgba(197, 200, 228, 0.25);
}

.article-featured-item-wrapper {
  position: relative;
  z-index: 1;
}

.header-alternative {
  padding-top: 45px;
  padding-bottom: 45px;
  background-color: transparent;
}

.loader-radius-1 {
  position: absolute;
  left: 0px;
  width: 10px;
  height: 10px;
  min-width: 10px;
  border-radius: 1000px;
  background-color: #4b80fb;
}

.loader-radius-2 {
  position: absolute;
  right: 0px;
  width: 10px;
  height: 10px;
  min-width: 10px;
  border-radius: 1000px;
  background-color: #4b80fb;
}

.grid-licenses {
  margin-top: 32px;
  grid-column-gap: 24px;
  grid-row-gap: 24px;
  -ms-grid-columns: 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.license-image {
  border-radius: 24px;
}

.link-license {
  -webkit-transition: opacity 350ms ease, color 350ms ease;
  transition: opacity 350ms ease, color 350ms ease;
}

.link-license:hover {
  opacity: 0.7;
}

.heading-size-h3 {
  margin-bottom: 20px;
  color: #201e62;
  font-size: 24px;
  line-height: 1.375em;
  font-weight: 700;
}

.image-wrapper-2 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}

.image-wrapper-2.careers-hero-1 {
  position: absolute;
  left: 0px;
  top: 0px;
  max-width: 85%;
  border-radius: 60px;
}

.image-wrapper-2.careers-hero-2 {
  max-width: 41%;
  margin-left: auto;
  border-radius: 40px;
  box-shadow: 0 1px 20px 0 rgba(5, 2, 41, 0.1);
}

.bg-2 {
  position: absolute;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}

.bg-2.careers-hero {
  left: 0%;
  top: auto;
  right: 0%;
  bottom: 0%;
  z-index: -1;
  min-height: 64%;
  background-color: #f9f9fb;
}

.bg-2.cta {
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  width: 100%;
  height: 100%;
  min-height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}

.careers-hero-images-wrapper {
  position: relative;
  margin-bottom: 80px;
  padding-top: 102px;
}

.container-default-2 {
  max-width: 1272px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.card-2 {
  overflow: hidden;
  border-radius: 36px;
  background-color: #fff;
  box-shadow: 0 1px 9px 0 rgba(0, 0, 0, 0.02), 0 2px 6px 0 rgba(0, 0, 0, 0.01), 0 10px 34px 0 rgba(0, 0, 0, 0.03);
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}

.card-2.careers-perk {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding: 48px 36px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  border-style: solid;
  border-width: 1px;
  border-color: #e4e4eb;
}

.card-2.careers-team {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding: 38px 100px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-style: solid;
  border-width: 1px;
  border-color: #e4e4eb;
  border-radius: 24px;
}

.careers-perks-grid {
  grid-column-gap: 24px;
  grid-row-gap: 24px;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.container-medium-874px {
  max-width: 874px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.container-medium-874px.careers-hero {
  margin-bottom: 80px;
  text-align: center;
}

.button-primary-2 {
  padding: 22px 40px;
  border-radius: 14px;
  background-color: #fb6e67;
  -webkit-transition: background-color 300ms ease;
  transition: background-color 300ms ease;
  color: #fff;
  line-height: 1.111em;
  font-weight: 800;
  text-align: center;
}

.button-primary-2:hover {
  background-color: rgba(5, 2, 41, 0.6);
  color: #fff;
}

.paragraph-large-2 {
  font-size: 20px;
  line-height: 1.7em;
}

.paragraph-large-2.careers-hero {
  max-width: 682px;
  margin-right: auto;
  margin-bottom: 46px;
  margin-left: auto;
}

.section-2 {
  padding-top: 180px;
  padding-bottom: 180px;
}

.section-2.careers-hero {
  position: relative;
  padding-top: 88px;
}

.section-2.careers-team {
  padding-top: 140px;
  padding-bottom: 140px;
}

.section-2.cta {
  padding-top: 100px;
  padding-bottom: 100px;
}

.container-large-1112px {
  max-width: 1112px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.card-careers-team-content {
  position: relative;
  bottom: -15px;
  max-width: 456px;
}

.card-careers-team-position {
  font-size: 20px;
  line-height: 1.7em;
}

.container-large-1064px {
  max-width: 1064px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.card-careers-team-name {
  color: #050229;
  font-size: 22px;
  line-height: 1.273em;
  font-weight: 800;
}

.icon {
  overflow: hidden;
}

.notice-bar {
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
}

.container {
  max-width: 1360px;
  padding-right: 40px;
  padding-left: 40px;
}

.notice-bar-content {
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  grid-column-gap: 16px;
  grid-row-gap: 16px;
  -ms-grid-columns: 1fr 3fr 1fr;
  grid-template-columns: 1fr 3fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.close-wrap {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 28px;
  height: 28px;
  padding: 2px;
  border-radius: 50%;
  background-image: linear-gradient(296deg, #4d0eae, #d846a5);
  cursor: pointer;
}

.close-content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 100%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 50%;
  background-color: #060203;
}

.download-app-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.container-default-3 {
  max-width: 1272px;
  margin-right: auto;
  margin-left: auto;
  padding-right: 24px;
  padding-left: 24px;
}

.button-primary-3 {
  padding: 22px 40px;
  border-radius: 14px;
  background-color: #050229;
  -webkit-transition: background-color 300ms ease;
  transition: background-color 300ms ease;
  color: #fff;
  line-height: 1.111em;
  font-weight: 800;
  text-align: center;
}

.button-primary-3:hover {
  background-color: rgba(5, 2, 41, 0.6);
  color: #fff;
}

.button-primary-3.download-app {
  padding: 20px 32px;
  font-size: 16px;
  line-height: 1.375em;
  font-weight: 700;
  text-decoration: none;
}

.button-primary-3.download-app._2-buttons-button {
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #fb6e67;
}

.button-primary-3.download-app._2-buttons-button {
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

._2-buttons-2 {
  margin-bottom: -15px;
}

._2-buttons-2.cta {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.cta-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-height: 483px;
  padding: 60px 88px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.cta-main-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  padding-top: 139px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
  border-radius: 60px;
}

.cta-content {
  max-width: 548px;
  margin-right: 30px;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

.cta-bg-wrapper {
  position: absolute;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: -1;
  overflow: hidden;
  border-radius: 60px;
}

@media screen and (max-width: 991px) {
  h1 {
    font-size: 48px;
  }

  blockquote {
    padding: 52px 62px;
  }

  figcaption {
    margin-top: 20px;
  }

  .styleguide-sidebar {
    display: none;
  }

  .container-default {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .styleguide-content {
    margin-left: 0px;
  }

  .section-styleguide {
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .styleguide-header {
    padding-top: 80px;
    padding-bottom: 80px;
  }

  .typography-container {
    padding-top: 40px;
    padding-bottom: 40px;
  }

  .paragraph-large {
    font-size: 22px;
  }

  .styleguide-subheader {
    padding-top: 34px;
    padding-bottom: 34px;
  }

  .styleguide-content-wrapper {
    padding-top: 80px;
    padding-bottom: 80px;
  }

  .buttons-grid {
    grid-row-gap: 40px;
  }

  .button-primary.footer-store {
    margin-bottom: 0px;
  }

  .button-primary.header-button {
    margin-left: 28px;
  }

  .button-primary.header-button-mobile {
    width: 100%;
    padding-top: 28px;
    padding-bottom: 28px;
    font-size: 20px;
  }

  .button-secondary.blog-category {
    margin-right: 10px;
    margin-left: 10px;
  }

  .cards-grid {
    grid-row-gap: 64px;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .header-logo.alternative {
    display: none;
  }

  .header-logo.alternative-white {
    display: block;
  }

  .header-navigation {
    margin-right: 24px;
    margin-left: 24px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .nav-item-wrapper {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    margin-right: 0px;
    padding-top: 15px;
    padding-bottom: 15px;
  }

  .nav-item-wrapper.mobile {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }

  .nav-item-wrapper.mobile.button {
    margin-top: 80px;
  }

  .nav-link {
    -webkit-transition: color 350ms ease, -webkit-transform 350ms ease;
    transition: color 350ms ease, -webkit-transform 350ms ease;
    transition: transform 350ms ease, color 350ms ease;
    transition: transform 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
    font-size: 28px;
  }

  .nav-link:hover {
    -webkit-transform: translate(6px, 0px);
    -ms-transform: translate(6px, 0px);
    transform: translate(6px, 0px);
  }

  .nav-link.contact {
    font-size: 18px;
  }

  .nav-link.contact:hover {
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
  }

  .nav-link.contact-alternative {
    font-size: 18px;
  }

  .nav-link.contact-alternative:hover {
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
  }

  .menu-button {
    z-index: 999;
    width: 46px;
    height: 46px;
    min-width: 46px;
    margin-left: 20px;
    padding: 12px;
    border-radius: 1000px;
    background-color: #fb6e67;
    box-shadow: 0 10px 18px 0 rgba(239, 113, 107, 0.15);
    -webkit-transition: -webkit-transform 350ms ease;
    transition: -webkit-transform 350ms ease;
    transition: transform 350ms ease;
    transition: transform 350ms ease, -webkit-transform 350ms ease;
    color: #fff;
    font-size: 30px;
  }

  .menu-button:hover {
    background-color: #fb6e67;
    -webkit-transform: scale3d(0.94, 0.94, 1.01);
    transform: scale3d(0.94, 0.94, 1.01);
  }

  .menu-button.w--open {
    background-color: #fb6e67;
  }

  .nav-menu {
    width: 100%;
    padding-top: 132px;
    padding-bottom: 36px;
    background-color: #fafafd;
  }

  .footer {
    padding-top: 70px;
    padding-bottom: 30px;
  }

  .footer-grid {
    margin-bottom: 86px;
    grid-row-gap: 60px;
    -ms-grid-columns: auto;
    grid-template-columns: auto;
  }

  .utility-page-hero {
    padding-top: 70px;
    padding-bottom: 70px;
  }

  .section {
    padding-top: 160px;
    padding-bottom: 160px;
  }

  .section.checkout-hero {
    padding-top: 70px;
    padding-bottom: 70px;
  }

  .section.home-services {
    padding-top: 128px;
  }

  .section.about-hero {
    padding-top: 60px;
  }

  .section.story {
    padding-top: 129px;
    padding-bottom: 142px;
  }

  .section.mission {
    padding-top: 130px;
    padding-bottom: 108px;
  }

  .section.about-team {
    padding-bottom: 128px;
  }

  .section.blog {
    padding-top: 112px;
    padding-bottom: 112px;
  }

  .section.blog-hero {
    padding-top: 60px;
    padding-bottom: 112px;
  }

  .section.blog-post-articles {
    padding-top: 112px;
    padding-bottom: 112px;
  }

  .section.blog-post {
    padding-bottom: 112px;
  }

  .section.team-members {
    padding-top: 60px;
    padding-bottom: 139px;
  }

  .section.more-doctors {
    padding-top: 112px;
    padding-bottom: 112px;
  }

  .section.team-page {
    padding-bottom: 112px;
  }

  .section.services {
    padding-top: 56px;
  }

  .section.packages {
    padding-top: 56px;
    padding-bottom: 80px;
  }

  .section.packages-faqs {
    padding-top: 80px;
    padding-bottom: 144px;
  }

  .section.packages-testimonials {
    padding-top: 112px;
    padding-bottom: 112px;
  }

  .section.plan {
    padding-bottom: 112px;
  }

  .section.contact-faqs {
    padding-top: 112px;
    padding-bottom: 112px;
  }

  .section.contact {
    padding-top: 50px;
    padding-bottom: 142px;
  }

  .section.packages-category {
    padding-top: 56px;
  }

  .section.blog-category {
    padding-top: 56px;
    padding-bottom: 112px;
  }

  .section.utility-page.changelog {
    padding-bottom: 112px;
  }

  .divider.card-service {
    margin-bottom: 20px;
  }

  .divider.card-value {
    margin-top: 15px;
    margin-bottom: 15px;
  }

  .divider.card-service-page {
    margin-bottom: 20px;
  }

  .divider.plan {
    margin-top: 65px;
    margin-bottom: 70px;
  }

  .paragraph.home-hero {
    margin-bottom: 40px;
  }

  .paragraph.card-service {
    margin-bottom: 20px;
  }

  .paragraph.card-team-page {
    margin-bottom: 25px;
  }

  .paragraph.card-service-page {
    margin-bottom: 20px;
  }

  .paragraph.plan-description {
    margin-bottom: 30px;
  }

  .paragraph.card-get-plan {
    margin-bottom: 30px;
  }

  .paragraph.card-careers-team {
    margin-bottom: 20px;
  }

  .card.testimonial {
    max-width: 800px;
    margin-bottom: 40px;
  }

  .card.testimonial.last {
    -webkit-align-self: auto;
    -ms-flex-item-align: auto;
    -ms-grid-row-align: auto;
    align-self: auto;
  }

  .card.value {
    padding-right: 45px;
    padding-left: 45px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card.article-featured {
    position: static;
    max-width: 754px;
    margin-right: 60px;
    margin-left: 60px;
  }

  .card.blog-post-hero {
    position: relative;
    max-width: 90%;
    margin-top: -120px;
    padding-top: 63px;
    padding-bottom: 63px;
    padding-left: 40px;
  }

  .card.team-page {
    margin-bottom: 71px;
    padding: 40px;
  }

  .card.packages {
    padding-top: 61px;
    padding-bottom: 61px;
  }

  .card.get-plan-mobile {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .card.contact {
    margin-bottom: 60px;
    padding-top: 60px;
    padding-bottom: 60px;
  }

  .checkout-form {
    padding-top: 70px;
    padding-bottom: 112px;
  }

  .checkout-block-header {
    padding-right: 60px;
    padding-left: 60px;
  }

  .checkout-block-content {
    padding-right: 60px;
    padding-left: 60px;
  }

  .title.home-features {
    margin-right: auto;
    margin-left: auto;
  }

  .title.cta-2 {
    margin-right: 0px;
    margin-bottom: 40px;
  }

  .title.home-hero {
    max-width: 563px;
    margin-right: auto;
    margin-left: auto;
  }

  .title.home-mission {
    max-width: 548px;
    margin-right: auto;
    margin-left: auto;
  }

  .title.blog {
    margin-bottom: 30px;
  }

  .title.card-blog-post-hero {
    font-size: 34px;
  }

  .title.card-team-page-name {
    font-size: 34px;
  }

  .title.plan {
    font-size: 48px;
  }

  .title.category {
    font-size: 48px;
  }

  .title.blog-newsletter {
    margin-right: 0px;
    margin-bottom: 40px;
  }

  .title.careers-hero {
    margin-bottom: 10px;
  }

  .title.card-careers-perk {
    margin-bottom: 0px;
  }

  .title.careers-perks {
    margin-bottom: 40px;
  }

  .title.careers-team {
    margin-bottom: 50px;
  }

  .title.card-careers-team {
    margin-bottom: 15px;
  }

  .split-content.checkout-left {
    margin-right: 0px;
    margin-bottom: 40px;
  }

  .split-content.checkout-right {
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .split-content.home-hero-left {
    max-width: 754px;
    margin-right: 0px;
    text-align: center;
  }

  .split-content.home-features-left {
    max-width: 754px;
    margin-right: 0px;
    margin-bottom: 40px;
  }

  .split-content.home-mission-right {
    max-width: 754px;
    margin-bottom: 60px;
    text-align: center;
  }

  .split-content.testimonials-left {
    max-width: 100%;
    margin-right: 0px;
    margin-bottom: 40px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .split-content.testimonials-right {
    max-width: 100%;
  }

  .split-content.story-left {
    max-width: 754px;
    margin-right: 0px;
    margin-bottom: 60px;
    text-align: center;
  }

  .split-content.mission-right {
    max-width: 754px;
    margin-bottom: 60px;
    text-align: center;
  }

  .split-content.services-left {
    margin-bottom: 30px;
  }

  .split-content.services-right {
    margin-bottom: 30px;
  }

  .split-content.plan-body {
    max-width: none;
    margin-right: 0px;
  }

  .split-content.plan-sidebar {
    display: none;
  }

  .split-content.contact-left {
    max-width: 100%;
    margin-right: 0px;
  }

  .split-content.contact-right {
    max-width: 100%;
    margin-bottom: 60px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .image-wrapper.card-service {
    margin-bottom: 30px;
  }

  .image-wrapper.article-featured {
    max-width: 100%;
    min-height: auto;
    margin-bottom: -123px;
  }

  .image-wrapper.card-service-page {
    margin-bottom: 30px;
  }

  .image.home-hero {
    width: 538px;
    margin-right: 0px;
    margin-bottom: 60px;
  }

  .image.home-features {
    margin-bottom: 40px;
  }

  .image.home-mission {
    width: auto;
  }

  .image.value {
    margin-bottom: 20px;
  }

  .image.story {
    width: auto;
    margin-right: 0px;
  }

  .image.mission {
    width: auto;
    margin-right: 0px;
    margin-left: 0px;
  }

  .image.blog-post-main-image {
    max-width: 100%;
    min-height: auto;
  }

  .image.card-team-page {
    width: 40%;
    min-width: 40%;
    margin-right: 25px;
    -o-object-fit: cover;
    object-fit: cover;
  }

  .image.plan {
    margin-bottom: 20px;
  }

  .image.card-get-plan-icon {
    margin-bottom: 30px;
  }

  .image.contact {
    max-width: 566px;
    min-width: auto;
  }

  .image.card-careers-perk-icon {
    margin-right: 0px;
    margin-bottom: 20px;
  }

  .image.card-careers-team {
    margin-right: 0px;
    margin-bottom: 40px;
  }

  .image.cta {
    max-width: 364px;
    min-width: auto;
    margin-top: 0px;
    margin-bottom: -308px;
  }

  .cart-button {
    margin-right: 20px;
  }

  .brand {
    z-index: 999;
  }

  .home-hero-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: reverse;
    -webkit-flex-direction: column-reverse;
    -ms-flex-direction: column-reverse;
    flex-direction: column-reverse;
  }

  ._2-buttons.cta-2 {
    margin-bottom: 0px;
  }

  ._2-buttons.home-hero {
    padding-bottom: 25px;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }

  .content-top.home-features {
    margin-bottom: 40px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    text-align: center;
  }

  .content-top.about-team {
    margin-bottom: 40px;
  }

  .content-top.blog {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .content-top.blog-post-articles {
    max-width: 800px;
    margin-right: auto;
    margin-left: auto;
  }

  .content-top.more-doctors {
    margin-bottom: 40px;
  }

  .content-top.services {
    margin-bottom: 10px;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .content-top.blog-category {
    margin-bottom: 40px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .home-mission-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: reverse;
    -webkit-flex-direction: column-reverse;
    -ms-flex-direction: column-reverse;
    flex-direction: column-reverse;
  }

  .cta-1-wrapper {
    padding-top: 68px;
    padding-bottom: 68px;
    border-radius: 54px;
  }

  .cta-2-wrapper {
    padding: 70px 40px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .home-services-slider {
    margin-bottom: 50px;
  }

  .testimonials-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .testimonials-title-wrapper {
    min-width: auto;
    margin-top: 0px;
    margin-bottom: 60px;
    text-align: center;
  }

  .card-testimonial-about-wrapper {
    margin-left: -65px;
  }

  .home-features-grid {
    grid-row-gap: 16px;
  }

  .bg.home-hero {
    bottom: auto;
    width: 100%;
    height: 600px;
  }

  .bg.header-home-hero-wrapper-bg {
    width: 100%;
  }

  .bg.about-hero {
    display: none;
  }

  .bg.about-hero-outside {
    width: 100%;
    height: 38%;
  }

  .bg.contact {
    width: 100%;
    height: 530px;
  }

  .bg.header-contact-wrapper-bg {
    width: 100%;
  }

  .section-blog-grid {
    max-width: 800px;
    margin-right: auto;
    margin-left: auto;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .footer-bottom-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: reverse;
    -webkit-flex-direction: column-reverse;
    -ms-flex-direction: column-reverse;
    flex-direction: column-reverse;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .small-print {
    margin-right: 0px;
    margin-bottom: 0px;
  }

  .footer-nav-wrapper {
    max-width: none;
  }

  .shape.home-mission {
    top: -211px;
  }

  .shape.cta-2 {
    right: 248px;
  }

  .shape.testimonial-1 {
    top: 91px;
  }

  .shape.testimonial-2 {
    left: 498px;
  }

  .shape.testimonial-3 {
    right: -239px;
    bottom: -141px;
  }

  .shape._2-cta-3 {
    top: -187.5px;
    right: 10px;
  }

  .shape.story {
    left: -311px;
  }

  .shape.mission {
    right: -365px;
  }

  .shape.values-1 {
    left: -163px;
    bottom: -154px;
  }

  .shape.values-2 {
    left: 234px;
  }

  .shape.values-3 {
    right: -132px;
  }

  .shape.team-members-1 {
    top: 201px;
  }

  .shape.team-members-3 {
    bottom: -129px;
  }

  .shape.team-page-1 {
    top: 150px;
  }

  .shape.team-page-2 {
    right: -169px;
  }

  .shape.more-doctors {
    left: -197px;
    top: -144px;
  }

  .shape.packages-1 {
    left: -241px;
    top: -157px;
  }

  .shape.packages-2 {
    right: -183px;
  }

  .shape.faqs {
    right: -428px;
  }

  .shape.contact-1 {
    left: -363px;
    top: 30px;
  }

  .shape.contact-2 {
    bottom: -106px;
  }

  .shape.checkout-1 {
    left: -302px;
  }

  .shape.checkout-2 {
    top: -346px;
  }

  .shape.checkout-3 {
    right: -126px;
    bottom: -226px;
  }

  .shape.password-1 {
    right: -83px;
  }

  .shape.password-2 {
    left: -226px;
  }

  .shape.not-found-1 {
    left: -415px;
  }

  .shape.not-found-2 {
    right: -83px;
    bottom: 2px;
  }

  .shape.blog-newsletter-3 {
    top: -187.5px;
    right: 10px;
  }

  .shape.blog-post-1 {
    top: -126px;
  }

  .container-medium-926px.about-hero {
    margin-bottom: 60px;
  }

  .story-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .values-title-wrapper {
    margin-bottom: 40px;
  }

  .about-team-grid {
    grid-column-gap: 20px;
    grid-row-gap: 40px;
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .card-team-content {
    padding-bottom: 40px;
  }

  .mission-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: reverse;
    -webkit-flex-direction: column-reverse;
    -ms-flex-direction: column-reverse;
    flex-direction: column-reverse;
  }

  .blog-hero-title-wrapper {
    margin-bottom: 40px;
  }

  .article-featured-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .blog-grid {
    max-width: 800px;
    margin-right: auto;
    margin-left: auto;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .blog-categories-grid.blog-category {
    margin-bottom: 0px;
  }

  .blog-post-hero-wrapper {
    margin-bottom: 70px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: reverse;
    -webkit-flex-direction: column-reverse;
    -ms-flex-direction: column-reverse;
    flex-direction: column-reverse;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .rich-text ul {
    margin-bottom: 45px;
  }

  .rich-text ol {
    margin-bottom: 45px;
  }

  .rich-text blockquote {
    margin-top: 55px;
    margin-bottom: 70px;
  }

  .container-medium-806px.team-members {
    margin-bottom: 40px;
  }

  .team-grid {
    grid-column-gap: 20px;
    grid-row-gap: 40px;
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .card-team-page-rol {
    font-size: 20px;
  }

  .card-team-page-content {
    max-width: 57%;
  }

  .services-grid {
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .packages-grid {
    -ms-grid-columns: auto;
    grid-template-columns: auto;
  }

  .package-grid-item {
    padding: 40px 0px;
    border-width: 1.5px 0px;
    border-top-style: solid;
    border-top-color: #f2f1f6;
    border-bottom-style: solid;
    border-bottom-color: #f2f1f6;
  }

  .package-grid-item:first-child {
    padding-top: 0px;
    border-top-width: 0px;
    border-bottom-width: 0px;
  }

  .package-grid-item:last-child {
    padding-bottom: 0px;
    border-top-width: 0px;
    border-bottom-width: 0px;
  }

  .package-item-wrapper {
    max-width: 100%;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }

  .package-item-features-grid {
    margin-bottom: 60px;
  }

  .faqs-grid {
    max-width: 800px;
    margin-right: auto;
    margin-left: auto;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .package-item-content-top {
    max-width: 45%;
    margin-right: 40px;
  }

  .plan-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card-get-plan-content-top {
    max-width: 45%;
    margin-right: 40px;
    margin-bottom: 0px;
  }

  .card-get-plan-add-to-cart {
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .contact-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: reverse;
    -webkit-flex-direction: column-reverse;
    -ms-flex-direction: column-reverse;
    flex-direction: column-reverse;
  }

  .contact-title-wrapper {
    max-width: 635px;
    margin-right: auto;
    margin-left: auto;
    text-align: center;
  }

  .contact-links-grid {
    display: none;
  }

  .contact-link-text {
    font-size: 22px;
  }

  .contact-links-grid-mobile {
    position: relative;
    z-index: 1;
    display: -ms-grid;
    display: grid;
    grid-auto-columns: 1fr;
    grid-column-gap: 16px;
    grid-row-gap: 16px;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
    -ms-grid-rows: auto auto auto;
    grid-template-rows: auto auto auto;
  }

  .category-title-wrapper.blog-category {
    margin-right: 0px;
  }

  .changelog-version {
    left: -18px;
  }

  .rich-text-styleguide ul {
    margin-bottom: 45px;
  }

  .rich-text-styleguide ol {
    margin-bottom: 45px;
  }

  .rich-text-styleguide blockquote {
    margin-top: 55px;
    margin-bottom: 70px;
  }

  .dropdown-arrow {
    top: -5px;
    font-size: 9px;
  }

  .header-dropdown {
    margin-right: 0px;
    margin-left: 0px;
  }

  .menu-grid-wrapper {
    padding: 40px 0px 0px;
    border-width: 0px;
    background-color: transparent;
    box-shadow: none;
  }

  .header-dropdown-toggle {
    top: 0px;
    -webkit-transition: color 350ms ease, -webkit-transform 350ms ease;
    transition: color 350ms ease, -webkit-transform 350ms ease;
    transition: transform 350ms ease, color 350ms ease;
    transition: transform 350ms ease, color 350ms ease, -webkit-transform 350ms ease;
    font-size: 28px;
    line-height: 0.75em;
  }

  .header-dropdown-toggle:hover {
    -webkit-transform: translate(6px, 0px);
    -ms-transform: translate(6px, 0px);
    transform: translate(6px, 0px);
  }

  .header-dropdown-toggle.w--open {
    display: inline-block;
  }

  .mega-menu-title {
    margin-bottom: 28px;
  }

  .menu-grid {
    width: 100%;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-pack: start;
    -webkit-justify-content: start;
    -ms-flex-pack: start;
    justify-content: start;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    grid-auto-columns: auto;
    -ms-grid-columns: auto;
    grid-template-columns: auto;
  }

  .dropdown-list.w--open {
    position: static;
    overflow: auto;
    padding-top: 0px;
  }

  .menu-button-icon-wrapper {
    position: absolute;
    left: 0%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .menu-button-icon {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    width: 20px;
    height: 18px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-pack: justify;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .menu-line-top {
    max-height: 2px;
    min-height: 2px;
    padding: 0px;
    grid-auto-columns: 1fr;
    grid-column-gap: 16px;
    grid-row-gap: 16px;
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
    -ms-grid-rows: auto auto;
    grid-template-rows: auto auto;
    background-color: #fff;
  }

  .menu-line-middle {
    max-height: 2px;
    min-height: 2px;
    padding: 0px;
    background-color: #fff;
  }

  .menu-line-bottom {
    max-height: 2px;
    min-height: 2px;
    padding: 0px;
    background-color: #fff;
  }

  .blog-newsletter-wrapper {
    padding: 70px 40px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .blog-newsletter-form-block {
    max-width: 594px;
  }

  .image-wrapper-2.careers-hero-1 {
    border-radius: 40px;
  }

  .image-wrapper-2.careers-hero-2 {
    border-radius: 30px;
  }

  .careers-hero-images-wrapper {
    margin-bottom: 60px;
  }

  .card-2.careers-perk {
    padding-top: 40px;
    padding-bottom: 40px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card-2.careers-team {
    padding-right: 60px;
    padding-bottom: 60px;
    padding-left: 60px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    text-align: center;
  }

  .container-medium-874px.careers-hero {
    margin-bottom: 60px;
  }

  .paragraph-large-2.careers-hero {
    margin-bottom: 40px;
  }

  .section-2 {
    padding-top: 144px;
    padding-bottom: 144px;
  }

  .section-2.careers-hero {
    padding-top: 70px;
  }

  .section-2.careers-team {
    padding-top: 112px;
    padding-bottom: 112px;
  }

  .section-2.cta {
    padding-top: 80px;
    padding-bottom: 80px;
  }

  .card-careers-team-content {
    position: static;
    max-width: 598px;
  }

  .container {
    padding-right: 32px;
    padding-left: 32px;
  }

  ._2-buttons-2.cta {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }

  .cta-wrapper {
    max-height: none;
    padding-top: 100px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    text-align: center;
  }

  .cta-main-wrapper {
    padding-top: 0px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    border-radius: 50px;
  }

  .cta-content {
    margin-right: 0px;
    margin-bottom: 60px;
  }

  .cta-bg-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    border-radius: 50px;
  }
}

@media screen and (max-width: 767px) {
  h1 {
    margin-bottom: 16px;
    font-size: 40px;
  }

  h2 {
    font-size: 32px;
  }

  h3 {
    margin-bottom: 16px;
    font-size: 24px;
  }

  blockquote {
    padding: 43px 40px;
    border-radius: 20px;
    font-size: 22px;
  }

  figcaption {
    margin-top: 15px;
  }

  .styleguide-title {
    font-size: 46px;
    line-height: 52px;
  }

  .styleguide-header {
    padding-right: 32px;
    padding-left: 32px;
  }

  .color-primary-grid {
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .color-secondary-grid {
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .color-neutral-grid {
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .paragraph-large {
    font-size: 20px;
  }

  .styleguide-subheader {
    padding-right: 32px;
    padding-left: 32px;
  }

  .styleguide-content-wrapper {
    padding-right: 32px;
    padding-left: 32px;
  }

  .icons-grid {
    grid-template-columns: repeat(auto-fit, 80px);
  }

  .button-primary._2-buttons {
    margin-right: 20px;
    margin-bottom: 20px;
  }

  .button-primary.header-button {
    display: none;
  }

  .button-primary.header-button-mobile {
    padding-top: 24px;
    padding-bottom: 24px;
  }

  .button-secondary._2-buttons {
    margin-bottom: 20px;
  }

  .button-secondary.blog-category {
    margin-right: 14px;
    margin-left: 0px;
  }

  .header {
    padding-top: 40px;
    padding-bottom: 40px;
  }

  .header-logo {
    width: 180px;
  }

  .nav-item-wrapper.mobile.button {
    margin-top: 60px;
  }

  .nav-link.contact {
    display: none;
  }

  .nav-link.contact-alternative {
    display: none;
  }

  .nav-menu {
    padding-top: 125px;
  }

  .display-1 {
    font-size: 64px;
    line-height: 72px;
  }

  .display-2 {
    font-size: 52px;
    line-height: 58px;
  }

  .display-3 {
    font-size: 26px;
    line-height: 30px;
  }

  .footer-grid {
    margin-bottom: 40px;
    grid-row-gap: 50px;
  }

  .utility-page-hero {
    padding-top: 60px;
    padding-bottom: 60px;
  }

  .section {
    padding-top: 128px;
    padding-bottom: 128px;
  }

  .section.checkout-hero {
    padding-top: 60px;
    padding-bottom: 60px;
  }

  .section.home-services {
    padding-top: 100px;
  }

  .section.home-features {
    padding-top: 40px;
  }

  .section.about-hero {
    padding-top: 48px;
  }

  .section.story {
    padding-top: 103px;
    padding-bottom: 114px;
  }

  .section.mission {
    padding-top: 104px;
    padding-bottom: 86px;
  }

  .section.about-team {
    padding-bottom: 100px;
  }

  .section.blog {
    padding-top: 90px;
    padding-bottom: 90px;
  }

  .section.blog-hero {
    padding-top: 48px;
    padding-bottom: 90px;
  }

  .section.blog-post-articles {
    padding-top: 90px;
    padding-bottom: 90px;
  }

  .section.blog-post {
    padding-top: 40px;
    padding-bottom: 90px;
  }

  .section.team-members {
    padding-top: 48px;
    padding-bottom: 111px;
  }

  .section.more-doctors {
    padding-top: 90px;
    padding-bottom: 90px;
  }

  .section.team-page {
    padding-top: 20px;
    padding-bottom: 90px;
  }

  .section.services {
    padding-top: 45px;
  }

  .section.packages {
    padding-top: 45px;
    padding-bottom: 64px;
  }

  .section.packages-faqs {
    padding-top: 64px;
    padding-bottom: 115px;
  }

  .section.packages-testimonials {
    padding-top: 90px;
    padding-bottom: 90px;
  }

  .section.plan {
    padding-top: 37px;
    padding-bottom: 90px;
  }

  .section.contact-faqs {
    padding-top: 90px;
    padding-bottom: 90px;
  }

  .section.contact {
    padding-top: 40px;
    padding-bottom: 113px;
  }

  .section.packages-category {
    padding-top: 45px;
  }

  .section.blog-category {
    padding-top: 45px;
    padding-bottom: 90px;
  }

  .section.utility-page.changelog {
    padding-bottom: 90px;
  }

  .utility-page-content-password {
    padding-right: 32px;
    padding-left: 32px;
  }

  .container-medium-761px.changelog {
    margin-top: -110px;
  }

  .divider.card-service {
    margin-bottom: 18px;
  }

  .divider.card-article-item {
    margin-top: 20px;
    margin-bottom: 20px;
  }

  .divider.card-value {
    margin-top: 10px;
    margin-bottom: 10px;
  }

  .divider.card-article-featured {
    margin-top: 25px;
  }

  .divider.card-service-page {
    margin-bottom: 18px;
  }

  .divider.plan {
    margin-top: 54px;
    margin-bottom: 58px;
  }

  .paragraph.home-hero {
    margin-bottom: 30px;
  }

  .paragraph.home-mission {
    margin-bottom: 30px;
  }

  .paragraph.footer-main-content {
    margin-bottom: 30px;
  }

  .paragraph.about-hero {
    margin-right: 0px;
    margin-bottom: 30px;
    margin-left: 0px;
    text-align: left;
  }

  .paragraph.card-blog-post-hero {
    margin-bottom: 30px;
  }

  .paragraph.card-team-page {
    margin-bottom: 20px;
  }

  .paragraph.packages {
    margin-left: 0px;
  }

  .paragraph.faq-content {
    margin-left: 71px;
  }

  .paragraph.plan-description {
    margin-bottom: 25px;
  }

  .paragraph.card-get-plan {
    margin-bottom: 25px;
  }

  .paragraph.packages-category {
    margin-left: 0px;
  }

  .card {
    border-radius: 20px;
  }

  .card.changelog {
    margin-bottom: 40px;
    padding: 50px 40px;
  }

  .card.testimonial {
    margin-bottom: 30px;
    padding: 40px;
  }

  .card.service {
    padding-top: 40px;
    padding-bottom: 46px;
  }

  .card.article-item-card {
    margin-right: 20px;
    margin-left: 20px;
  }

  .card.value {
    padding-right: 40px;
    padding-left: 40px;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }

  .card.team {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .card.article-featured {
    margin-right: 20px;
    margin-left: 20px;
    padding-top: 44px;
  }

  .card.blog-post-hero {
    max-width: 95%;
    margin-top: -32px;
    padding: 53px 30px;
  }

  .card.about-author {
    margin-top: 35px;
    padding: 50px 40px 45px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card.team-page {
    max-width: 611px;
    margin-bottom: 60px;
    padding-top: 30px;
    padding-bottom: 30px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .card.service-page {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    padding-top: 40px;
    padding-bottom: 46px;
  }

  .card.packages {
    padding-top: 51px;
    padding-bottom: 51px;
  }

  .card.faq-wrapper.last {
    padding-top: 40px;
    padding-bottom: 40px;
  }

  .card.get-plan-mobile {
    margin-top: 50px;
    padding-top: 40px;
    padding-bottom: 60px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card.contact {
    min-height: 918px;
    margin-bottom: 50px;
    padding: 50px 30px;
  }

  .card.default {
    padding: 50px 30px;
  }

  .checkout-form {
    padding-top: 60px;
    padding-bottom: 90px;
  }

  .checkout-block-header {
    padding-right: 40px;
    padding-left: 40px;
  }

  .checkout-block-content {
    padding-right: 40px;
    padding-left: 40px;
  }

  .title.home-features {
    margin-right: 0px;
    margin-left: 0px;
  }

  .title.cta-1 {
    max-width: 600px;
    margin-bottom: 30px;
  }

  .title.testimonials {
    margin-bottom: 30px;
  }

  .title.cta-2 {
    margin-bottom: 30px;
  }

  .title.footer-nav-title {
    margin-bottom: 30px;
  }

  .title.home-hero {
    margin-right: 0px;
    margin-left: 0px;
  }

  .title.home-mission {
    margin-right: 0px;
    margin-left: 0px;
  }

  .title.card-testimonial {
    margin-bottom: 16px;
  }

  .title.card-blog-post-hero {
    font-size: 32px;
  }

  .title.about-author-name {
    font-size: 22px;
  }

  .title.card-team-page-name {
    font-size: 32px;
  }

  .title.plan {
    font-size: 40px;
  }

  .title.card-get-plan {
    font-size: 22px;
  }

  .title.category {
    font-size: 40px;
  }

  .title.blog-newsletter {
    margin-bottom: 30px;
  }

  .title.careers-perks {
    max-width: 346px;
    margin-right: auto;
    margin-left: auto;
  }

  .title.careers-team {
    max-width: 575px;
    margin-bottom: 40px;
  }

  .title.card-careers-team {
    max-width: 538px;
    margin-right: auto;
    margin-bottom: 10px;
    margin-left: auto;
  }

  .title.neutral-100.cta {
    margin-bottom: 30px;
  }

  .split-content.home-hero-left {
    text-align: left;
  }

  .split-content.home-features-left {
    margin-bottom: 30px;
  }

  .split-content.home-mission-right {
    margin-bottom: 40px;
    text-align: left;
  }

  .split-content.testimonials-left {
    margin-bottom: 30px;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .split-content.story-left {
    max-width: 600px;
    margin-bottom: 40px;
    text-align: left;
  }

  .split-content.about-team-left {
    max-width: 500px;
    margin-bottom: 30px;
  }

  .split-content.mission-right {
    max-width: 600px;
    margin-bottom: 40px;
    text-align: left;
  }

  .split-content.blog-post-articles-left {
    margin-bottom: 20px;
  }

  .split-content.more-doctors-left {
    margin-right: 40px;
    margin-bottom: 30px;
  }

  .split-content.more-doctors-right {
    margin-bottom: 30px;
  }

  .split-content.services-right {
    margin-bottom: 0px;
  }

  .split-content.contact-right {
    margin-bottom: 50px;
  }

  .checkout-row {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .image-wrapper.order-item-image {
    max-width: 67px;
    border-radius: 20px;
  }

  .image-wrapper.card-service {
    margin-bottom: 25px;
  }

  .image-wrapper.article-item-image {
    margin-bottom: -43px;
    border-radius: 20px;
  }

  .image-wrapper.card-team {
    max-width: 38%;
    -webkit-align-self: stretch;
    -ms-flex-item-align: stretch;
    -ms-grid-row-align: stretch;
    align-self: stretch;
  }

  .image-wrapper.article-featured {
    margin-bottom: -58px;
    border-radius: 25px;
  }

  .image-wrapper.about-author {
    width: 121px;
    height: 121px;
    min-width: 121px;
    margin-right: 30px;
    margin-bottom: 20px;
  }

  .image-wrapper.card-service-page {
    margin-right: 25px;
    margin-bottom: 20px;
  }

  .image-wrapper.cart-item-image {
    max-width: 67px;
    border-radius: 20px;
  }

  .image.home-hero {
    width: auto;
    max-width: 500px;
    margin-bottom: 40px;
    -webkit-align-self: center;
    -ms-flex-item-align: center;
    -ms-grid-row-align: center;
    align-self: center;
  }

  .image.card-testimonial-about {
    width: 87px;
    height: 87px;
    min-width: 87px;
  }

  .image.card-testimonial-stars {
    margin-bottom: 0px;
  }

  .image.value {
    width: 77px;
    height: 77px;
    min-width: 77px;
    margin-right: 20px;
    border-radius: 25px;
  }

  .image.card-team {
    height: 100%;
    -o-object-fit: cover;
    object-fit: cover;
  }

  .image.card-team-page {
    width: 275px;
    height: 275px;
    min-width: 275px;
    margin-right: 0px;
    margin-bottom: 30px;
  }

  .image.plan {
    margin-bottom: 15px;
  }

  .image.plan-feature-icon {
    margin-right: 10px;
  }

  .image.card-get-plan-icon {
    width: 78px;
    height: 78px;
    min-width: 78px;
    margin-bottom: 25px;
    border-radius: 20px;
  }

  .image.contact {
    max-width: 572px;
  }

  .image.contact-link-icon {
    width: 30px;
    height: 30px;
    min-width: 30px;
  }

  .image.styleguide-icon {
    border-radius: 20px;
  }

  .image.card-careers-perk-icon {
    margin-right: 20px;
    margin-bottom: 0px;
    border-radius: 20px;
  }

  .image.card-careers-team {
    max-width: 253px;
    margin-bottom: 33px;
  }

  .image.cta {
    margin-bottom: -297px;
  }

  .cart-button {
    margin-right: 10px;
  }

  .home-hero-wrapper {
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  ._2-buttons.cta-2 {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  ._2-buttons.home-hero {
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }

  .subtitle {
    margin-bottom: 10px;
    font-size: 16px;
  }

  .content-top.home-services-content-top {
    margin-bottom: 150px;
  }

  .content-top.home-features {
    margin-bottom: 20px;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    text-align: left;
  }

  .content-top.about-team {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .content-top.blog {
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .content-top.blog-post-articles {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .content-top.about-author {
    margin-bottom: 18px;
  }

  .content-top.more-doctors {
    margin-bottom: 10px;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .content-top.services {
    margin-bottom: 40px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .content-top.blog-category {
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .flex-vc {
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .home-mission-wrapper {
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .cta-1-wrapper {
    padding-top: 57px;
    padding-bottom: 57px;
    border-radius: 30px;
  }

  .cta-2-wrapper {
    padding-top: 60px;
    padding-bottom: 40px;
    border-radius: 20px;
  }

  .container-small-596px.home-blog {
    margin-left: 0px;
    text-align: left;
  }

  .home-services-slider {
    margin-bottom: 40px;
  }

  .testimonials-title-wrapper {
    margin-bottom: 40px;
    text-align: left;
  }

  .card-testimonial-about-wrapper {
    margin-left: 0px;
  }

  .home-services-slide {
    margin-right: 20px;
  }

  .slider-right-arrow {
    left: 80px;
    right: auto;
    width: 56px;
    height: 56px;
    min-width: 56px;
    font-size: 20px;
  }

  .slider-left-arrow {
    left: 0px;
    right: auto;
    width: 56px;
    height: 56px;
    min-width: 56px;
    font-size: 20px;
  }

  .bg.home-hero {
    height: 560px;
    border-bottom-left-radius: 120px;
  }

  .bg.about-hero-outside {
    height: 30%;
  }

  .bg.team-page {
    height: 80%;
  }

  .bg.contact {
    height: 520px;
    border-bottom-left-radius: 150px;
  }

  .bg.header-contact-wrapper-bg {
    width: 100%;
  }

  .section-blog-grid {
    grid-row-gap: 40px;
  }

  .badge.card-blog-post-hero {
    margin-bottom: 10px;
  }

  .footer-nav-box {
    margin-bottom: 40px;
  }

  .footer-nav-wrapper {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .footer-nav-link-item {
    margin-bottom: 15px;
  }

  .shape.home-services-1 {
    left: -406px;
    top: -172px;
  }

  .shape.home-services-2 {
    top: 115px;
    right: -320px;
  }

  .shape.home-features-1 {
    left: auto;
    top: -37px;
    right: -287px;
    width: 76%;
  }

  .shape.home-features-2 {
    left: -356px;
    right: auto;
    bottom: -149px;
  }

  .shape.home-mission {
    top: -118px;
    right: 376px;
    width: 60%;
  }

  .shape.cta-1 {
    left: -164px;
    top: 182px;
    width: auto;
  }

  .shape.cta-2 {
    right: 395px;
  }

  .shape.cta-3 {
    top: -157px;
    right: -140px;
    width: auto;
  }

  .shape.testimonial-1 {
    left: -196px;
    top: 67px;
  }

  .shape.testimonial-2 {
    left: 327px;
    top: 487px;
  }

  .shape.testimonial-3 {
    right: -183px;
    bottom: -120px;
  }

  .shape.home-blog-1 {
    top: -298px;
  }

  .shape.home-blog-2 {
    left: -11.5px;
    bottom: -344.7344px;
  }

  .shape.home-blog-3 {
    bottom: 186.2656px;
  }

  .shape._2-cta-2 {
    left: 288px;
  }

  .shape._2-cta-3 {
    right: -78px;
  }

  .shape.footer-2 {
    top: auto;
    right: -189px;
    bottom: 147px;
  }

  .shape.about-hero-1 {
    left: -425.5px;
    top: -262px;
  }

  .shape.about-hero-2 {
    top: -465px;
    right: -351px;
  }

  .shape.story {
    top: -50.109px;
  }

  .shape.mission {
    right: -379px;
  }

  .shape.values-1 {
    left: -145px;
    bottom: -123px;
  }

  .shape.values-2 {
    left: 47px;
  }

  .shape.values-3 {
    top: -72px;
    right: -75px;
  }

  .shape.blog-hero-1 {
    left: -331px;
    top: -32px;
  }

  .shape.blog-hero-2 {
    right: -301px;
    bottom: -149px;
  }

  .shape.team-members-1 {
    left: -319px;
  }

  .shape.team-members-3 {
    right: -304px;
    bottom: -95px;
  }

  .shape.team-page-1 {
    top: 342px;
  }

  .shape.packages-1 {
    left: -202px;
    top: -107px;
  }

  .shape.faqs {
    top: 59px;
    right: -256px;
  }

  .shape.contact-1 {
    left: -265px;
  }

  .shape.checkout-1 {
    left: -342px;
    bottom: -320px;
  }

  .shape.checkout-2 {
    left: 37px;
  }

  .shape.checkout-3 {
    right: -193px;
    bottom: -239px;
  }

  .shape.password-1 {
    right: -147px;
  }

  .shape.password-2 {
    left: -305px;
  }

  .shape.not-found-1 {
    left: -342px;
  }

  .shape.not-found-2 {
    right: -147px;
  }

  .shape.blog-newsletter-2 {
    left: 288px;
  }

  .shape.blog-newsletter-3 {
    right: -78px;
  }

  .shape.blog-post-1 {
    left: -255px;
    top: -111px;
  }

  .shape.blog-post-2 {
    top: -93.1719px;
  }

  .container-medium-926px.about-hero {
    margin-bottom: 30px;
    text-align: left;
  }

  .story-wrapper {
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .values-grid {
    grid-row-gap: 30px;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .about-team-grid {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .card-team-content {
    padding-top: 40px;
  }

  .mission-wrapper {
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .blog-hero-title-wrapper {
    margin-bottom: 30px;
    text-align: left;
  }

  .blog-grid {
    grid-row-gap: 40px;
  }

  .blog-categories-grid {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .blog-post-hero-wrapper {
    margin-bottom: 60px;
  }

  .rich-text h2 {
    margin-bottom: 16px;
  }

  .rich-text p {
    margin-bottom: 20px;
  }

  .rich-text ul {
    margin-top: 20px;
    margin-bottom: 40px;
    padding-left: 30px;
  }

  .rich-text h3 {
    margin-top: 30px;
  }

  .rich-text h4 {
    margin-top: 30px;
  }

  .rich-text ol {
    margin-top: 20px;
    margin-bottom: 40px;
    padding-left: 30px;
  }

  .rich-text blockquote {
    margin-top: 50px;
    margin-bottom: 60px;
  }

  .rich-text h5 {
    margin-top: 30px;
  }

  .rich-text h6 {
    margin-top: 30px;
  }

  .rich-text img {
    border-radius: 20px;
  }

  .rich-text figure {
    margin-top: 35px;
    margin-bottom: 45px;
  }

  .team-grid {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .card-team-page-rol {
    font-size: 18px;
  }

  .card-team-page-content {
    max-width: 100%;
  }

  .services-grid {
    grid-row-gap: 20px;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .container-medium-692px.packages {
    margin-left: 0px;
    text-align: left;
  }

  .container-medium-692px.plans-category {
    margin-left: 0px;
    text-align: left;
  }

  .package-item-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .package-item-features-grid {
    margin-bottom: 40px;
  }

  .package-item-price {
    font-size: 25px;
  }

  .faqs-title-wrapper {
    text-align: left;
  }

  .faq-icon-wrapper {
    margin-right: 20px;
  }

  .package-item-content-top {
    max-width: 446px;
    margin-right: 0px;
  }

  .plan-features-grid {
    grid-row-gap: 20px;
  }

  .card-get-plan-price {
    font-size: 28px;
  }

  .card-get-plan-content-top {
    max-width: 100%;
    margin-right: 0px;
    margin-bottom: 30px;
  }

  .card-get-plan-add-to-cart {
    width: 100%;
    -webkit-box-flex: 0;
    -webkit-flex: 0 auto;
    -ms-flex: 0 auto;
    flex: 0 auto;
  }

  .contact-form {
    grid-row-gap: 25px;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .contact-title-wrapper {
    margin-bottom: 30px;
    margin-left: 0px;
    text-align: left;
  }

  .contact-link-text {
    font-size: 20px;
    line-height: 32px;
  }

  .contact-links-grid-mobile {
    margin-left: 0px;
  }

  .category-title-wrapper.plans-category {
    margin-bottom: 16px;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }

  .changelog-version {
    position: static;
    width: 87px;
    height: 87px;
    min-width: 87px;
    margin-bottom: 20px;
  }

  .rich-text-styleguide h2 {
    margin-bottom: 16px;
  }

  .rich-text-styleguide p {
    margin-bottom: 20px;
  }

  .rich-text-styleguide ul {
    margin-top: 20px;
    margin-bottom: 40px;
    padding-left: 30px;
  }

  .rich-text-styleguide h3 {
    margin-top: 30px;
  }

  .rich-text-styleguide h4 {
    margin-top: 30px;
  }

  .rich-text-styleguide ol {
    margin-top: 20px;
    margin-bottom: 40px;
    padding-left: 30px;
  }

  .rich-text-styleguide blockquote {
    margin-top: 50px;
    margin-bottom: 60px;
  }

  .rich-text-styleguide h5 {
    margin-top: 30px;
  }

  .rich-text-styleguide h6 {
    margin-top: 30px;
  }

  .rich-text-styleguide img {
    border-radius: 20px;
  }

  .menu-grid-wrapper {
    padding-top: 30px;
  }

  .mega-menu-columns {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .menu-grid {
    grid-column-gap: 40px;
  }

  .empty-state {
    padding-top: 60px;
    padding-bottom: 60px;
    border-radius: 20px;
  }

  .blog-newsletter-wrapper {
    padding-top: 60px;
    padding-bottom: 40px;
    border-radius: 20px;
  }

  .blog-newsletter-form-block {
    max-width: 100%;
  }

  .header-alternative {
    padding-top: 40px;
    padding-bottom: 40px;
  }

  .grid-licenses {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .image-wrapper-2.careers-hero-1 {
    border-radius: 30px;
  }

  .careers-hero-images-wrapper {
    margin-bottom: 50px;
  }

  .card-2 {
    border-radius: 30px;
  }

  .card-2.careers-perk {
    padding-top: 33px;
    padding-bottom: 33px;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }

  .card-2.careers-team {
    padding: 30px 35px 50px;
  }

  .careers-perks-grid {
    max-width: 575px;
    margin-right: auto;
    margin-left: auto;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .container-medium-874px.careers-hero {
    margin-bottom: 50px;
  }

  .paragraph-large-2 {
    font-size: 20px;
    line-height: 32px;
  }

  .paragraph-large-2.careers-hero {
    margin-bottom: 35px;
  }

  .section-2 {
    padding-top: 115px;
    padding-bottom: 115px;
  }

  .section-2.careers-hero {
    padding-top: 56px;
  }

  .section-2.careers-team {
    padding-top: 90px;
    padding-bottom: 90px;
  }

  .section-2.cta {
    padding-top: 64px;
    padding-bottom: 64px;
  }

  .card-careers-team-position {
    font-size: 18px;
  }

  .card-careers-team-name {
    font-size: 20px;
  }

  .container {
    padding-right: 24px;
    padding-left: 24px;
  }

  .notice-bar-content {
    text-align: left;
  }

  .button-primary-3.download-app {
    width: 240.390625px;
    padding: 22px 20px;
  }

  .button-primary-3.download-app._2-buttons-button {
    margin-right: 0px;
  }

  .button-primary-3.download-app._2-buttons-button {
    margin-right: 0px;
  }

  ._2-buttons-2.cta {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .cta-wrapper {
    padding: 0px 25px 50px;
    -webkit-box-pack: end;
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
  }

  .cta-main-wrapper {
    border-radius: 40px;
  }

  .cta-content {
    margin-top: 76px;
    margin-bottom: 50px;
  }

  .cta-bg-wrapper {
    padding-right: 25px;
    padding-left: 25px;
    border-radius: 40px;
  }
}

@media screen and (max-width: 479px) {
  h1 {
    margin-bottom: 10px;
    font-size: 34px;
  }

  h2 {
    margin-bottom: 10px;
    font-size: 28px;
  }

  h3 {
    margin-bottom: 10px;
    font-size: 20px;
  }

  h4 {
    font-size: 18px;
  }

  h5 {
    font-size: 16px;
  }

  h6 {
    font-size: 14px;
  }

  blockquote {
    padding: 36px 20px;
    font-size: 20px;
  }

  figcaption {
    margin-top: 10px;
    font-size: 16px;
  }

  .container-default {
    padding-right: 16px;
    padding-left: 16px;
  }

  .section-styleguide {
    padding-top: 32px;
    padding-bottom: 32px;
  }

  .styleguide-header {
    padding-right: 20px;
    padding-left: 20px;
  }

  .color-primary-grid {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .color-secondary-grid {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .color-neutral-grid {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .styleguide-subheader {
    padding-right: 20px;
    padding-left: 20px;
  }

  .styleguide-content-wrapper {
    padding: 60px 20px;
  }

  .icons-grid {
    grid-template-columns: repeat(auto-fit, 60px);
  }

  .buttons-grid {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .button-primary {
    display: block;
    padding: 24px 16px;
  }

  .button-primary._2-buttons {
    margin-right: 0px;
  }

  .button-primary.footer-store {
    margin-right: 0px;
    margin-bottom: 20px;
    padding-top: 20px;
    padding-bottom: 20px;
  }

  .button-primary.home-hero {
    margin-right: 0px;
  }

  .button-primary.header-button-mobile {
    font-size: 18px;
  }

  .button-primary.blog-newsletter {
    position: static;
    margin-top: 20px;
    padding: 24px 16px;
  }

  .button-secondary {
    display: block;
    padding: 24px 16px;
  }

  .button-secondary._2-buttons {
    margin-bottom: 0px;
  }

  .button-secondary.blog-category {
    margin-right: 16px;
    margin-left: 0px;
  }

  .button-secondary.blog-category.w--current {
    margin-right: 0px;
  }

  .button-secondary.blog-category.all {
    margin-top: 6px;
    margin-right: 14px;
    margin-bottom: 6px;
  }

  .header {
    padding-top: 35px;
    padding-bottom: 35px;
  }

  .header-navigation {
    margin-right: 16px;
    margin-left: 16px;
  }

  .nav-item-wrapper {
    padding-top: 13px;
    padding-bottom: 13px;
  }

  .nav-link {
    font-size: 25px;
  }

  .menu-button {
    padding: 10px;
    font-size: 26px;
  }

  .nav-menu {
    padding-top: 120px;
  }

  .footer-grid {
    grid-row-gap: 40px;
  }

  .utility-page-hero {
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .section {
    padding-top: 100px;
    padding-bottom: 100px;
  }

  .section.home-services {
    position: static;
    padding-top: 82px;
    -o-object-fit: fill;
    object-fit: fill;
  }

  .section.about-hero {
    padding-top: 38px;
  }

  .section.story {
    padding-top: 82px;
    padding-bottom: 91px;
  }

  .section.mission {
    padding-top: 83px;
    padding-bottom: 69px;
  }

  .section.about-team {
    padding-bottom: 82px;
  }

  .section.blog {
    padding-top: 72px;
    padding-bottom: 72px;
  }

  .section.blog-hero {
    padding-top: 38px;
    padding-bottom: 72px;
  }

  .section.blog-post-articles {
    padding-top: 72px;
    padding-bottom: 72px;
  }

  .section.blog-post {
    padding-top: 32px;
    padding-bottom: 72px;
  }

  .section.team-members {
    padding-top: 38px;
    padding-bottom: 89px;
  }

  .section.more-doctors {
    padding-top: 72px;
    padding-bottom: 72px;
  }

  .section.team-page {
    padding-bottom: 72px;
  }

  .section.services {
    padding-top: 36px;
  }

  .section.packages {
    padding-top: 36px;
  }

  .section.packages-faqs {
    padding-top: 51px;
    padding-bottom: 92px;
  }

  .section.packages-testimonials {
    padding-top: 72px;
    padding-bottom: 72px;
  }

  .section.plan {
    padding-top: 29px;
    padding-bottom: 72px;
  }

  .section.contact-faqs {
    padding-top: 72px;
    padding-bottom: 72px;
  }

  .section.contact {
    padding-top: 32px;
    padding-bottom: 91px;
  }

  .section.packages-category {
    padding-top: 36px;
  }

  .section.blog-category {
    padding-top: 36px;
    padding-bottom: 72px;
  }

  .section.utility-page.changelog {
    padding-bottom: 72px;
  }

  .utility-page-wrap {
    padding-right: 16px;
    padding-left: 16px;
  }

  .utility-page-content-password {
    padding: 56px 20px;
  }

  .input {
    height: 60px;
    padding-right: 16px;
    padding-left: 16px;
  }

  .input.blog-newsletter {
    height: 60px;
    padding-right: 16px;
    padding-left: 16px;
  }

  .container-medium-761px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .container-medium-761px.changelog {
    margin-top: -100px;
  }

  .divider.card-testimonial {
    margin-top: 25px;
    margin-bottom: 20px;
  }

  .divider.card-service {
    margin-top: 15px;
    margin-bottom: 15px;
  }

  .divider.card-article-item {
    margin-bottom: 15px;
  }

  .divider.card-article-featured {
    margin-top: 20px;
    margin-bottom: 15px;
  }

  .divider.card-service-page {
    margin-top: 15px;
    margin-bottom: 15px;
  }

  .divider.plan {
    margin-top: 45px;
    margin-bottom: 49px;
  }

  .paragraph.card-service {
    margin-bottom: 15px;
  }

  .paragraph.card-blog-post-hero {
    margin-bottom: 25px;
  }

  .paragraph.card-team-page {
    margin-bottom: 15px;
  }

  .paragraph.card-service-page {
    margin-bottom: 15px;
  }

  .paragraph.faq-content {
    margin-left: 61px;
  }

  .paragraph.card-get-plan {
    margin-bottom: 20px;
  }

  .card.changelog {
    margin-bottom: 30px;
    padding: 40px 20px;
  }

  .card.testimonial {
    margin-bottom: 20px;
  }

  .card.testimonial.last {
    padding-right: 20px;
    padding-left: 20px;
  }

  .card.service {
    padding: 30px 20px 36px;
  }

  .card.article-item-card {
    margin-right: 0px;
    margin-left: 0px;
    padding: 30px 20px 10px;
    border-top-left-radius: 0px;
    border-top-right-radius: 0px;
  }

  .card.value {
    padding: 30px 20px 36px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card.team {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card.article-featured {
    margin-right: 0px;
    margin-left: 0px;
    padding: 30px 20px 16px;
    border-top-left-radius: 0px;
    border-top-right-radius: 0px;
  }

  .card.blog-post-hero {
    max-width: 100%;
    margin-top: 0px;
    padding: 40px 20px;
    border-top-left-radius: 0px;
    border-top-right-radius: 0px;
  }

  .card.about-author {
    margin-top: 30px;
    padding: 40px 20px;
  }

  .card.team-page {
    margin-bottom: 40px;
    padding-right: 20px;
    padding-left: 20px;
  }

  .card.service-page {
    padding: 30px 20px 36px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card.packages {
    padding: 40px 20px;
  }

  .card.faq-wrapper {
    margin-bottom: 20px;
    padding: 40px 20px;
  }

  .card.get-plan-mobile {
    margin-top: 45px;
    padding: 30px 20px 50px;
  }

  .card.contact {
    margin-bottom: 40px;
    padding: 40px 20px;
  }

  .card.default {
    padding: 40px 20px;
  }

  .checkout-form {
    padding-top: 50px;
    padding-bottom: 72px;
  }

  .checkout-block-header {
    padding-right: 20px;
    padding-left: 20px;
  }

  .checkout-block-content {
    padding-right: 20px;
    padding-left: 20px;
  }

  .title.footer-nav-title {
    margin-bottom: 25px;
  }

  .title.home-hero {
    max-width: 400px;
  }

  .title.card-testimonial {
    margin-bottom: 10px;
  }

  .title.card-team {
    margin-bottom: 6px;
  }

  .title.card-blog-post-hero {
    margin-bottom: 10px;
    font-size: 28px;
  }

  .title.card-team-page-name {
    font-size: 28px;
  }

  .title.plan {
    margin-right: 8px;
    font-size: 34px;
  }

  .title.card-get-plan {
    font-size: 20px;
  }

  .title.category {
    margin-right: 8px;
    font-size: 34px;
  }

  .title.careers-hero {
    max-width: 358px;
    margin-right: auto;
    margin-left: auto;
  }

  .title.careers-perks {
    max-width: 268px;
    margin-bottom: 35px;
  }

  .title.careers-team {
    margin-bottom: 35px;
  }

  .title.card-careers-team {
    margin-bottom: 6px;
  }

  .title.neutral-100.cta {
    margin-bottom: 25px;
    font-size: 25px;
  }

  .split-content.home-services-left {
    max-width: 400px;
  }

  .split-content.testimonials-left {
    margin-bottom: 20px;
  }

  .split-content.story-left {
    margin-bottom: 30px;
  }

  .split-content.about-team-left {
    max-width: 400px;
    margin-bottom: 25px;
  }

  .split-content.mission-right {
    margin-bottom: 30px;
  }

  .split-content.more-doctors-left {
    margin-right: 0px;
  }

  .split-content.more-doctors-right {
    margin-bottom: 0px;
  }

  .split-content.contact-right {
    margin-bottom: 40px;
  }

  .checkout-required-text {
    font-size: 18px;
  }

  .order-item {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .image-wrapper.order-item-image {
    margin-right: 0px;
    margin-bottom: 15px;
  }

  .image-wrapper.card-service {
    width: 83px;
    height: 83px;
    min-width: 83px;
    margin-bottom: 20px;
    border-radius: 20px;
  }

  .image-wrapper.article-item-image {
    margin-bottom: 0px;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 0px;
  }

  .image-wrapper.card-team {
    max-width: 100%;
  }

  .image-wrapper.article-featured {
    margin-bottom: 0px;
    border-radius: 20px 20px 0px 0px;
  }

  .image-wrapper.about-author {
    margin-right: 0px;
  }

  .image-wrapper.card-service-page {
    width: 83px;
    height: 83px;
    min-width: 83px;
    border-radius: 20px;
  }

  .image-wrapper.cart-item-image {
    margin-right: 0px;
    margin-bottom: 15px;
  }

  .image.home-hero {
    height: 400px;
  }

  .image.home-features {
    margin-top: 60px;
    margin-bottom: -100px;
  }

  .image.card-testimonial-about {
    width: 73px;
    height: 73px;
    min-width: 73px;
    margin-right: 10px;
  }

  .image.home-feature-icon {
    width: 27px;
    height: 27px;
    min-width: 27px;
    margin-right: 8px;
  }

  .image.value {
    margin-bottom: 15px;
  }

  .image.blog-post-main-image {
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 0px;
  }

  .image.card-team-page {
    width: 229px;
    height: 229px;
    min-width: auto;
    margin-bottom: 20px;
    border-radius: 20px;
  }

  .image.package-item-feature-icon {
    margin-right: 6px;
  }

  .image.plan {
    width: 82px;
    height: 82px;
    min-width: 82px;
    margin-bottom: 10px;
    border-radius: 20px;
  }

  .image.plan-feature-icon {
    width: 27px;
    height: 27px;
    min-width: 27px;
    margin-right: 6px;
  }

  .image.card-get-plan-icon {
    width: 65px;
    height: 65px;
    min-width: 65px;
    margin-bottom: 20px;
  }

  .image.contact {
    height: 320px;
  }

  .image.contact-link-icon {
    margin-right: 10px;
  }

  .image.styleguide-icon {
    width: 60px;
    height: 60px;
    min-width: 60px;
  }

  .image.card-careers-perk-icon {
    width: 60px;
    min-height: 60px;
    min-width: 60px;
    margin-right: 0px;
    margin-bottom: 15px;
    border-radius: 15px;
  }

  .image.card-careers-team {
    max-width: 211px;
    margin-bottom: 28px;
  }

  .image.cta {
    width: 100%;
    margin-bottom: -228px;
  }

  .order-item-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .cart-button {
    margin-right: 0px;
  }

  .brand {
    margin-right: 10px;
  }

  ._2-buttons.cta-2 {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  ._2-buttons.home-hero {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .content-top.home-services-content-top {
    margin-bottom: 130px;
  }

  .content-top.about-author {
    margin-bottom: 15px;
    padding-bottom: 0px;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .content-top.more-doctors {
    margin-bottom: 40px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .cta-1-wrapper {
    padding-top: 40px;
    padding-right: 30px;
    padding-left: 30px;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    border-radius: 20px;
  }

  .cta-2-wrapper {
    padding-top: 50px;
    padding-right: 30px;
    padding-left: 30px;
  }

  .container-small-596px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .card-testimonial-about-name {
    margin-bottom: 6px;
  }

  .home-feature-wrapper {
    font-size: 18px;
  }

  .slider-right-arrow {
    top: -100px;
  }

  .slider-left-arrow {
    top: -100px;
  }

  .bg.home-hero {
    height: 430px;
    border-bottom-left-radius: 100px;
  }

  .bg.about-hero-outside {
    height: 20%;
  }

  .bg.contact {
    height: 350px;
    border-bottom-left-radius: 100px;
  }

  .header-home-hero-wrapper {
    overflow: hidden;
  }

  .section-blog-grid {
    grid-row-gap: 30px;
  }

  .article-item-wrapper {
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .card-article-item-about-wrapper {
    -webkit-flex-wrap: wrap-reverse;
    -ms-flex-wrap: wrap-reverse;
    flex-wrap: wrap-reverse;
  }

  .card-article-item-date {
    margin-bottom: 20px;
  }

  .badge {
    padding: 10px 20px;
  }

  .badge.card-article-item {
    margin-bottom: 20px;
  }

  .badge.card-article-featured {
    margin-bottom: 20px;
  }

  .footer-main-content-wrapper {
    max-width: 100%;
  }

  .small-print {
    font-size: 16px;
  }

  .footer-social-media-grid {
    -ms-grid-row-align: stretch;
    align-self: stretch;
    grid-template-columns: repeat(auto-fit, 38px);
  }

  .footer-nav-box {
    margin-bottom: 30px;
  }

  .footer-nav-links {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .shape.home-hero {
    left: -220px;
    bottom: 23px;
    width: auto;
  }

  .shape.home-services-1 {
    left: -204px;
    top: -107px;
  }

  .shape.home-services-2 {
    right: -217px;
  }

  .shape.home-features-1 {
    top: 6px;
    right: -132px;
  }

  .shape.home-features-2 {
    left: -258px;
    bottom: -92px;
  }

  .shape.home-mission {
    top: -47px;
    right: 181px;
  }

  .shape.cta-2 {
    top: -166px;
    right: 235px;
  }

  .shape.testimonial-1 {
    left: -147px;
    top: 194px;
  }

  .shape.testimonial-2 {
    left: 171px;
    top: 689px;
    width: 90%;
  }

  .shape.testimonial-3 {
    right: -124px;
    bottom: -80px;
  }

  .shape._2-cta-1 {
    left: -208px;
  }

  .shape._2-cta-2 {
    left: 226px;
  }

  .shape.about-hero-1 {
    left: -329.5px;
  }

  .shape.about-hero-2 {
    right: -274px;
  }

  .shape.story {
    left: -258px;
  }

  .shape.mission {
    right: -256px;
  }

  .shape.values-1 {
    left: -75px;
    bottom: -86px;
  }

  .shape.values-2 {
    bottom: 375px;
  }

  .shape.values-3 {
    top: -50px;
  }

  .shape.about-team-1 {
    left: -146px;
    bottom: 308px;
  }

  .shape.about-team-2 {
    right: -217px;
  }

  .shape.team-members-1 {
    left: -121px;
    top: 346px;
  }

  .shape.team-members-2 {
    top: -87px;
    right: -215px;
  }

  .shape.team-members-3 {
    right: -124px;
    bottom: -100px;
  }

  .shape.team-page-1 {
    top: 258px;
  }

  .shape.team-page-2 {
    top: -59px;
  }

  .shape.services-1 {
    left: -108px;
    bottom: -118px;
  }

  .shape.services-2 {
    top: 97px;
    right: -122px;
  }

  .shape.packages-2 {
    right: -170px;
  }

  .shape.faqs {
    top: 404px;
    right: -159px;
  }

  .shape.contact-1 {
    left: -168px;
    top: 113px;
  }

  .shape.contact-2 {
    right: -145px;
    bottom: 40px;
  }

  .shape.checkout-1 {
    left: -189px;
    bottom: -213px;
  }

  .shape.checkout-2 {
    left: 37px;
    top: -279px;
  }

  .shape.checkout-3 {
    right: -172px;
    bottom: -221px;
  }

  .shape.password-2 {
    left: -149px;
  }

  .shape.not-found-1 {
    left: -184px;
    top: 35px;
  }

  .shape.not-found-2 {
    right: -187px;
    bottom: 39px;
  }

  .shape.blog-newsletter-1 {
    left: -208px;
  }

  .shape.blog-newsletter-2 {
    left: 226px;
  }

  .shape.blog-post-1 {
    left: -148px;
    top: -54px;
  }

  .shape.blog-post-2 {
    top: -41.1719px;
    right: -130px;
  }

  .container-medium-926px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .container-medium-926px.about-hero {
    margin-bottom: 50px;
  }

  .values-title-wrapper {
    max-width: 380px;
  }

  .values-grid {
    grid-row-gap: 20px;
  }

  .about-team-grid {
    grid-row-gap: 30px;
  }

  .card-team-content {
    padding: 20px 20px 30px;
  }

  .blog-hero-title-wrapper {
    margin-bottom: 25px;
  }

  .card-article-featured-about-wrapper {
    -webkit-flex-wrap: wrap-reverse;
    -ms-flex-wrap: wrap-reverse;
    flex-wrap: wrap-reverse;
  }

  .blog-grid {
    grid-row-gap: 30px;
  }

  .card-article-featured-date {
    margin-bottom: 20px;
  }

  .blog-category-wrapper {
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .pagination-button {
    display: block;
    padding: 24px 16px;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .container-medium-992px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .blog-post-hero-wrapper {
    margin-bottom: 40px;
  }

  .rich-text h2 {
    margin-bottom: 10px;
  }

  .rich-text ul {
    margin-bottom: 30px;
    padding-left: 20px;
  }

  .rich-text h3 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .rich-text h4 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .rich-text ol {
    margin-bottom: 30px;
    padding-left: 20px;
  }

  .rich-text blockquote {
    margin-top: 40px;
    margin-bottom: 50px;
  }

  .rich-text h5 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .rich-text h6 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .rich-text figure {
    margin-top: 30px;
    margin-bottom: 40px;
  }

  .about-author-contact-grid {
    margin-bottom: 20px;
  }

  .about-author-name-link-wrapper {
    margin-bottom: 20px;
  }

  .container-medium-806px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .team-grid {
    grid-row-gap: 30px;
  }

  .container-medium-975px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .card-team-page-rol {
    margin-bottom: 10px;
    font-size: 16px;
  }

  .container-medium-692px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .package-grid-item {
    padding-top: 30px;
    padding-bottom: 30px;
  }

  .package-item-features-grid {
    margin-bottom: 35px;
  }

  .package-item-feature-wrapper {
    font-size: 16px;
  }

  .package-item-price {
    font-size: 21px;
  }

  .faqs-grid {
    grid-row-gap: 20px;
  }

  .faq-icon-wrapper {
    width: 45px;
    height: 45px;
    min-width: 45px;
    margin-right: 15px;
  }

  .space.faq-content {
    height: 10px;
  }

  .plan-title-wrapper {
    margin-bottom: 10px;
  }

  .plan-feature-wrapper {
    font-size: 18px;
  }

  .card-get-plan-price {
    font-size: 25px;
  }

  .select {
    height: 60px;
  }

  .select-wrapper {
    height: 60px;
    padding-right: 16px;
    padding-left: 16px;
  }

  .card-get-plan-title-wrapper {
    margin-bottom: 10px;
  }

  .text-area {
    padding: 23px 16px;
  }

  .contact-title-wrapper {
    margin-bottom: 25px;
  }

  .contact-link {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .contact-link-text {
    font-size: 18px;
  }

  .contact-links-grid-mobile {
    -ms-grid-rows: auto auto;
    grid-template-rows: auto auto;
  }

  .category-title-wrapper.plans-category {
    margin-bottom: 10px;
  }

  .changelog-version {
    width: 72px;
    height: 72px;
    min-width: 72px;
    margin-bottom: 15px;
  }

  .rich-text-styleguide h2 {
    margin-bottom: 10px;
  }

  .rich-text-styleguide ul {
    margin-bottom: 30px;
    padding-left: 20px;
  }

  .rich-text-styleguide h3 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .rich-text-styleguide h4 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .rich-text-styleguide ol {
    margin-bottom: 30px;
    padding-left: 20px;
  }

  .rich-text-styleguide blockquote {
    margin-top: 40px;
    margin-bottom: 50px;
  }

  .rich-text-styleguide h5 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .rich-text-styleguide h6 {
    margin-top: 25px;
    margin-bottom: 10px;
  }

  .dropdown-arrow {
    font-size: 8px;
  }

  .mega-menu {
    margin-right: 40px;
    margin-bottom: 10px;
  }

  .mega-menu.last {
    margin-right: 0px;
  }

  .menu-grid-wrapper {
    padding-top: 28px;
  }

  .header-dropdown-toggle {
    font-size: 25px;
  }

  .mega-menu-title {
    margin-bottom: 25px;
  }

  .menu-grid {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .dropdown-list {
    width: 100%;
  }

  .cart-item-quantity {
    height: 60px;
    padding-right: 16px;
    padding-left: 16px;
  }

  .cart-item-wrapper {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .cart-item {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .cart-footer {
    padding-right: 16px;
    padding-bottom: 20px;
    padding-left: 16px;
  }

  .cart-header {
    padding-right: 16px;
    padding-left: 16px;
  }

  .cart-list {
    padding-right: 16px;
    padding-left: 16px;
  }

  .empty-state.cart {
    padding-right: 16px;
    padding-left: 16px;
  }

  .blog-newsletter-wrapper {
    padding-top: 50px;
    padding-right: 30px;
    padding-left: 30px;
  }

  .blog-newsletter-form {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .header-alternative {
    padding-top: 35px;
    padding-bottom: 35px;
  }

  .image-wrapper-2.careers-hero-1 {
    border-radius: 20px;
  }

  .image-wrapper-2.careers-hero-2 {
    border-radius: 20px;
  }

  .careers-hero-images-wrapper {
    margin-bottom: 40px;
    padding-top: 58px;
  }

  .container-default-2 {
    padding-right: 16px;
    padding-left: 16px;
  }

  .card-2 {
    border-radius: 25px;
  }

  .card-2.careers-perk {
    padding: 28px 25px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .card-2.careers-team {
    padding: 25px 25px 42px;
  }

  .container-medium-874px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .container-medium-874px.careers-hero {
    margin-bottom: 40px;
  }

  .button-primary-2 {
    display: block;
    padding-right: 15px;
    padding-left: 15px;
  }

  .paragraph-large-2.careers-hero {
    margin-bottom: 30px;
  }

  .section-2 {
    padding-top: 92px;
    padding-bottom: 92px;
  }

  .section-2.careers-hero {
    padding-top: 45px;
  }

  .section-2.careers-team {
    padding-top: 72px;
    padding-bottom: 72px;
  }

  .section-2.cta {
    padding-top: 51px;
    padding-bottom: 51px;
  }

  .container-large-1112px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .card-careers-team-position {
    font-size: 16px;
  }

  .container-large-1064px {
    padding-right: 16px;
    padding-left: 16px;
  }

  .card-careers-team-name {
    font-size: 18px;
  }

  .container {
    padding-right: 16px;
    padding-left: 16px;
  }

  .text-block {
    margin-right: -85px;
    padding-right: 0px;
  }

  .container-default-3 {
    margin-top: 0px;
    padding-right: 16px;
    padding-left: 16px;
  }

  .button-primary-3 {
    display: block;
    padding-right: 15px;
    padding-left: 15px;
  }

  .button-primary-3.download-app {
    width: auto;
    padding-right: 15px;
    padding-left: 15px;
  }

  .button-primary-3.download-app._2-buttons-button {
    margin-right: 0px;
  }

  .button-primary-3.download-app._2-buttons-button {
    margin-right: 0px;
  }

  ._2-buttons-2 {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    margin-bottom: 0px;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  ._2-buttons-2.cta {
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .cta-wrapper {
    padding-bottom: 42px;
  }

  .cta-main-wrapper {
    border-radius: 30px;
  }

  .cta-content {
    margin-bottom: 40px;
  }

  .cta-bg-wrapper {
    border-radius: 30px;
  }
}

#w-node-_64e9950f-9d38-3066-3102-eb9e0b8a3cf5-d456963e {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-e36d5f8c-7fa0-0c32-d96c-642694cdce01-d456963e {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
  -ms-grid-column-align: start;
  justify-self: start;
}

@media screen and (max-width: 767px) {
  #w-node-_64e9950f-9d38-3066-3102-eb9e0b8a3cf5-d456963e {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }

  #w-node-e36d5f8c-7fa0-0c32-d96c-642694cdce01-d456963e {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }
}

@media screen and (max-width: 479px) {
  #w-node-e36d5f8c-7fa0-0c32-d96c-642694cdce01-d456963e {
    -ms-grid-column-align: stretch;
    justify-self: stretch;
  }
}

@font-face {
  font-family: 'Icons Hospital Template';
  src: url('../fonts/icons-hospital-template.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Plus Jakarta Display';
  src: url('../fonts/PlusJakartaDisplay-Regular.otf') format('opentype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Plus Jakarta Display';
  src: url('../fonts/PlusJakartaDisplay-Bold.otf') format('opentype');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Plus Jakarta Display';
  src: url('../fonts/PlusJakartaDisplay-Medium.otf') format('opentype');
  font-weight: 500;
  font-style: normal;
  font-display: swap;
}
