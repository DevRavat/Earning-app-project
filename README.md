# Gradient Drawable Linear card Code (with set redius and Elevation) 

android.graphics.drawable.GradientDrawable gd1 = new android.graphics.drawable.GradientDrawable(android.graphics.drawable.GradientDrawable.Orientation.LEFT_RIGHT, new int[]{
0xFF2979FF,
0xFFFF5100
});
gd1.setCornerRadius(40f);
linearname.setElevation(0f);
linearname.setBackgroundDrawable(gd1);
