# KP
    double f(double x) {
        if (x < 0.5) {
            return log(1 + fabs(x)) / (1 + exp(-x));
        } else if (x < 6) {
            return (sin(x*x) * cos(x)) / sqrt(1 + pow(x, 6));
        } else {
            return cosh(3*x - 1);
        }
