# golf-website-clone
made a clone website of a golf-website 

Learned Topics --

-- CSS Properties --
  ::selection {}
  ::-webkit-scrollbar {}
  ::-webkit-scrollbar-thumb {}

  blur { transition: all linear 0.4s; }
  -webkit-text-stroke: 1.5px #95c11e;
   white-space: nowrap;
    overflow-x: auto;
    overflow-y: hidden;
    position: relative;
    transform: rotate3d(-1, 1, 0, 20deg);

Animations --
  animation-name: scroll;
    animation-duration: 40s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;

-- JS Topics -- 
document.addEventListener("mousemove", function (dets) {
  cursor.style.left = dets.x + "px";
  cursor.style.top = dets.y + "px";
  blur.style.left = dets.x - 250 + "px";
  blur.style.top = dets.y - 250 + "px";
});

elem.addEventListener("mouseenter", function () {}
  elem.addEventListener("mouseleave", function () {}

gsap.from("#page4 h1", {
  y: 50,
  scrollTrigger: {
    trigger: "#page4 h1",
    scroller: "body",
    // markers:true,
    start: "top 75%",
    end: "top 70%",
    scrub: 3,
  },
