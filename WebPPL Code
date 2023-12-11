Image 1 Q1

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  //looking at first image from each person's observation because of index 0; change this index for different image
  return trueClass[0];
};

var dist11 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist11)
~~~~

Image 1 Q2

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  //looking at first image from each person's observation because of index 0; change this index for different image
  return trueClass[0];
};

var dist12 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist12)
~~~~

Image 1 Q3

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], 
                    ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz']];

var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  //looking at first image from each person's observation because of index 0; change this index for different image
  return trueClass[0];
};

var dist13 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist13)
~~~~

Image 2 Q1

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[1];
};

var dist11 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist11)
~~~~

Image 2 Q2

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[1];
};

var dist12 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist12)
~~~~

Image 2 Q3

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], 
                    ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz']];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[1];
};

var dist13 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist13)
~~~~

Image 3 Q1

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[2];
};

var dist11 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist11)
~~~~

Image 3 Q2

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[2];
};

var dist12 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist12)
~~~~

Image 3 Q3

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], 
                    ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz']];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[2];
};

var dist13 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist13)
~~~~

Image 4 Q1

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[3];
};

var dist11 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist11)
~~~~

Image 4 Q2

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[3];
};

var dist12 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist12)
~~~~

Image 4 Q3

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], 
                    ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz']];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[3];
};

var dist13 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist13)
~~~~

Image 5 Q1

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[4];
};

var dist11 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist11)
~~~~

Image 5 Q2

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[4];
};

var dist12 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist12)
~~~~

Image 5 Q3

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], 
                    ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz']];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[4];
};

var dist13 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist13)
~~~~

Image 6 Q1

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[5];
};

var dist11 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist11)
~~~~

Image 6 Q2

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[5];
};

var dist12 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist12)
~~~~

Image 6 Q3

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], 
                    ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz']];

var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[5];
};

var dist13 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist13)
~~~~

Image 7 Q1

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};


var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[6];
};

var dist11 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist11)
~~~~

Image 7 Q2

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
  ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'],
];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[6];
};

var dist12 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist12)
~~~~

Image 7 Q3

~~~~
var classes = ["Flitz", "NotFlitz"];

var prior = function (p) {
  return Categorical({ vs: classes, ps: [p, 1-p] });
};

var observations = [['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz'], ['Flitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'Flitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], 
                    ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz'], ['NotFlitz', 'NotFlitz', 'NotFlitz', 'NotFlitz', 'Flitz', 'NotFlitz', 'NotFlitz']];


var model = function () {
  //looking per person
  var trueClass = repeat(7, function() {uniform({a:0, b:1})});
  map(function (personObservations) {
    //looking per observation
    var logProb = mapIndexed(function (i, observation) {
      observe(prior(trueClass[i]), observation)
    }, personObservations);
  }, observations);
  return trueClass[6];
};

var dist13 = Infer({ method: 'MCMC', samples: 1000}, model)
viz(dist13)
~~~~
